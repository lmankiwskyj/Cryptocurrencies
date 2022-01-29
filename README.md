# Cryptocurrencies

## Purpose 
Accountability Accounting is interested in offering a new cryptocurrency investment portfolio for its customers. They have requested a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Methods Used 
The data set was processed to fit the machine learning models. 
  - Null data points were removed
  - Only includes cryptocurrencies that are currently being traded and have mined coined 
  
 Unsupervised learning was used since there is no known output.
  - Created variables for the text features with get_dummies()
  - The features were standardized using the StandardScaler fit_transform() function
  - Used the Principal Component Analysis (PCA) algorithm, the dimensions were reduced to three principal components 
 
 Then grouped with a clustering algorithm. 
  - Used the K-means algorithm hvPlot to find the best value for K
![Capture1](https://user-images.githubusercontent.com/90974647/151676247-7dffdb78-9515-44d8-be47-8021e9ba1f90.PNG)
  - Then to predict the K clusters for the cryptocurrencies’ data
![Capture2](https://user-images.githubusercontent.com/90974647/151676260-ab9c3e43-7347-46f0-8615-9da3da4550e1.PNG)

## Outcome
There are 532 tradable cryptocurrencies.
