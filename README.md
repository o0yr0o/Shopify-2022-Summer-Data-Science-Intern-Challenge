# Shopify - 2022 Summer Data Science Intern Challenge

## Question 1
Given some sample data, write a program to answer the following: click here to access the required data set On Shopify, we have exactly 100 sneaker shops, and each of these shops sells only one model of shoe. We want to do some analysis of the average order value (AOV). When we look at orders data over a 30 day window, we naively calculate an AOV of $3145.13. Given that we know these shops are selling sneakers, a relatively affordable item, something seems wrong with our analysis.
1. Think about what could be going wrong with our calculation. Think about a better way to evaluate this data.
    - The reason why the AOV is so large is that some orders purchased a large number of sneakers per order which would increase the value per order, these extreme values could affect AOV.
    - We can define the value of sneakers instead of order value to check if the value of the sneakers is reasonable, then calculate the average sneakers value.
2. What metric would you report for this dataset?
    - I would calculate the value of each pair of sneakers. After I calculated the value of the sneakers, I found some orders have unreasonable high values of sneakers, so I deleted these outliers to help us to indicate average sneakers value more correctly.
3. What is its value?
    - The average sneakers value is $152.48, which is more reasonable than the AOV.

## Question 2
For this question you’ll need to use SQL. Follow this link to access the data set required for the challenge. Please use queries to answer the following questions. Paste your
queries along with your final numerical answers below.
1. How many orders were shipped by Speedy Express in total?
    - 54 orders were shipped by Speedy Express.
    - ![image](https://user-images.githubusercontent.com/82549782/150240156-beba64af-9163-4d58-a6f8-6406107331ff.png)
2. What is the last name of the employee with the most orders?
    - The last name of the employee with the most orders is Peacock.
    - ![image](https://user-images.githubusercontent.com/82549782/150249597-21349841-90d3-4fe1-921e-8721572f97cd.png)
3. What product was ordered the most by customers in Germany?
    - Gorgonzola Telino was ordered the most by customers in Germany.
    - ![image](https://user-images.githubusercontent.com/82549782/150244173-844fabd0-3467-475f-8316-c8faa2e3a4c8.png)
