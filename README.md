# PoseClassifier

A multi class face expression and pose classifier kernel built by using OpenCV and Mediapipe Framework. Pose classification is done by using holistic framework of Mediapipe which covers both the Pose as well as the facemesh. MediaPipe Holistic utilizes the pose, face and hand landmark models in MediaPipe Pose, MediaPipe Face Mesh and MediaPipe Hands respectively to generate a total of 543 landmarks (33 pose landmarks, 468 face landmarks, and 21 hand landmarks per hand). 
First all the landmark points were imported as a csv file. This csv is further trained using different scikit-learn classifier model. The model is then imported as a pickle file found in this repo. Using this pickle file we are able to classify the pose/face expressions. 

## Dependencies
Mediapipe 
scikit-learn
Pandas
Numpy
OpenCV 

## Sample Output

<img width="478" alt="image" src="https://user-images.githubusercontent.com/97725657/210267999-f3a2ea88-d23c-485b-b044-0d3a47eabf95.png">
<img width="478" alt="image" src="https://user-images.githubusercontent.com/97725657/210268314-28ff5f79-1860-476a-8a82-1f2c711e2c2c.png">
<img width="466" alt="image" src="https://user-images.githubusercontent.com/97725657/210268430-998ea914-2cc1-4c1b-a8a0-67a00d9df67c.png">
