## Implementing-a-CNN-from-scratch-and-using-it-on-MNIST-digit-dataset

libraries used : kagglehub, tensorflow, matplotlib

### CNN architecture : 

INPUT -> CONV -> ReLU -> POOL -> CONV -> Relu -> POOL -> FLATTEN -> FC -> DO -> FC -> OUTPUT (with softmax activation)

FC = Fully Connected Layer     
DO = Dropout Regularization

Note : I have not provided dataset link because we are directly downloading it through kagglehub during runtime and preprocessing it  ( I prefer this method to manually downloading it locally )
