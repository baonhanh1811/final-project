# Final project 
# Group 1 
# Online Sales
Subject: Introduction to Data Science

Class: MAS02

Lecturer: Dr. Emmanuel Lance Christopher VI M. Plan

| Student ID | Name               | Task Done                                               | Remark by Leader                    | Student Evaluation |
|------------|--------------------|---------------------------------------------------------|-------------------------------------|--------------------|
| 22080297   | Phạm Tô Bảo Anh   | Conclusion, Machine Learning, Comprehensive study of all content | Complete well, responsible, on time | 100%               |
| 22080322   | Lương Khánh Linh  | Data research, 1 bar chart, 1 scatter plot              | Complete well, responsible, on time | 100%               |
| 22080325   | Bùi Ánh Mai      | Data research, boxplot, interesting findings            | Complete well, responsible, on time | 100%               |
| 22080338   | Nguyễn Thu Phương | Data research, line chart, pie chart                    | Complete well, responsible, on time | 100%               |
| 22080339   | Tạ Thu Phương     | Data research, introduction, 1 bar chart, 1 scatter plot | Complete well, responsible, on time | 100%               |

1. Introduction
This data includes two CSV files: Order.csv and Details.csv
- Order.csv: This data file provides basic customer information including five columns of information respectively as follows: Order ID, Order Date, Customer Name, State and City
- Details.csv: This data set provides more detailed information because it includes seven Cute data respectively as follows: Order ID, Amount, Profit, Quantity, Category, Sub-Category and Payment Mode
- These two data files collect information of Indian people which can be from retail platforms or e-commerce platforms. The information shows data about sales or orders or tracking the profits of the business
2. Detailed Information
   
- Orders.csv:
+ Order ID: Identifier for each order
+ Order Date: Specific order date
+ Customer Name: Full name of customers who placed the order
+ State: State where the customer resides
+ City: City where the customer resides
  
- Details.csv:
+ Order ID: Code associated with Order csv file
+ Amount: Total order value
+ Profit: Profit earned from the order
+ Quantity: Quantity of items in the order
+ Category: Category of products
+ Sub-Category: More detailed description from the product category
+ PaymentMode: Payment methods used by customers for the transaction

3. Data Types:
- In Orders.csv, the "Order Date" column is currently in object (string) format and should be converted 
to a proper date format for any time-based analysis.

- Outliers in Numeric Data (from Details.csv): Amount: The minimum value of 4 and maximum value of 5729 appear normal, though there is a wide range.

- Profit: There are negative values in the "Profit" column, which may indicate losses. However, some values seem extreme (e.g., -1981), so these should be checked to determine if they are valid or errors.

4. Interesting findings
1. Geographical location
- There are many orders from far away places like Nagaland (Kohima), Jammu and Kashmir, Kerala (Thiruvananthapuram). Showing the wide distribution capacity of the business
- Chandigarh appears in both Punjab and Haryana (being the common administrative center of the two states)
- Some big cities like Bangalore, Chennai have few orders.
- Hyderabad appears as a city of Andhra Pradesh
=> Wide geographical distribution, orders come from different states in India, from Gujarat in the west to Nagaland in the northeast, and from Jammu and Kashmir in the north to Kerala in the south. This shows that the company has a wide range of operations.
- Diversity of cities: Orders come not only from big cities like Mumbai, Delhi, Bangalore which are the main sources of revenue for the company but also from smaller cities like Mathura, Prayagraj, Kohima. This shows that the company has the ability to serve both urban and rural areas.
- Customer name diversity: The customer list includes a variety of names, reflecting the cultural and linguistic diversity of India.
- Repeat orders: There are some customer names that appear multiple times (e.g. Madhav, Shrichand), indicating that there are regular customers or possibly dealers.
- Customer names reflect the cultural and religious diversity of India (e.g. Hindu, Muslim, Sikh). There are both traditional and modern names, indicating a diverse customer base in terms of age and culture.

2. Profit
- Electronics has the highest profit margin of all categories, reflecting its dominance in society and high demand. There is a huge gap from high losses (-916) to high profits (1864), which can happen due to excessive discounting, or during periods of high demand, production costs are higher than revenue.
- Many products in the Clothing category have negative profit margins, especially low-value items such as Handkerchiefs

5. Charts

Bar chart - Sub-category by Amount:
+ Description: Shows the total sales volume by sub-category, including 17 sub-categories with the highest volume level of 60,000.
+ Reviews: The sub-category with the highest sales is "Printers" with a quantity of about 60,000 while the sub-category with the lowest is "Skirt" with a quantity of only about 2,000.
+ Purpose: Compare and analyze the effectiveness and sales performance between product sub-categories.
+ Lesson: Focus on key products, change weak products, diversify products, create differences.
![Bar Chart](image/bar1.jpg)

Pie Chart - Payment mode:
+ Description: Provides an overview of the sales structure according to different payment methods, helping businesses make strategic decisions.
+ Reviews: Cash on delivery (COD) accounts for the highest percentage, debit cards account for the lowest percentage of all payment methods.
+ Purpose: Visualize the percentage of each different payment method chosen by customers when making a purchase.
+ Lesson: Understand customer behavior, diversify payment methods and focus on key methods.
![Pie Chart](image/pie.jpg)

Line Chart - Monthly Profit Trend:
+ Description: Provides an overview of the monthly profit development of the enterprise.
+ Reviews: Profits reached the highest point around November 2018, and dropped to the lowest level around May 2018.
+ Purpose: Illustrate the fluctuations in profits over time, support analysis and decision making.
+ Lesson: Understand profit fluctuations, recognize risks plan and forecast.
![Line Chart](image/line.jpg)

Bar chart - Total Sales by State:
+ Description: Evaluate business performance and make strategic decisions.
+ Reviews: The state of "Maharashtra" has the highest revenue, incontrast "Mizoram" has the lowest revenue, shows a large difference in revenue between states.
+ Purpose: Compare revenue, evaluate and develop business performance.
+ Lesson: Focus and expand key markets, improve business strategy.
![Bar Chart](image/bar2.jpg)

Scatter Plot - Quantity of products sold and Profit:
+ Description: Shows the relationship between the number of products sold and the profit of each product.
+ Reviews: Very high profits but have some negative profits, large quantity but not the only deciding factor.
+ Purpose: Identify key and weak products, evaluate the effectiveness of marketing campaigns.
+ Lesson: Quantity does not determine profits, develop an sensible pricing strategy.
![Scatter Plot Chart](image/scatterplot.jpg)

Boxplot - Profit distribution by category:
+ Description: Shows the distribution of profits across three product categories: Furniture, Electronics, and Clothing.
+ Reviews: The median profit of electronics is the highest point, this number in funiture is higher than zero, in clothing is nearly zero.
+ Purpose: Reduce large losses and optimize profit, cost control, finding a new marketing strategy, discontinuing low-performing products.
+ Lesson: Focus resources on electronics, cost and marketing optimization.
![Boxplot Chart](image/boxplot.jpg)

6. Machine Learning

Elbow Graph
+ The Elbow graph illustrates value ranging from 1 to 10, with the best value is 3, because it shows the most variation at both ends.
=> Using point 3 is the best way to analyze data in all points.
![Elbow Graph](image/elbow.jpg)
+ K Means


Linear Regression
+ Linear regression algorithm outputs a model to predict the relationship between two values ​​Amount and Profit. This graph helps predict trends from real wine including two parts: tourist spots and linear regression line.
![Linear Regression](image/linear.jpg)


