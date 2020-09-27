# Convolutional Neural Networks

Image Representation
![image](https://user-images.githubusercontent.com/44740658/94370945-83f66680-0110-11eb-965d-69e869f9bb49.png)
Steps
![image](https://user-images.githubusercontent.com/44740658/94370979-b1431480-0110-11eb-8beb-97b6e6b5d8c5.png)

## Step-1 Convolution
![image](https://user-images.githubusercontent.com/44740658/94371010-e2234980-0110-11eb-825e-a40579a0ee93.png)

### Feature Map
Reduce the size of image(depending on strides)
Detect important features in the image
![image](https://user-images.githubusercontent.com/44740658/94371078-5b22a100-0111-11eb-8175-b20e5ebbc993.png)
Convolutional layer
![image](https://user-images.githubusercontent.com/44740658/94371125-b94f8400-0111-11eb-9936-853f77651e65.png)
Applying filter
![image](https://user-images.githubusercontent.com/44740658/94371160-fca9f280-0111-11eb-845b-6e32d2c0d218.png)
ReLU Layer
Reduce the non-linearity
![image](https://user-images.githubusercontent.com/44740658/94371208-81950c00-0112-11eb-947d-35b8466cc909.png)
Without ReLU
![image](https://user-images.githubusercontent.com/44740658/94371296-0ed86080-0113-11eb-96ba-f6ec8d3f572c.png)
With ReLU
![image](https://user-images.githubusercontent.com/44740658/94371336-7a223280-0113-11eb-8d4e-da31eafe75f0.png)

## Step-2 Pooling
Making the model spacially invariant...getting rid of extra information which might not be useful...also preveents overfitting.
![image](https://user-images.githubusercontent.com/44740658/94373827-94650c00-0125-11eb-8d72-0dd87d79417d.png)
![image](https://user-images.githubusercontent.com/44740658/94373888-105f5400-0126-11eb-935c-ff0a2fcca55c.png)

## Step-3 FLattening
Converting matrix to column for ANN
![image](https://user-images.githubusercontent.com/44740658/94373960-86fc5180-0126-11eb-8929-4a21e933faa7.png)
![image](https://user-images.githubusercontent.com/44740658/94373986-9e3b3f00-0126-11eb-94c5-f2cc526ad90b.png)

## 1-2-3
![image](https://user-images.githubusercontent.com/44740658/94373997-b01ce200-0126-11eb-8037-0fb650e3a098.png)

## Step-4 Full Connection
![image](https://user-images.githubusercontent.com/44740658/94374024-f2deba00-0126-11eb-9005-f4a8cd841378.png)
The output looks out for which neuron to look for..the more the number of time that neuron lights up for it..the more that neuron is significant for that output

## Softmax and cross entropy
Softmax function is used to bring the output values inside of 0-1...so to obtain the probabilites
![image](https://user-images.githubusercontent.com/44740658/94374383-8b763980-0129-11eb-9f1b-6836f88af47b.png)
Cross entropy function(Loss Function(Cost function))
![image](https://user-images.githubusercontent.com/44740658/94374446-f3c51b00-0129-11eb-81bd-1cab9bb9146e.png)
![image](https://user-images.githubusercontent.com/44740658/94374470-18b98e00-012a-11eb-870c-a0a1cd903081.png)
Accurate Error Prediction
Advantages of Cross entropy over mean squared
If the output is very low compared to the actual..mean squared won't show much difference for the improvement
![image](https://user-images.githubusercontent.com/44740658/94374523-806fd900-012a-11eb-959c-d5b052434758.png)








