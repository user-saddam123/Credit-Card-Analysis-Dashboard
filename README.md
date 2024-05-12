# Credit Card Spending Analysis

### Created and Analyzed by: Saddam Ansari @Aspiring Data Analyst [LinkedIn](https://www.linkedin.com/in/saddam-ansari-dataanalyst/)
### Live Dashboard At Novypro [Link](https://www.novypro.com/create_project/credit-card-spending-analysis-by-saddam-ansari)


✨➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖✨

## Project Objective:

The objective of this Power BI dashboard is to analyze the dataset and generate a comprehensive report aimed at facilitating strategic decision-making for stakeholders. 

By leveraging the insights provided, stakeholders can identify patterns and trends in credit card usage, enabling them to make informed decisions on optimizing features to potentially increase revenue.

## About Datset:

Before Moving Forward I want to share with you about data set,

 * So Basicaly For this project, an American credit card transaction dataset has been utilized, encompassing data from January 2023 to December 2023.

 * The dataset comprises two Excel sheets: "credit_card.xls" and "customers.xls". These sheets contain essential information regarding credit card transactions and customer details.

## Data Description:
### Credit_Card.xls 
Here's a description of the data fields in the provided dataset:

 * Client_Num: Unique identification number assigned to each client/customer.
 * Card_Category: Category of the credit card (e.g., Blue, Gold, Platinum).
 * Annual_Fees: Annual fee associated with the credit card.
 * Activation_30_Days: Indicator (0 or 1) specifying whether the card was activated within 30 days of issuance.
 * Customer_Acq_Cost: Cost incurred in acquiring the customer.
 * Week_Start_Date: Start date of the week to which the data pertains.
 * Week_Num: Week number corresponding to the data entry.
 * Qtr: Quarter of the year (Q1, Q2, Q3, Q4).
 * current_year: Year to which the data belongs.
 * Credit_Limit: Maximum amount that can be charged on the credit card.
 * Total_Revolving_Bal: Total outstanding balance on the credit card.
 * Total_Trans_Amt: Total transaction amount made using the credit card.
 * Total_Trans_Vol: Total transaction volume (number of transactions) made using the credit card.
 * Avg_Utilization_Ratio: Average utilization ratio of the credit card balance to the credit limit.
 * Use Chip: Indicates whether the credit card transaction was done using a chip (Chip) or not (Swipe, Online).
 * Exp Type: Type of expenditure associated with the transaction (e.g., Travel, Entertainment, Bills, Grocery, Fuel).
 * Interest_Earned: Interest earned on the credit balance.
 * Delinquent_Acc: Indicates whether the account is delinquent (1) or not (0).

### Customer.xls
Here's a description of the data fields in the provided customer dataset:

 * Client_Num: Unique identification number assigned to each client/customer.
 * Customer_Age: Age of the customer.
 * Gender: Gender of the customer (M for Male, F for Female).
 * Dependent_Count: Number of dependents the customer has.
 * Education_Level: Educational qualification of the customer.
 * Marital_Status: Marital status of the customer (Single, Married, Divorced, etc.).
 * state_cd: State code indicating the state where the customer resides.
 * Zipcode: Zip code of the customer's location.
 * Car_Owner: Indicates whether the customer owns a car (yes/no).
 * House_Owner: Indicates whether the customer owns a house (yes/no).
 * Personal_loan: Indicates whether the customer has a personal loan (yes/no).
 * contact: Preferred mode of contact with the customer (cellular, telephone, etc.).
 * Customer_Job: Occupation or job role of the customer.
 * Income: Annual income of the customer.
 * Cust_Satisfaction_Score: Customer satisfaction score, possibly based on feedback or surveys.

✨➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖✨

## Dashboard Overview:

The Power BI dashboard comprises two distinct pages, each serving a specific purpose in alignment with the project request:

#### 1.Customers Demographic Page:
This page offers an in-depth portrayal of customers' demographic attributes.

#### 2.Customers Transaction Page:
The second page of the dashboard is dedicated to presenting customer transaction data.

✨➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖✨

## Detailed Explanation:

