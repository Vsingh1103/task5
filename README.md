# task5
**In this repo we are working on all sql joins with example** 
-In first step, we worked on INNER JOIN
SELECT o.OrderID, c.Name, o.OrderDate
FROM Orders o
INNER JOIN Customer c ON o.CustomerID = c.CustomerID;

-In 2nd step, we worked on LEFT JOIN
SELECT c.CustomerID, c.Name, o.OrderID, o.OrderDate
FROM Customer c
LEFT JOIN Orders o ON c.CustomerID = o.CustomerID;

-In 3rd step, we worked on RIGHT JOIN
SELECT c.CustomerID, c.Name, o.OrderID, o.OrderDate
FROM Customer c
RIGHT JOIN Orders o ON c.CustomerID = o.CustomerID;

-In 4th step, we worked on FULL OUTER JOIN
SELECT c.CustomerID, c.Name, o.OrderID, o.OrderDate
FROM Customer c
FULL OUTER JOIN Orders o ON c.CustomerID = o.CustomerID;

-In the last step, we worked on CROSS JOIN
SELECT c.Name AS CustomerName, p.Name AS ProductName
FROM Customer c
CROSS JOIN Product p;
