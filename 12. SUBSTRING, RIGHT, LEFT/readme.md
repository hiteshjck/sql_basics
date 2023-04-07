<pre>
<h1>Description</h1>
The SUBSTRING() function extracts some characters from a string.

The RIGHT() function extracts a number of characters from a string (starting from right).

The LEFT() function extracts a number of characters from a string (starting from left).
<h1>Query</h1>
SELECT ContactName, substring(ContactName,2,8) as substr, left(ContactName, 5) as left_str, 
right(ContactName, 5) as right_str from Customers;

Try this command <a href="https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all">here</a>!
</pre>
