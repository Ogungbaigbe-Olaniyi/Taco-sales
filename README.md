# Taco-sales

![Image](https://github.com/user-attachments/assets/bc0427a0-a0e2-4dff-9f2a-3c22285d5ed8)

## Project objective and overview
The objective is to analyze the sales dataset from ten restaurants across 10 cities in the United States which are into the sales of taco with the aim of knowing the total sales orders and revenue generated, understanding order timing and patterns, evaluate the delivery performance of each restaurant, products insights and customers behaviour
## Analysis tools
Excel and Power BI (Visualization)
## Analysis steps
The dataset is in csv format in a zip folder. The dataset was extracted and save in excel in xlsx format. It contains 1000 Taco delivery orders with the following column
| Column                         | Description                                     |
| ------------------------------ | ----------------------------------------------- |
| **Order ID**                   | Unique identifier for each order                |
| **Restaurant Name**            | Name of the taco restaurant                     |
| **Location**                   | City where the order was placed                 |
| **Order Time / Delivery Time** | Timestamp of order and delivery                 |
| **Delivery Duration (min)**    | Time taken for delivery                         |
| **Taco Size**                  | Regular or Large                                |
| **Taco Type**                  | Type of taco (Chicken, Beef, Pork, etc.)        |
| **Toppings Count**             | Number of toppings selected                     |
| **Distance (km)**              | Delivery distance                               |
| **Price (\$)**                 | Cost of the taco                                |
| **Tip (\$)**                   | Tip amount given by customer                    |
| **Weekend Order**              | Whether the order was on a weekend (True/False) |

Having cleaned and evaluate the dataset, the following analysis were done

1. Visualization of the key metrics (descriptive analysis) and business questions answered were done using Power BI by mapping them to the exact type of chart

## Key metrics
The following key metrics were done by looking at the categorical and numerical columns
1. Average delivery duration
2. Average topping count
3. Maximum and minimum price
4. Total order
5. Total revenue
6. Average delivery distance

## Business questions
The business questions were group into categories so that they can be easier to work on.The categories are:
1. Sales order and revenue
2. Delivery performance
3. Customer behaviour and product insights

### Sales and revenue Busness questions
The following are the business questions under the sales and revenue category
1. Which restaurants generate the most orders and highest revenue?
2. What are the top-performing cities by sales volume and revenue?
3. Do Large tacos generate more revenue than Regular tacos?
4. Which taco type brings in the most sales revenue?
5. Are weekends better and busier than weekdays in terms of order count and sales revenue?
#### Key metrics, Sales and revenue Dashboard

<img width="861" height="489" alt="Image" src="https://github.com/user-attachments/assets/f33c00e0-47bb-4c94-86c4-b2030755a3e9" />

<img width="860" height="488" alt="Image" src="https://github.com/user-attachments/assets/f2123f40-321f-4f18-917a-83136f83c962" />

### Delivery performance business questions
The busness questions under the delivery performance category are:
1. Which locations or restaurants have the fastest and slowest delivery times?
2. Are weekend deliveries slower or faster than weekday deliveries?
#### Delivery performance dashboard

<img width="859" height="486" alt="Image" src="https://github.com/user-attachments/assets/3d3064e1-b6d6-4408-be51-29806f9b74fd" />

### Customer behaviour and product insights questions
Customers behaviour and products insights questions are:
1. Do customers tip more for certain taco sizes or types?
2. Do customers in certain cities tip more generously?
3. Which taco type is most popular in each location?
4. Are there cities where Large tacos sell better than Regular ones?
#### Customer behaviour and product insights dashboard

<img width="869" height="489" alt="Image" src="https://github.com/user-attachments/assets/33783c84-854b-49b5-8bd5-06fee41a82d9" /> 

## Key findings and Insights
After analyzing the dataset, the following are the deductions or findings:
1. The top 3 restaurants in terms of sales order generated are Urban tacos, Grande tacos and the taco stand
2. Highest revenue generating restaurant is Urban taco
3. Least revenue generating restaurant is El taco loco
4. Chicken taco is the most popular while beef taco is the least popular as they both generate the highest and least revenue respectively
5. Most order are placed during weekdays compared to weekends for all taco types
6. Restaurants in Chicago generate the most sales order and revenue while Dallas has the least order and revenue
7. in terms of delivery time, La Vida taco has the fastest delivery time overall while taco stand has the slowest . This is also applicable in the state of Dallas
8. overall delivery is faster on weekend than on weekdays however, Casa Del taco deliver faster on weekday compare to Taco stand where delivery is faster on weekend
9. Fish taco and chicken taco rank first and second respectively in termas of order as Fish taco is more popular in 5 states of Dallas, Nwe York, Sandiego, Los Angeles and San jose while chicken taco is popular in 4 states of Chicago, San Antonio, Houston, and Phoenix
10. Restaurants got more customer tips for large taco than the regular taco
11. Customers tend give more tips for chicken taco and pork taco 

