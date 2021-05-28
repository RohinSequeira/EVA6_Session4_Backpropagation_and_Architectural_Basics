# MNIST Architecture to achieve 99.4% Accuracy

### Requirement:
#### Build a MNIST digit identifier such that it achieves the following:
1. 99.4% validation accuracy.   
2. Less than 20k Parameters.   
3. Use an of the concepts covered.   
4. Less than 20 Epochs.  
5. Have used BN, Dropout, a Fully connected layer, have used GAP.  

### Approaches

We have adopted two approaches to achieve the target of 99.4 % accuracy. One using Average pooling and one with Max pooling, before the fully connected layer. The reason for talking about the one with Max pooling is because it has provided us with the best Accuracy and least loss.


## Approach 1: With Avg pooling before fully connected layer

### Architecture




### Model Summary



### Training Logs



### Losses and Accuracy




## Approach 2: With Max pooling before fully connected layer

### Architecture

![image](https://user-images.githubusercontent.com/31658286/120028032-c65ea300-c011-11eb-8774-54f017fa96eb.png)



### Model Summary



### Training Logs

```Epoch 1 : 
Train set: Average loss: 0.0967, Accuracy: 94.61

Test set: Average loss: 0.064, Accuracy: 98.34

Epoch 2 : 
Train set: Average loss: 0.0496, Accuracy: 98.63

Test set: Average loss: 0.043, Accuracy: 98.75

Epoch 3 : 
Train set: Average loss: 0.0111, Accuracy: 98.95

Test set: Average loss: 0.035, Accuracy: 98.89

Epoch 4 : 
Train set: Average loss: 0.0019, Accuracy: 99.12

Test set: Average loss: 0.029, Accuracy: 99.08

Epoch 5 : 
Train set: Average loss: 0.0017, Accuracy: 99.22

Test set: Average loss: 0.028, Accuracy: 99.09

Epoch 6 : 
Train set: Average loss: 0.0136, Accuracy: 99.27

Test set: Average loss: 0.023, Accuracy: 99.22

Epoch 7 : 
Train set: Average loss: 0.0241, Accuracy: 99.36

Test set: Average loss: 0.021, Accuracy: 99.28

Epoch 8 : 
Train set: Average loss: 0.0014, Accuracy: 99.67

Test set: Average loss: 0.018, Accuracy: 99.47

Epoch 9 : 
Train set: Average loss: 0.0186, Accuracy: 99.76

Test set: Average loss: 0.017, Accuracy: 99.45

Epoch 10 : 
Train set: Average loss: 0.0002, Accuracy: 99.82

Test set: Average loss: 0.016, Accuracy: 99.49

Epoch 11 : 
Train set: Average loss: 0.0015, Accuracy: 99.84

Test set: Average loss: 0.015, Accuracy: 99.48

Epoch 12 : 
Train set: Average loss: 0.0034, Accuracy: 99.88

Test set: Average loss: 0.015, Accuracy: 99.48

Epoch 13 : 
Train set: Average loss: 0.0007, Accuracy: 99.88

Test set: Average loss: 0.016, Accuracy: 99.47

Epoch 14 : 
Train set: Average loss: 0.0058, Accuracy: 99.91

Test set: Average loss: 0.016, Accuracy: 99.46

Epoch 15 : 
Train set: Average loss: 0.0001, Accuracy: 99.91

Test set: Average loss: 0.015, Accuracy: 99.47

Epoch 16 : 
Train set: Average loss: 0.0040, Accuracy: 99.91

Test set: Average loss: 0.015, Accuracy: 99.50

Epoch 17 : 
Train set: Average loss: 0.0014, Accuracy: 99.93

Test set: Average loss: 0.015, Accuracy: 99.46

Epoch 18 : 
Train set: Average loss: 0.0024, Accuracy: 99.93

Test set: Average loss: 0.015, Accuracy: 99.49

Epoch 19 : 
Train set: Average loss: 0.0026, Accuracy: 99.93

Test set: Average loss: 0.015, Accuracy: 99.44

Epoch 20 : 
Train set: Average loss: 0.0123, Accuracy: 99.93

Test set: Average loss: 0.015, Accuracy: 99.46
```

### Losses and Accuracy

![Loss](https://user-images.githubusercontent.com/31658286/120024596-11c28280-c00d-11eb-9a89-f5c849f6b895.png)


![Accuracy](https://user-images.githubusercontent.com/31658286/120024703-34549b80-c00d-11eb-8e6f-b252c3da9f5e.png)



### Collaborators:

Abhiram Gurijala  
Arijit Ganguly  
Rohin Sequeira  
