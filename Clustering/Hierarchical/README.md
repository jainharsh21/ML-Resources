# Hierarchical Clustering

## What it does
![image](https://user-images.githubusercontent.com/44740658/93881792-ffb17700-fcfc-11ea-8c74-3287270d0998.png)

## Types
1) Bottom - up
2) Top - down
![image](https://user-images.githubusercontent.com/44740658/93881966-2e2f5200-fcfd-11ea-9ce2-04f0126082c9.png)

## Agglomerative 
### Algorithm
![image](https://user-images.githubusercontent.com/44740658/93882404-d1806700-fcfd-11ea-8c08-d74c04b83645.png)
Distance betweem two clusters
![image](https://user-images.githubusercontent.com/44740658/93883243-ef9a9700-fcfe-11ea-9036-6ef321b0b347.png)

Distance between two points is basically the disimillarity between them.

### Dendogram
![image](https://user-images.githubusercontent.com/44740658/93884125-202f0080-fd00-11ea-8b74-404b8cb50139.png)

In dendograms we set thresholds which helps us to determine the number of clusters in our model.
The number of clusters is equal to the number of verticle lines our threshold horizontal line custs.
![image](https://user-images.githubusercontent.com/44740658/93884570-b2cf9f80-fd00-11ea-92e7-0ee460d26365.png)

To find the optimal number of clusters we need to find the longest vertical line that doesn't cut any of the horizontal lines and pass our threshold through that.
![image](https://user-images.githubusercontent.com/44740658/93885315-a26bf480-fd01-11ea-87b6-5ab97e0f2027.png)
