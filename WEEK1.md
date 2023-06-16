Code Talks MySql Week 1

EX Question: Write a query that shows the name of the products that have an inventory of over 30. 

SELECT product_name FROM Products WHERE current_inventory > 30

Explanation: We are setting this query to slect from the specific column that has our product name. We then next add what table we'll be selecting that column from. To top it off, we'll be grabbing the information on the invetory that's more than 30 from the current_inventory column from.

QUESTION: Select all the product ID's from the CodeTalks table:
SELECT product_id FROM CodeTalks

QUESTION: Select all transactions with an ID of 11:
SELECT * FROM Code_Talks WHERE transaction_id = 11

QUESTION: Have the transaction ID's go in descending order:
SELECT * FROM Transactions ORDER BY transaction_id DESC

QUESTION: Select all the proucts that are produce that only weigh in ounces:
SELECT * FROM Products WHERE  product_type ="produce" AND unit = "oz"