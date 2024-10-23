# group4project1
# Pizza Shop Orders Database

Our task was to build a Relational Database focused on the day to day operations surrounding a Pizza Shop. Managing a pizza shop requires keeping track of orders in a way that helps the business run smoothly. Knowing which pizzas are most popular and having accurate data is essential. If managers don't track orders effectively, they could run into problems like wasting food, being understaffed during busy times, or delivering orders late. By using an efficient SQL system, managers can stay on top of trends, optimize staffing, and improve customer satisfaction, all of which are key to the shop's success.



## Acknowledgements

 - [Forward_engineer](https://github.com/Malik01010/Group4_project1/blob/0e7880c9f5623f5623c74e6ada0f8ec5a4cde79a/Forward_engineer)
 - [Queries](https://github.com/Malik01010/Group4_project1/blob/0e7880c9f5623f5623c74e6ada0f8ec5a4cde79a/Queries)
 - [Data](https://github.com/Malik01010/Group4_project1/blob/0e7880c9f5623f5623c74e6ada0f8ec5a4cde79a/data)
 


## Team

- Abhi Malik [@Malik01010](https://github.com/Malik01010)
- Eric Kho [@ek29262](https://github.com/ek29262)
- Arish Petani [@Arishpetani](https://github.com/Arishpetani)
- Samuel Suen [@samsuen999](https://github.com/samsuen999)
- Dan https://github.com/danmmosu



## Data Model

<img width="612" alt="Screenshot 2024-10-16 at 3 07 15 PM" src="https://github.com/user-attachments/assets/580939f8-7f63-48a0-9bc5-936ced5c74d2">


## Data Dictionary
<img width="838" alt="Screenshot 2024-10-16 at 3 08 01 PM" src="https://github.com/user-attachments/assets/796439b2-cb38-4e17-9eba-9e3fe01a6f2d">

<img width="915" alt="Screenshot 2024-10-23 at 2 40 08 PM" src="https://github.com/user-attachments/assets/67c84669-4c4b-4af5-94b1-91870faee63b">


## Queries 

| Features | Query 1    | Query 2   | Query 3 | Query 4 | Query 5 | Query 6 | Query 7 | Query 8 | Query 9 | Query 10 |
| :-------- | :------- | :---------- | --- | ---        | ---     | ---     | ---     | ----    | -----   | -----     |
| Multi Table Join |  |  |  |  | x | x | x | x | x | x |
| Group By |  | x | x | x | x | x | x | x | x | x |
| Built in Functions | | x | x | x | x | x | x | x |  | x |
| Group By with Having |  |  |  |  | x |  | x |  |  |  |
| Subquery|  |  |  |  |  |  |  |  |x  | x |



## Query 1
This query returns which products were ordered the most. This can help with pricing items, advertising items, and with inventory.

![image](https://github.com/user-attachments/assets/a7d9a054-6f25-4541-9d5b-a81c00d9bdf8)

## Query 2
This query shows how many products are ordered on certain dates. This is good for analyzing important dates such as weekends and holidays to analyze which days get more orders.

![image](https://github.com/user-attachments/assets/ab81bc6e-c144-43df-8334-2236d257f2f3)

## Query 3
This query shows the revenue from each day. This can also be used for analyzing important dates, and which days are seeing the more orders or more expensive items being ordered.

![image](https://github.com/user-attachments/assets/d0c2efda-345f-4c1b-a3fb-56d8595515f1)

## Query 4
This query returns the total revenue from each payment method. This is good for determing how much cash should be kept in the cash register, and if we should invest in more card readers.

![image](https://github.com/user-attachments/assets/368dc9ef-d888-4eb8-86fa-e163550ab994)

## Query 5
This query returns the average transaction value from each payment method where customers paid over $20. This helps pinpoint what method customers are using in our highest value transactions.

![image](https://github.com/user-attachments/assets/68a3f381-89a9-4c00-93be-213436278869)

## Query 6
This shows the average transaction value of transactions by employees. This shows high performance employees. We can use this information to promote employees, or see what strategies high performance employees are using and use the strategy with our other employees.
![image](https://github.com/user-attachments/assets/f5a7bf17-25bf-464e-b64d-efa036401f3b)

## Query 7
This query shows the customers who ordered more than 1 distinct product and the total amount they spent. This is good for seeing which products are ordered together. We can run promotional deals based of these combinations.
![image](https://github.com/user-attachments/assets/459b4266-00a1-4050-8e3d-43469914cae1)

## Query 8
This query shows which products are being sold by each employee. This shows which products each employee is more inclined to promote. This can help determine which products are selling more effectively.
![image](https://github.com/user-attachments/assets/9d0021df-31de-44a5-8ba4-625e49717b80)

## Query 9
This shows the highest spending 3 customers and the employees who managed them. With this we can determine our highest spending and most loyal customers. We can also see which employees are good at getting customers to spend more.
![image](https://github.com/user-attachments/assets/176d9e43-12ac-42e4-8001-28f0967142f9)


## Query 10
This query shows what percent of products sold were the most popular product. This determines how much of sales the most popular product truly takes up. This can help with what products we should market or change.
![image](https://github.com/user-attachments/assets/ee04bafc-4508-49fc-aa3c-d85660b92f28)


## Database Information
Database name: ha_ek29262 
All queries can be called using stored procedures using this format: CALL TP_Q1();
