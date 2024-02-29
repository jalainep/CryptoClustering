# CryptoClustering

Use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.




![image](https://github.com/jalainep/CryptoClustering/assets/143963189/ca8116a8-1c31-4aed-ac69-a4ae3e44f6c7)













# Prepare the Data
-Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.

-Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.


![image](https://github.com/jalainep/CryptoClustering/assets/143963189/9751bd10-2177-4e16-b641-a1a3d8208dad)











# Process

Find the Best Value for k Using the Original Scaled DataFrame

Cluster Cryptocurrencies with K-means Using the Original Scaled Data

Optimize Clusters with Principal Component Analysis

Find the Best Value for k Using the PCA Data

Cluster Cryptocurrencies with K-means Using the PCA Data






# Results




Elbow Curve

![bokeh_plot (1)](https://github.com/jalainep/CryptoClustering/assets/143963189/09465006-5410-40b9-bfb0-8e52627d79b3)





















Elbow Curve with PCA Data

![bokeh_plot](https://github.com/jalainep/CryptoClustering/assets/143963189/874d2393-dfee-440d-8b8f-caa2de30c05c)
































Cluster With Original Data
![bokeh_plot (2)](https://github.com/jalainep/CryptoClustering/assets/143963189/57e2ba65-275f-4ee6-83fa-8685ba8caa83)

































Cluster With PCA Data

![scatter](https://github.com/jalainep/CryptoClustering/assets/143963189/ab548774-7968-45dc-8450-28104a5df24a)






