# praticaSQL

>[IMPORTANT]
>INTRO
#### codigo sql

SELECT CustomerName FROM Customers;

>[IMPORTANT]
>Syntax
#### codigo sql

SELECT Condiments FROM Categories

>[IMPORTANT]
>Select
#### codigo sql

SELECT CategoryName,CategoryID FROM Categories;

>[IMPORTANT]
>Select Distinct
#### codigo sql

SELECT DISTINCT CategoryID FROM Categories;

>[IMPORTANT]
>Where
#### codigo sql

SELECT * FROM Products
WHERE ProductName='Chais';

>[IMPORTANT]
>Order By
#### codigo sql

SELECT ProductName FROM Products
ORDER BY Price;

>[IMPORTANT]
>And
#### codigo sql

SELECT * FROM Customers
WHERE Country = 'Mexico' AND CustomerName LIKE 'A%';

>[IMPORTANT]
>Or
#### codigo sql

SELECT CustomerID FROM Customers
WHERE Country = 'Germany' OR Country = 'Spain';

>[IMPORTANT]
>Not
#### codigo sql

SELECT CustomerName FROM Customers
WHERE NOT Country = 'Mexico';

>[IMPORTANT]
>Insert Into
#### codigo sql

INSERT INTO Customers (CustomerName, Country)
VALUES ('Cardinal', 'Brasil');

>[IMPORTANT]
>Null Values
#### codigo sql

SELECT CustomerID
FROM Customers
WHERE CustomerName IS NULL;

>[IMPORTANT]
>Update
#### codigo sql

UPDATE Customers
SET ContactName = 'Pedro', City= 'Cristino Castro'
WHERE CustomerID = 1;

>[IMPORTANT]
>Delete
#### codigo sql

DELETE FROM Customer WHERE CostumerName='Jack';
