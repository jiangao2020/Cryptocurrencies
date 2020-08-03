# Cryptocurrencies

# Challenge

# Data Processesing
I first used sklearn.preprocessing to lable the string columns to numeric, but this lead to a smooth elbow curve, K= 8. Then, I used pandas to convert the same column which lead to a much clearer elbow curve K = 4 and K = 5.

# K-Means
From K-Means elbow curve, both K= 4 and K = 5 can be used. I chose K = 4 because its 3D plot shows clusters clearer, it also has classes 0 and 2 split more logically. Also, It is hard to define the three different classes near the origin when K = 5. 

# 3D Plot
![3D Plot] (https://github.com/jiangao2020/Cryptocurrencies/blob/master/Figures/3D%20Plot.jpeg)

# Data Table
![DataTable] (https://github.com/jiangao2020/Cryptocurrencies/blob/master/Figures/DataTable.jpeg)

# Scatter Plot
![Scatter Plot] (https://github.com/jiangao2020/Cryptocurrencies/blob/master/Figures/Scatter.jpeg)
