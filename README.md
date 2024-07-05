# Accident Detection

## Introduction
This project is trained with images of vehicle collisions and accidents. In the test video, if a collision occurs between vehicles, the application detects it as an accident. Training is done using TensorFlow and the CNN algorithm.

## Observations/Techniques/Analysis

Programming Language – Python Libraries:

Pandas – To read the data from the database 
NumPy – For the mathematical calculations      
cv2- To read the image     
Willow- To process the images    
TensorFlow keras – To create the model
Play sound library - Easy and simple way to play sound files in  python

## Model

- We used CNN (Convolutional Neural Network) Model. The CNN is not a model itself. It is an algorithm, and it consists of many models.
- We used a sequential model from the CNN Algorithm for our project.

## Results

Link for complete ppt file which includes all of the details about project results.

https://docs.google.com/presentation/d/17ykrHopoCucoPVdI_6cVCAKmMlOZEjVn/edit?usp=sharing&ouid=105113173567749343506&rtpof=true&sd=true

## Challenges

- Our Model Works only if two vehicles crashed into each other.
- It can not detect any self-made accidents like falling off the road,flying and crashing on the road without the  interference of  any other vehicle.


## Conclusion


This accident detection project effectively identifies vehicle collisions in videos using a CNN model trained with TensorFlow. While the model accurately detects accidents involving two vehicles, it currently does not recognize single-vehicle incidents or accidents without vehicle interaction.
