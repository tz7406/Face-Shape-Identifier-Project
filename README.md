# Face Shape Identifier
PROJECT TITLE: Face Shape identifier (Square/Round/Oval/Oblong/Heart)

PROJECT DESCRIPTION: This network was trained with 2500 images of 
female celebrity faces categorized into 5 different face shape groups.
The different face shape groups are as follows: square, round, oval,
oblong, and heart. The trained network can take input (e.g. an image 
ofyour face taken by a webcam) and analyze your face shape to see 
which category of face shape you fall in. The model network used for 
this project was ResNet18 for image recognition and classification 
into several categories. 

STEPS TO REPLICATE (ASSUMING MODEL IS ALREADY TRAINED): 
1. Open the connection (with Jetson Nano)
2. Go to the folder containing the dataset and model networks
3. Set the Network (NET) to the trained network that will be used
4. Set the Dataset (DATASET)
5. Run the command to make the network run and analyze an image
6. Open Visual Studio Code and navigate to the folder(s) where the output image is stored
7. Output appears as the original image with the class + percentage in the top left corner

DATASET USED: https://www.kaggle.com/datasets/niten19/face-shape-dataset 

VIDEO DEMONSTRATION OF STEPS TO REPLICATE: https://youtu.be/jb07msipzI4


