# praticaSQL

>[IMPORTANT]
>INTRO
#### INTRO

SELECT CustomerName FROM Customers;

>[IMPORTANT]
>Syntax
#### Syntax

SELECT Condiments FROM Categories

>[IMPORTANT]
>Select
#### Select

SELECT CategoryName,CategoryID FROM Categories;

>[IMPORTANT]
>Select Distinct
#### Select Distinct

SELECT DISTINCT CategoryID FROM Categories;

>[IMPORTANT]
>Where
#### Where

SELECT * FROM Products
WHERE ProductName='Chais';

>[IMPORTANT]
>Order By
#### Order By

SELECT ProductName FROM Products
ORDER BY Price;

>[IMPORTANT]
>And
#### And
SELECT * FROM Customers
WHERE Country = 'Mexico' AND CustomerName LIKE 'A%';

>[IMPORTANT]
>Or
#### Or
SELECT CustomerID FROM Customers
WHERE Country = 'Germany' OR Country = 'Spain';

>[IMPORTANT]
>Not
#### Not

SELECT CustomerName FROM Customers
WHERE NOT Country = 'Mexico';

>[IMPORTANT]
>Insert Into
#### Insert Into

INSERT INTO Customers (CustomerName, Country)
VALUES ('Cardinal', 'Brasil');

>[IMPORTANT]
>Null Values
#### Null Values

SELECT CustomerID
FROM Customers
WHERE CustomerName IS NULL;

>[IMPORTANT]
>Update
#### Update
UPDATE Customers
SET ContactName = 'Pedro', City= 'Cristino Castro'
WHERE CustomerID = 1;

>[IMPORTANT]
>Delete
#### Delete

DELETE FROM Customer WHERE CostumerName='Jack';
