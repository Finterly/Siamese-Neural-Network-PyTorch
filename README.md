# SiameseNN
Siamese neural network for protein remote homology 

The following architecture was built using Pytorch:

<img src="https://github.com/Finterly/SiameseNN/blob/master/img/Picture1.png" height="250">


The final model consisted of twin four-layer convolutional neural networks:  

<img src="https://github.com/Finterly/SiameseNN/blob/master/img/Picture2.png" height="280">


Our model was validated using stratified 5-fold cross-validation:
<img src="https://github.com/Finterly/SiameseNN/blob/master/img/Picture3.png" height="280">

SiameseNN Model performance on Saripella PFAM, GENE3D, and SUPFAM datasets compared to existing methods: 
<img src="https://github.com/Finterly/SiameseNN/blob/master/img/Capture.PNG" width="300" height="270">

<img src="https://github.com/Finterly/SiameseNN/blob/master/img/Capture2.PNG" width = "300" height="270">

<img src="https://github.com/Finterly/SiameseNN/blob/master/img/Capture3.PNG" width = "300" height="270">

SiameseNN Model was found to have higher precision and lower FPR. 
