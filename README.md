# Lab-4

– Identify data quality issues
 
First, I checked the dataset to see if there were any data quality problems such as missing values or incorrect data types. After checking the dataset, I found that there were no missing values in the original data.

– Apply missing value strategies

Even though the dataset did not contain missing values, I created some missing values to demonstrate how to handle them. Then I tried different strategies such as removing rows with missing values and filling the missing values using the mean and median of the column.

– Detect and handle outliers using IQR

I used the IQR method to check if there were any outliers in the dataset by calculating the lower and upper bounds. After checking the values, I found that there were no significant outliers.

– Normalize numerical features

I normalized the numerical features using two methods: Min-Max scaling and Z-score standardization. This helps put the features on a similar scale

– Apply PCA

Finally, I checked the correlation between the features using a heatmap. Since there was some relationship between them, I applied PCA on hours_studied and exam_score. The results show that the first component explains about 60% of the variance and the second about 40%.
