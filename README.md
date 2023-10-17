##Project: Marketing Campaigns

we have a dataset related to marketing strategies and customer acquisition. The dataset contains information about different variables such as birth-year, education, income, product spending, sales channels, promotions, and more. The objective is to perform exploratory data analysis and hypothesis testing to understand the factors influencing customer acquisition.

Here are the steps involved in performing the analysis:

Import the data: Start by importing the dataset and check if the variables like 'Dt_Customer' and 'Income' are imported correctly.

Missing value imputation: Some customers have missing income values. To address this, assume that customers with similar education and marital status have the same average yearly income. Clean the data and perform the missing value imputation based on these assumptions.

Create additional variables: Generate new variables such as the total number of children, age, and total spending. The total purchases can be derived from the number of purchases made through the different sales channels.

Explore distributions and outliers: Create box plots and histograms to understand the distributions of variables and identify any outliers. Apply outlier treatment methods if necessary.

Encoding categorical variables: Use ordinal encoding and one-hot encoding techniques to handle different types of categorical variables in the dataset.

Correlation analysis: Create a heatmap to visualize the correlation between pairs of variables and understand their relationships.

Hypothesis testing: Test several hypotheses related to customer behavior. For example, examine if older people prefer in-store shopping, if customers with kids prefer online shopping, or if different distribution channels affect sales at the store. Also, analyze if the United States performs significantly better than other countries in terms of total purchases.

Visualization for analysis: Utilize appropriate visualizations to analyze various aspects such as the revenue performance of different products, the relationship between customer age and campaign acceptance rate, the country with the highest number of customers accepting the last campaign, the relationship between the number of children at home and total spending, and the education background of customers who lodged complaints in the last 2 years.

## Check if Income has extreme outliers or not
![image](https://github.com/kero1998a/Marketing_Campaigns/assets/24616273/3fab9aea-5cce-4840-a6ff-83052c42b478)

##Remove outliers 
![image](https://github.com/kero1998a/Marketing_Campaigns/assets/24616273/39e2df00-acd3-4ace-bba6-ad57e62aa845)
![image](https://github.com/kero1998a/Marketing_Campaigns/assets/24616273/6b10067a-ec45-4fb4-b975-9a61fb0a1fd3)
![image](https://github.com/kero1998a/Marketing_Campaigns/assets/24616273/1abf3c1e-c3ee-4900-a646-fd38ca0a9d53)
![image](https://github.com/kero1998a/Marketing_Campaigns/assets/24616273/1eab3b9f-22a1-4f81-8bc4-824e44280b01)

![image](https://github.com/kero1998a/Marketing_Campaigns/assets/24616273/53e1c021-f56e-4072-875a-96d6bc56c61e)
![image](https://github.com/kero1998a/Marketing_Campaigns/assets/24616273/bc7627bd-2597-4c16-92d3-30272353fdd8)
![image](https://github.com/kero1998a/Marketing_Campaigns/assets/24616273/46493e86-076d-414c-b816-99f3c2c3369e)
![image](https://github.com/kero1998a/Marketing_Campaigns/assets/24616273/b00889dc-fbeb-46e7-9415-318645c1d17e)
![image](https://github.com/kero1998a/Marketing_Campaigns/assets/24616273/a10cc803-3c2c-47ad-891b-3ab769bd3724)
![image](https://github.com/kero1998a/Marketing_Campaigns/assets/24616273/6c158801-9a43-4ab9-9e06-7ff905d3a547)








