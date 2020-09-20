# Kernel SVM

## Intuition

To seperate a linearly inseperable data..we add a dimension to it and split it

### Example of splitting 1D linearlly inseperable data
Pick a point and subtract that from the whole data set.
Square the subtract result and you'll get a curve and project the 1D points onto the curve
![image](https://user-images.githubusercontent.com/44740658/93713248-2eeaab80-fb78-11ea-8f78-e38f40cfc62d.png)

### Similary for 2D if the data is inseperable we'll using a mapping function to add a dimension...split using hyperplane
![image](https://user-images.githubusercontent.com/44740658/93713372-04e5b900-fb79-11ea-9130-f0d2d71ae9d1.png)

### And after splitting we'll project them back to the 2D plane and get a non-linear seperator.
![image](https://user-images.githubusercontent.com/44740658/93713424-673eb980-fb79-11ea-989c-c2c8374ba514.png)

### Problem with this approach
Problem with this approach is mapping to a higher dimension can be highly compute-intensive.

### Kernel trick
A landmark is chosen at the center..the more the close point is to the landmark...it would come into the cirle and all the points within the circumference of that circle will get value 1 and those outside it will get value 0. In this way our model would be split.
Increasing the value of sigma will increase the circumference of that circle.
![image](https://user-images.githubusercontent.com/44740658/93713675-fc8e7d80-fb7a-11ea-95b2-165e6bfb1b0b.png)

### Multiple landmarks
In case of more complex model we can make use of multiple landmarks which won't interfere with each other.
![image](https://user-images.githubusercontent.com/44740658/93713773-c1d91500-fb7b-11ea-9a75-acb8c9b34ef4.png)

### Kernel Functions
![image](https://user-images.githubusercontent.com/44740658/93713861-504d9680-fb7c-11ea-98dd-26dcc5ab634d.png)a
