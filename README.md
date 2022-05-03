# main_project
Automated bot for vehicle Tracking and license plate Detection for    Company Entry and Exit

Liscense plate detection Main modules:-
1. Dataset Collection
2. Data Preprocessing
3. Model Creation
4. Model Training
5. Model Testing

Dataset Collection:-
A collection of instances is a dataset and when working with machine learning methods we typically need a few datasets for different purposes. 
In our proposed system we uses the AOLP dataset that has vehicle images in various 
places and distances from the camera.

Data Preprocessing:-
A real-world data generally contains noises,
missing values, and maybe in an unusable format which cannot be directly used for machine learning models. Data preprocessing is required tasks
for cleaning the data and making it suitable for a deep learning model which also increases the accuracy and efficiency of a deep learning model.

Model Creation:-
Modeling in deep learning is an iterative phase we continually train and test deep learning models to discover the best one for the given task. 
In our proposed system, DNN and YOLO algorithm is used as model for training and testing


Model Training:-
The pre-processed data is trained by the model(DNN and YOLO algorithm).
In model training, DNN and YOLO algorithm is used to detect and extract the features of the liscense plate.
 When the features are extracted this extracted features of a vehicles are labelled and stored.


Model Testing:-
A video of the vehicle is collected. Then this video is preprocessed and fed to the model. The model will detect
 and extract the features of the liscense plate and compares it with the information(people name along with their
 vehicle and liscense plate image)in the dataset. If the person is from the company he is permitted to enter the
 entrance otherwise his permission is declined.
