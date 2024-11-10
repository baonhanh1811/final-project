Linear Regression: 
- Looking at the chart, we can see that the chart provides us with information to predict the value in Amount and some indicators such as Mean Squared Error (MSE), R-squared (R²).

- However, looking at the chart, we can also see that this algorithm does not perform this task well because the Blue points do not follow the red line but are scattered around.

- This is the line representing the points between the predicted value and the actual value that must coincide with each other and if a Linear model is good, these data points need to be distributed around this red line. However, it can be seen in the chart that the data points are quite scattered, some data points are outside the red water area, reaching close to the value of 4000, showing that the prediction model is not accurate.

- For small actual values, specifically below 500, the predictive model is generally more accurate than for large values, above 1000.

- The MSE value is 136195.13, which is the average squared error between the actual value and the predicted value. This value is quite high, indicating that the error between the prediction and the actual is too large, especially at large values. This shows that the predictive model is not good.

- The R² value is 0.454 to measure the proportion of data variation that the model can explain. The value of 0.454 is quite low, indicating that the model only explains 45.4% of the variation in the data. This shows that the model is not strong enough to capture the trend of the data, leading to large deviations.

- Through the chart and the indicators that the chart brings, it can be seen that this model is not good at predicting the actual revenue ratio compared to the predicted ratio. Businesses need to collect more data on important characteristics to be able to create a better chart in predicting. You can refer to collecting more data such as the number of times customers return, revenue compared to cost, total quantity of products, selling price and cost to produce the product, ... to be able to create a better chart in predicting.
![Linear Regression](image/linear1.jpg)

Elbow Graph
- The elbow plot shows the values ​​from 1 to 10. It can be seen that point 3 is the most reasonable and beautiful point to use in data analysis it balances the simplicity of the model and the representation of the data it shows a stable slope from point 1 to point 3 and point 3 to point 10 also shows a more stable decrease than all the other points
![Elbow Graph](image/elbow.jpg)

K Means
+ The Kmeans chart changes the customer segmentation results according to the two values ​​of Amount and Quantity. It can be seen that customers are divided into three different colors: purple, blue and yellow. In addition, the chart also provides some indicators such as: precision, recall, and f1-score.

+ Looking at the chart details, you can see that the purple cluster clusters the first customer segment with a number of about more than 1200 customers. This customer file often buys in quantities from 0 to 9 and in addition, there are some who buy from 10 to 14 but this percentage is very small. This customer file often buys and pays mainly under 1000. It can be seen that this is the average customer segment in society and often buys with a fairly stable frequency and low price.

+ The blue segment shows that the number of customers in this customer file is more than 200 customers, mainly distributed from the purchase quantity of 2 to 9 and also a very small portion of purchases from 10 to 13. This customer file generally seems to have a higher income than the purple customer file because the amount of money they spend to buy products is higher than the purple customer file, from 500 to nearly 2000.

+ Finally, the yellow customer segment accounts for the smallest percentage of all 3 customer files, distributed from the purchase quantity of 3 to 14. However, each quantity is very different and the price segment may be higher than the other two customer files, but it may not bring much profit due to the too scattered distribution in all. It can be seen that they spend a lot of money to buy products, proving that this is a VIP customer file, a high-end customer file, and they are willing to spend money and spend a lot of money to buy the product they want. Although it is not much, it still brings a fair profit to the business, but the profit will not be equal compared to the other two customer files.

+ For the indicators that the score also brings, namely precision, recall, and f1-score, these indicators all reach 1.00, which shows that this chart has completed the task it performs very well. It has segmented customers very well based on the available data, in addition, combining the use of the Elbow chart also helps to determine the index and segment customers well like this.

+ In practice, it can be seen that this chart has helped cluster customers according to the number of products they buy and their spending level. It can be seen that the purple customer file is the average customer. Businesses can create strategies and incentives to encourage these customers to spend more because this is also a fairly stable customer spending group. For the blue customer file, which is the average customer file, their spending level is higher and quite stable, so exclusive incentive programs can be created to retain customers. Finally, for the VIP customer file, products can be promoted more, creating more quality products to attract more VIP customers for the business and sell more products.
![Scatter Plot](image/kmean.jpg)


