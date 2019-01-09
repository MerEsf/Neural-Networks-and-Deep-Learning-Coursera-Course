# Neural Networks and Deep Learning Coursera Course
Neural Networks and Deep Learning Course on Coursera, part of Deep Learning Specialization offered by Deeplearning.ai

## Planar data classification with a hidden layer
The data looks like a "flower" with some red (label y=0) and some blue (y=1) points. The goal is to build a model to fit this data.

### Approach:
2-class (binary) classification neural network with a single hidden layer with 5 nodes
### Learning outcomes:
-	Accuracy of the neural network ( around 90%) is high compared to Logistic Regression (47%) (as the dataset is not linearly separable). So the model has learnt the leaf patterns of the flower!
- The larger models (with more hidden units) are able to fit the training set better, until eventually the largest models overfit the data. 
- The best hidden layer size seems to be around n_h = 5. Indeed, a value around here seems to  fits the data well without also incurring noticeable overfitting.




