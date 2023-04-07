<pre>
<h1>Description</h1>
The COUNT() function returns the number of records returned by a select query.
NULL values are not counted.

The MIN() function returns the smallest value of the selected column.

The MAX() function returns the largest value of the selected column.

The AVG() function returns the average value of an expression.
NULL values are ignored. 
<h1>Query</h1>
SELECT COUNT(ProductID) AS NumberOfProducts FROM Products;
SELECT MIN(Price) AS SmallestPrice FROM Products;
SELECT MAX(Price) AS LargestPrice FROM Products;
SELECT AVG(Price) AS AveragePrice FROM Products;

Try this command <a href="https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all">here</a>!
</pre>
