# Messi-Detection
A TensorFlow approach on a basic convolutional neural network

## Objetive
This repository is aimed to show an easy way to start building convolutional neural networks for computer vision or other data issues.

## Messi-Detection Model
Files in this repository are used to create a convolutional net to predict the presence of the footballer Lionel Messi. <br />
This is a good example of a relative complex task (Done with a small sample), where deep-learning shows it potential. <br />

## Code
The code is written in python3 and it is commented by blocks to improve the understanding. <br />

## Libraries
The python libraries used on the main code are the following: <br />
* Numpy: As the data handler library. <br />
* TensorFlow: As the machine-learning library. <br />
* Matplotlib: To visualize some important images in the process. <br />
* cv2: Used for initial data processing.<br />
* Random: Used for data sorting.<br />
* Pandas: Used for irrelevant taks. <br />

## Preview of the Results:
Model prediction for the following test images: <br />

<img src="Validation Data/Validation/Frenkie.jpeg" width="200"/> 
<img src="Validation Data/Validation/Messi close up.jpg" width="200"/>
<img src="Validation Data/Validation/Messi in game.jpg" width="200"/> 
<img src="Validation Data/Validation/Fake Twin.jpg" width="200"/>
<img src="Validation Data/Validation/cr7.jpg" width="200"/>

Table with Probablities and Result: <br />

Image                              | Estimated Probability | Results
---------------------------------- | --------------------- | ------------------
Frenkie de Jong                    |        0.7489 %       | Probably Not Messi
Lionel Messi close up              |       92.4914 %       | Probably Messi
Lionel Messi close up in game      |       98.1068 %       | Probably Messi
Famous Lionel Messi "Fake Twin"    |        7.9433 %       | Probably Not Messi
Cristiano Ronaldo close up in game |       16.4237 %       | Probably Not Messi

