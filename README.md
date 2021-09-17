# CNN-project
Detect the presence of pneumonia using chest x-ray images

What is pneumonia?
Pneumonia is an infection that inflames air sacs in one or both lungs, which may fill with fluid.The infection can be life-threatening to anyone, but particularly to infants, children and people over 65. Pneumonia can prevent your lungs from moving enough oxygen into your bloodstream.

What are its symptoms?
Symptoms include a cough with phlegm or pus, fever, chills and difficulty breathing.

How can we detect it?
-Pneumonia can be detected using Chest X-ray to look for the location and extent of inflammation in your  lungs.
-Blood tests to confirm the infection and to try to identify the germ that is causing your illness.
-Pulse oximetry to measure the oxygen level in your blood. Pneumonia can prevent your lungs from moving  enough oxygen into your bloodstream.

In this Project a CNN model is created that can classify chest X-Ray images as a Pneumonia case or a Normal case.Training a model reduces human errors and time,as it can take a lot of time to check thousands of images real time.

Data set:
The dataset consist of 3 folders: 
-train
-test
-val 
Each consists of normal and pneumonia chest x-ray images as subfolders.Images inside normal are free from any type of pneumonia and images inside pneumonia are either affected by viral or bacterial pneumonia.

Steps followed:

-Dealing with Image data sets.
-Performing Data Processing and Augmentation as and when required.
-Creating and training a Convolutional Neural Network using Tensorflow 2.0 

