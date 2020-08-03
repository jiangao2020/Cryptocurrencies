# Cryptocurrencies

# Challenge

# Data Processesing
I first used sklearn.preprocessing to lable the string columns to numeric, but this lead to a smooth elbow curve, K= 8. Then, I used pandas to convert the same column which lead to a much clearer elbow curve K = 4 and K = 5.

# K-Means
From K-Means elbow curve, both K= 4 and K = 5 can be used. I chose K = 4 because its 3D plot shows clusters clearer, it also has classes 0 and 2 split more logically. Also, It is hard to define the three different classes near the origin when K = 5. 

Scatter Plot, Elbow Curve, 3D Plot, and Data Table can be observed in the Challenge file.
