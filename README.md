# Training-VGG16-Model-of-pytorch-with-custom-layers
In this work i have modified the pre-trained vgg16 model in pytorch with custom made layers and then train it on CIFAR10 dataset.

##Modification made in vgg16 model 


In the modification part i have freezed all the lower convulational layers and replaced all upper fully connected layers with custom made fully connected layers and then trained the obtained model to utilize the power of original vgg16 model and so to make training of model fast and to obtaine a better accuracy in classification.


