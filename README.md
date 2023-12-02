## Classification of CIFAR10 dataset using a custom model in pytorch

### Dataset: https://www.cs.toronto.edu/~kriz/cifar.html

```bash
10 classes

Data categories:
['airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck']
```


### CNN Model: 

#### Feature Maps:
```bash
conv1 block : convolution + maxpool + batchnorm + relu
conv2 block : convolution + maxpool + batchnorm + relu
conv3 block : convolution + maxpool + batchnorm + relu
```
#### Linear Layers:
```bash
fc1 : fully connected + ReLU
fc2 : fully connected + ReLU
fc3 : fully connected + ReLU
```


### Hyperparameters
```bash
image_size : 3x32x32
epochs : 15
lr     : 0.001
weight decay: 1e-5
```
### Accuracy Obtained

```bash
Final model dev/test accuracy: 78.45%
```