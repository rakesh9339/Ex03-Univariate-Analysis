# Ex03-Univariate-Analysis
# Aim:
To read the given data and perform the univariate analysis with different types of plots.

# Theory:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

# Algorithm:
# Step 1:
Read the given data.

# Step 2:
Get the information about the data.

# Step 3:
Remove the null values from the data.

# Step 4:
Mention the datatypes from the data.

# Step 5:
Count the values from the data.

# Step 6:
Do plots like boxplots,countplot,distribution plot,histogram plot.

# Program:
```
# Devoloped by :Rakesh J.S
# Register no:212222230115
import pandas as pd
import numpy as np
import seaborn as sns

data=pd.read_csv('SuperStore.csv')
data

data.head()

data.info()

data.describe()

data.isnull().sum()

data.dtypes

data['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=data)

sns.countplot(x='Postal Code',data=data)

sns.distplot(data["Postal Code"])

sns.histplot(x='Postal Code',data=data)
```
# Output:
# Dataset:
![out1 png](https://user-images.githubusercontent.com/121115650/230705410-3b1c53a9-5e3f-4a29-b13a-d613642ed534.png)
# Data Head:
![out2 png](https://user-images.githubusercontent.com/121115650/230705480-8b36002a-7e7c-4781-94af-4ae41b9c95a8.png)
# Data Information:
![out3 png](https://user-images.githubusercontent.com/121115650/230705485-00734137-2792-4fbb-a827-c202e66d3c36.png)
# Data Describition: 
![out4 png](https://user-images.githubusercontent.com/121115650/230705496-e814df36-1059-4385-890a-f2082e76b9a1.png)
# Null Data:
![out5 png](https://user-images.githubusercontent.com/121115650/230705501-876238d8-6aca-4ce4-834a-d6f63c910674.png)
# Data Type:
![out6 png](https://user-images.githubusercontent.com/121115650/230705506-702997df-bdea-4704-a5d2-fc4d0c248b27.png)
# Value Counts:
![out7,png](https://user-images.githubusercontent.com/121115650/230705510-c60fc4ee-b121-42c9-8e2a-b0772095fcae.png)
# Box Plot:
![out8 png](https://user-images.githubusercontent.com/121115650/230705519-5a049069-3579-4195-a541-7d8cf692cdf6.png)
# Count Plot:
![out9 png](https://user-images.githubusercontent.com/121115650/230705528-a1819eec-49d1-41b8-9d03-bd5ff15d38ac.png)
# Distribution Plot:
![out10 png](https://user-images.githubusercontent.com/121115650/230705534-6745e8a6-cac9-4bfc-8d1a-fc454fa6d324.png)
# Histogram Plot:
![out11 png](https://user-images.githubusercontent.com/121115650/230705540-3105880f-1c48-49b5-b09f-b0be08607e34.png)

# Result:
Thus, we have read the given data and performed the univariate analysis with different types of plots.


