# Leaf Disease Detection and Health Grading System

The goal of this project is to develop an algorithm which can correctly classify infected leaves, based on the infection causing microorganism. The algorithm involves neural networks, image processing and fuzzy logic to correctly determine the output. This project has been completed in MATLAB.

### Artificial Neural Network
The algorithm follows a supervised learning approach to train the network. The technique will automatically extract features from the image during the training process and "learn" it to help classify the image into one of the following 5 categories- Bacteria, Virus, Fungi, Nematodes or Normal. The accuracy of the classification is approximately 83% as seen in the confusion matrix below-
![image](https://user-images.githubusercontent.com/108690286/204669367-cf5b102e-5ae0-4227-8620-c54e657b41f2.png)

### Image Processing
The main objective of image processing is to isolate the infected area of the leaf. This will allow us to determine the healthiness of the leaf later. 
![image](https://user-images.githubusercontent.com/108690286/204670063-92949cf0-ca29-43d6-a22b-0fe85dfea5cd.png)

### Fuzzy Logic
To determin the healthiness of the leaf in percentage, the algorithm follows some rules that have been set in the fuzzy inference system.
![image](https://user-images.githubusercontent.com/108690286/204671046-89fecd58-4e9d-46ae-ae54-5a28b5e9ccb8.png)
