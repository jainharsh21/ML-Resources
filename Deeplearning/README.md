# Deep Learning

Deep Learning is the most exciting and powerful branch of Machine Learning. Deep Learning models can be used for a variety of complex tasks:

Artificial Neural Networks for Regression and Classification
Convolutional Neural Networks for Computer Vision
Recurrent Neural Networks for Time Series Analysis
Self Organizing Maps for Feature Extraction
Deep Boltzmann Machines for Recommendation Systems
Auto Encoders for Recommendation Systems
In this part, you will understand and learn how to implement the following Deep Learning models:

Artificial Neural Networks for a Business Problem
Convolutional Neural Networks for a Computer Vision task

![image](https://user-images.githubusercontent.com/44740658/94340166-35b46b00-001d-11eb-840a-a8a705c621a9.png)

## Neuron

### Basic Structure
![image](https://user-images.githubusercontent.com/44740658/94340821-44515100-0022-11eb-93c0-5adf26b09914.png)

## Activation Function

### Threshold Function
![image](https://user-images.githubusercontent.com/44740658/94340975-8f1f9880-0023-11eb-8127-27e81069f6eb.png)

### Sigmoid Function
![image](https://user-images.githubusercontent.com/44740658/94341027-d27a0700-0023-11eb-91b6-9336c3a7f6b4.png)

### Rectifier
![image](https://user-images.githubusercontent.com/44740658/94341103-7bc0fd00-0024-11eb-981a-233d2ed70405.png)

### Hyperbolic Tangent(tanh)
![image](https://user-images.githubusercontent.com/44740658/94341114-95fadb00-0024-11eb-8517-0d03363ffa94.png)

## How Neural Networks Work?
Input layer => Hidden layer => Output Layer => Output
Input layer provides independent variables(attributes)..hidden layer combines those attributes in an unique way which would yield unexpected results...hidden layer combines to give results to output layer and finally we get the result as the final output.
![image](https://user-images.githubusercontent.com/44740658/94344474-4a086000-003d-11eb-9147-bb381de4909b.png)

Perception is a neural network with single hidden layer
![image](https://user-images.githubusercontent.com/44740658/94344571-f77b7380-003d-11eb-9477-c37b581da5df.png)
Model predicts value...compare with actual value...calculate cost..return the cost to model...update weights and keep repeating until both values match(cost value is minimum)
![image](https://user-images.githubusercontent.com/44740658/94344632-4b865800-003e-11eb-9bdc-a1c4e2580e00.png)
Multiple Rows
![image](https://user-images.githubusercontent.com/44740658/94344735-f3038a80-003e-11eb-9d88-1cf3fff91496.png)

## Gradient Descent
Used for back propogation(cost function)
For normal gradient descent the cost function should be convex.
![image](https://user-images.githubusercontent.com/44740658/94344996-aa4cd100-0040-11eb-8e81-95701712b7c1.png)

### Stochastic Gradient Descent 
We don't need the cost function to be convex.
Instead of batch calculation..we calculate row by row and then adjust the weight after each row
That doesn't mean it is slow...because it doesn't have to load the data each time from the memory.
It will find the global minimum instead of the local minimum.
Stochastic basically means random.
![image](https://user-images.githubusercontent.com/44740658/94345256-41feef00-0042-11eb-9ef7-20327e038ff1.png)


