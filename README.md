# Multi-class Image Classification (TensorFlow)
## SIGNS Dataset

![alt text](https://github.com/MerEsf/Neural_Networks_Deep_Learning/blob/master/Photos/hands.png)

### Approach:
One Hot Encodings, SoftMax Function, Xavier Initialization for weights and Zero Initialization for biases

### Results:
![alt text](https://github.com/MerEsf/Neural_Networks_Deep_Learning/blob/master/Photos/download.png)

# Binary Image Classification
## 1) Planar data classification
The data looks like a "flower" with some red (label y=0) and some blue (y=1) points. The goal is to build a model to fit this data.


![alt text](https://github.com/MerEsf/Neural-Networks-and-Deep-Learning-Coursera-Course/blob/master/Photos/Planar.png)


### Approach:
2-class (binary) classification neural network with a single hidden layer
### Results:
#### Logistic Regression:
![alt text](https://github.com/MerEsf/Neural_Networks_Deep_Learning/blob/master/Photos/Logist%20Palanr.png)

#### Neural Network (5 hidden layer):
![alt text](https://github.com/MerEsf/Neural_Networks_Deep_Learning/blob/master/Photos/result%20planar%205.png)

### Learning outcomes:
-	Accuracy of the neural network ( around 90%) is high compared to Logistic Regression (47%) (as the dataset is not linearly separable). So the model has learned the leaf patterns of the flower.
- The larger models (with more hidden units) are able to fit the training set better, until eventually the largest models overfit the data. 
- The best hidden layer size seems to be around n_h = 5. Indeed, a value around here seems to  fits the data well without also incurring noticeable overfitting.
#### Reference:
- http://scs.ryerson.ca/~aharley/neural-networks/
- http://cs231n.github.io/neural-networks-case-study/


## 2) Cat vs non-Cat Classification
Building a deep network, and applying it to cat vs non-cat classification (supervised learning)
### Approach:
2-class (binary) classification neural network (2-layer and 4-layer)
### Results:
#### 2-layer (72% accuracy):
![alt text](https://github.com/MerEsf/Neural_Networks_Deep_Learning/blob/master/Photos/2%20layer.png)
#### 4-layer (80% accuracy):
![alt text](https://github.com/MerEsf/Neural_Networks_Deep_Learning/blob/master/Photos/4%20layer.png)
