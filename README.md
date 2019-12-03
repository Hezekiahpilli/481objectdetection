Project done by: Hezekiah Pilli

Contact: hezekiahpilli@csu.fullerton.edu

Please find below the steps to run the Object detection algorithm.

•	Here I will be using the YOLOv3 algorithm for this Project.
•	Since it is a computer vision problem, I intended to use Google colab (like Jupyter) as it is useful for good visualization than a standalone .py file.
•	The code can be viewed as AI_project.ipynb.

• Dataset used for training is PASCAL VOC-2012
https://pjreddie.com/

•	The code is mainly divided into three parts. Pre-requisites stage, training stage, and prediction stage. Please follow the steps to run/test the predictions.

• Model Training has been done in google colab. 
1. First trained for 50 epochs with batch size=32.
2. Training samples =5700 validated on 500 images.
3. Later retrained for few more times for more reduce of loss with decreased batch size to 10.

*In the preprocessing section the code that reads Darknet config and weights and converts back into Keras model with Tensorflow backend was provided by Keras official sources i have used the required code and made changes with respect to my code.As it was just a framework level problem which was handled by keras.

Please click on this below link to get yolo prerequisite folder, which contains few test images and config files needed during the training. Add it to your drive.

https://drive.google.com/open?id=1SNnx0E0FsWkG7tVumWoysxOlPa5rvq94

Please click on this below link to get a trained model pickle file which, is used for prediction. Add it to your drive.

https://drive.google.com/open?id=15sPBUhfsD_4hpCA6TA4EI0PMeNQP5QVH


Steps to run :

1.	The AI_project.ipynb notebook contains all the necessary steps right above each cell block to execute the code. Before that please ensure the above prerequisite files are added to your google drive.

2.	Please continue with the program execution with AI_project.ipynb, all the required steps are clearly mentioned in the code on top of each cell block.