###Page One: Customer
![Screenshot 2024-05-12 141300](https://github.com/user-saddam123/Credit-Card-Analysis-Dashboard/assets/123800896/316f5335-c722-412a-b77b-fac65d946cc9)



As evident above, Page One focuses on customer-based analysis. However, here's a detailed explanation:


#### Here are the important key performance indicators (KPIs) in detail:
![Screenshot 2024-05-12 162815](https://github.com/user-saddam123/Credit-Card-Analysis-Dashboard/assets/123800896/c3ef8f7a-8b17-44f6-b4a5-f060b42d2a53)

 * Total Customers: The dataset comprises a total of 10,110 customers.
 * Male Customers: There are 4,228 male customers in the dataset.
 * Female Customers: The dataset includes 5,880 female customers.
 * Average Customer Satisfaction Score: The average satisfaction score among customers is 3.19.



### Total Customers by Car Ownership:

Utilizing a bar chart, it's evident that out of the total customers, 6,044 do not own a car, whereas 4,064 customers possess a car.
![Screenshot 2024-05-12 163302](https://github.com/user-saddam123/Credit-Card-Analysis-Dashboard/assets/123800896/0e68d6a7-97df-404e-9636-3157e72d3294)

### Total Customers by Marital Status:
Represented with a donut chart, it's easy to observe that out of the total customer base, 5,128 are married, 4,236 are single, and there are 744 customers with unknown marital status.



### Customers by State Code and Gender:
![Screenshot 2024-05-12 164058](https://github.com/user-saddam123/Credit-Card-Analysis-Dashboard/assets/123800896/c88ebc26-0f19-4e52-94fe-cdbc1f0a1519)

Using a bar chart, the top 5 states by customer count are depicted, along with the distribution based on gender.

 * California (CA): This state has the highest number of customers. Specifically, there are 1,609 female customers and 859 male customers.
 * Texas (TX): Texas holds the third position in customer count. It comprises 1453 female customers and 941 male customers.
 * New York (NY): Following California, New York ranks second in terms of total customers. Here, there are 1,279 female customers and 991 male customers.
 * Florida (FL): Florida is the fourth-ranked state in terms of total customers. It consists of 897 female customers and 814 male customers.
 * New Jersey (NJ): Lastly, New Jersey is among the top 5 states, with 350 female customers and 366 male customers.
By examining this analysis in detail, stakeholders can gain valuable insights into the distribution of customers across different states and genders.



### Customers by Job Type and Gender:
![Screenshot 2024-05-12 170134](https://github.com/user-saddam123/Credit-Card-Analysis-Dashboard/assets/123800896/89b268d4-3b27-43f1-a975-78b1ef69cf4b)

Through this analysis, it can be observed how many customers hold different job types, indicating the nature of their employment or profession.

Examining the data in detail provides clear insights into the distribution of customers based on their job type and gender.





### Total Customers by Age:
![Screenshot 2024-05-12 170352](https://github.com/user-saddam123/Credit-Card-Analysis-Dashboard/assets/123800896/969bed1d-9c8e-4ca4-98d4-e968c2fe98c5)

For the analysis of total customers by age group, a column chart has been employed. 

 * This visualization allows for easy interpretation of the distribution of customers across different age groups. It's evident that the highest number of customers falls within the 40-50 age group, while the lowest number is observed within the 20-30 age group.

### Customers by Income Group:
![Screenshot 2024-05-12 170527](https://github.com/user-saddam123/Credit-Card-Analysis-Dashboard/assets/123800896/8b3ab5fe-881c-48df-8089-6e77fc7e54ec)

For the analysis of total customers by income group, a column chart has been utilized. 

This visualization facilitates easy observation of the distribution of customers across different income brackets. It's apparent that the highest number of customers belongs to the low-income group, whereas the high-income group comprises fewer customers.



### Customers by Education level-
![Screenshot 2024-05-12 170737](https://github.com/user-saddam123/Credit-Card-Analysis-Dashboard/assets/123800896/b769aaf1-d5dc-450c-8b9b-420d4fb0d935)

For the analysis of total customers by education level, a column bar chart has been employed. This visualization allows for easy observation of the distribution of customers across different education levels.

Upon analysis, it is evident that the highest number of customers hold a graduate degree.

✨➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖✨

## Page Two: Transaction 

![Screenshot 2024-05-12 141507](https://github.com/user-saddam123/Credit-Card-Analysis-Dashboard/assets/123800896/933c57b5-83dd-4825-904f-c195f4da524c)


#### Here's a detailed description of the important KPIs on Page Two - Transaction:

 * Total Revenue: The total revenue generated is $55 million.
 * Total Transactions: The total number of transactions is 656,000.
 * Transaction Amount: The total transaction amount is $45 million.
 * Interest Earned: The interest earned is $7.8 million.

### 1.Revenue Trend by Date:
A line chart has been utilized to illustrate the revenue trend over time. It's evident that the highest revenue was generated in July.

### 2.Quarterly Revenue by Transaction Count:
This analysis shows the revenue generated in each quarter alongside the transaction count. It's found that Q3 generated the highest revenue, amounting to $14.2 million, with the highest transaction count of 167,000.

### 3.Revenue by Card Category:
A table has been used to display revenue generated by different card categories, along with transaction count, transaction amount, and interest earned. Analysis reveals that the Blue card category yields the highest revenue, highest transaction amount, highest transaction count, and maximum interest earned.

### 4.Revenue by Use Method:
The analysis indicates that the highest revenue was generated through the swipe use method, totaling $34.9 million, while online transactions contributed the least, amounting to $3.4 million.

### 5.Revenue by Gender:
Using a donut chart, it's observed that revenue from male customers is $30 million, constituting 54% of the total revenue, whereas revenue from female customers amounts to $25 million.

### 6.Revenue by Marital Status:
A donut chart is employed to visualize revenue generated by different marital statuses. It's evident that married customers contributed the highest revenue ($28 million), followed by single customers ($23 million) and unknown marital status ($4 million).

### 7.Revenue by Expenditure Type:
The analysis reveals that bill expenditure generated the highest revenue ($14 million), while travel expenditure contributed the least revenue ($6 million).

### 8.Revenue by Customer Job:
It's observed that revenue generation is highest among business owners, totaling $17 million, followed by white-collar jobholders ($10 million) and self-employed individuals ($8 million).

### 9.Revenue by State Code:
Texas generates the highest revenue, amounting to $12.8 million, followed by New York with $12.7 million.

This detailed analysis provides comprehensive insights into revenue generation trends based on various factors.

✨➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖✨

## Our Target Customers:
Based on the analysis results, our target customers are likely to be:

#### 1.Graduate Degree Holders:
Since the majority of customers hold a graduate degree, targeting this demographic segment can be fruitful.

#### 2.Middle-Aged Individuals (40-50 age group):
With the highest number of customers falling within this age bracket, tailoring marketing strategies and product offerings to meet their needs and preferences can be effective.

#### 3.Low to Middle Income Group: 
As the dataset suggests a larger customer base in the low-income group, focusing on providing affordable and value-added services/products could attract and retain these customers.

#### 4.Blue Card Category Holders: 
Since the Blue card category contributes the most to revenue generation, offering incentives, rewards, or exclusive benefits to this group could further enhance their loyalty and spending.

#### 5.Customers Employed in Business/White-Collar Jobs:
Business ownrs and white-collar jobholders seem to generate the highest revenue. Thus, targeting professionals in these sectors with tailored financial products/services could lead to increased engagement and revenue.

✨➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖✨✨

## Recommendation:

 * Promote Rewards and Benefits: Enhance marketing efforts to highlight the rewards, cashback offers, and exclusive benefits associated with the Blue card category to attract more customers towards it.
 * Targeted Marketing Campaigns: Design targeted marketing campaigns focusing on the preferences and needs of middle-aged individuals, emphasizing convenience, security, and tailored financial solutions.
 * Financial Education and Planning Services: Offer financial education workshops or online resources to help customers in the low-income group manage their finances better and improve their financial well-being.
 * Personalized Offers and Recommendations: Leverage data analytics to provide personalized offers and recommendations based on customers' transaction history, preferences, and life stage to increase engagement and cross-selling opportunities.
 * Customer Retention Strategies: Implement customer retention strategies such as loyalty programs, personalized communications, and proactive customer service to foster long-term relationships and reduce churn.

By targeting these specific customer segments and implementing the recommended strategies, we can aim for sustainable revenue growth and enhanced customer satisfaction in the long run.

✨✨➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖✨✨

**Don't forget to give a start to this project because its motivate me and also please follow me on [Linkeldin](https://www.linkedin.com/in/saddam-ansari-dataanalyst/). and Please consider me for any internship or entry level data analyst role. I need a job or internship even thought its a free or paid. Thanks in Advance.**

#

### How Can You Help Me
 * First and foremost, your appreciation and endorsement of this project mean the world to me. If you have any recommendations or suggestions, please feel free to share them with me. Your input can immensely assist me in refining and improving this project further.

 * Additionally, I have worked on over **40 projects**, which you can explore on my [portfolio at Novypro](https://www.novypro.com/profile_projects/saddamansari). If you believe that my skills align with your requirements, I would be grateful if you could recommend me on [LinkedIn](https://www.linkedin.com/in/saddam-ansari-dataanalyst/).

 * As I am currently seeking internship or entry-level positions, your support and assistance would be invaluable to me. I assure you of my gratitude for any help extended.

I hope you found this project enjoyable and insightful.😊😊

#

Created & Presented by -Saddam Ansari @ Aspiring Data Analyst

Date- 03/01/2024

Place- Bihar, India
