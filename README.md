# Image Classification with CIFAR-10 Dataset using PyTorch

## Overview of the Dataset
* The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class.
* There are 50000 training images and 10000 test images.
* The dataset is divided into five training batches and one test batch, each with 10000 images.
* The test batch contains exactly 1000 randomly-selected images from each class.
* The classes of the dataset are :
1. airplane
2. automobile
3. bird
4. cat
5. deer
6. dog
7. frog
8. horse
9. ship
10. truck
## Models used to train
* VGG16 : Used the pretrained model (Transfer Learning) with the help of torchvision.models.
* LeNet : Made a LeNet from Scratch and tried to optimize it.
* ResNet : Used the pretrained model (Transfer Learning) with the help of torchvision.models.
* GoogleNet : Used the pretrained model (Transfer Learning) with the help of torchvision.models.
## Results
1. VGG16 : Accuracy on Trainset = 45.096 ,Accuracy on Testset = 45.46
2. LeNet : Accuracy on Trainset = 60.57 ,Accuracy on Testset = 70.97
3. ResNet : Accuracy on Trainset = 57.182 ,Accuracy on Testset = 56.51
4. GoogleNet : Accuracy on Trainset = 52.544 ,Accuracy on Testset = 52.56
## Conclusion
These are illustrations of simple models hence the accuracy are a little lower than what can actually be obtained. It can be further 
tested using different optimizers ,loss functions and even by changing the values of number of epochs, batch size, learning rate etc.  
