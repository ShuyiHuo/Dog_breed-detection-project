# Dog_breed detection project
 Dog-breed-detection using CNN and transfer learning in PyTorch. 
 
# Project Overview
Dog bread classifier is a popular image classification problem in the computer vision domain.  There are two major tasks in this project. First one is to identify the image given from input is a dog face or human face. Second one is to identify the breed of dog if the input image is dog or identify the resembling dog breed if the input image is human. The main vision is to build a Machine learning pipeline that will take the user-supplied images from real world and output the result of classification. We will use supervised learning in this project to solve the problem. Further, building a web app would be feasible for users to input the image an then get the predicted output. 

The goal of project is building a machine learning model to predict the dog breed or resembling dog breed giving a human face. Two main tasks are human face detector and dog breed detector.

# Refinement:
The custom  CNN model form scratch has accuracy of 18% (151/836) and the loss is 3.4669. Although this model satisfy the benchmarking, the model can be improved more by using transfer learning. To create CNN from transfer learning, I used the Resnet101 which has 101 layers deep and pertained on ImageNet dataset. The performance of model is extremely better then custom CNN from scratch because it has 84% accuracy and  0.5704 loss.

< img src="image/sample1.png" width="40%">
< img src="image/sample2.png" width="40%">
< img src="image/sample3.png" width="40%">
