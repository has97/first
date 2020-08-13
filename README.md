### Introduction
- This model used to classify the facial expression of a person. The expressions that is detected include happiness,sad,angry,surprise and Neutral Expression.
### Install
```
pip install opencv
pip install tensorflow
pip install numpy
pip install matplotlib
```
### Model used
The Model used for this project is MobileNet with pre-trained weights (imagenet) and fine tuned this Network to obtain an accuracy of 66%. Image Augmentations are applied to obtain a better result for classification. The details regarding model training can be seen in modeltraining python notebook in the repository. 

### How to use it
- First Download the models weights (.h5) and model architecture (.json) in the repository.
- Change the path to (.h5) file and (.json) file in your computer
- Download the ipynb notebook (face expression)

### Accuracy
 The model is trained to detect Facial Expression at a validation accuracy of 66%.


