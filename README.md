Download Link: https://assignmentchef.com/product/solved-cse111-lab3
<br>
<strong>DATABASESYSTEMS</strong>




In this lab session you have to write 15 SQL queries for the TPCH database created and populated in the previous labs. The queries are the following (1 point per query):

<ol>

 <li>What is the address, phone number, and account balance of Customer#000000010?</li>

 <li>What is the smallest account balance of a supplier?</li>

 <li>Find all the line items with the return flag set to R on the receipt date of August 22, 1993. Print l receiptdate, l returnflag, l extendedprice, and l tax for every line item.</li>

 <li>Find the number of line items that have l shipdate smaller than l commitdate.</li>

 <li>What is the minimum, maximum, and total account balance among the customers in every marketsegment?</li>

 <li>What are the nations of customers who made orders between September 10-12, 1996? Print every nation only once and sort them in alphabetical order.</li>

 <li>How many line items with l receiptdate in 1993 did Customer#000000010 order? Print the number of ordered line items corresponding to every month.</li>

 <li>Find the name of the suppliers from AMERICA who have more than $5000 on account balance. Print the supplier name and their account balance.</li>

 <li>Find the maximum account balance of the suppliers from nations with more than 5 suppliers. Printthe nation name, the number of suppliers from that nation, and the maximum account balance.</li>

 <li>Find the total price o totalprice of orders made by customers from AMERICA in 1996.</li>

 <li>Find the number of customers that received a discount of at least 10% for one of the line items on their orders. Count every customer exactly once even if they have multiple discounted line items.</li>

 <li>Find the number of orders having status F. Group these orders based on the region of the customer who posted the order. Print the region name and the number of status F</li>

 <li>Find the total account balance of all the customers from EUROPE in the MACHINERY market segment.</li>

 <li>Find how many 1-URGENT priority orders have been posted by customers from BRAZIL between 1994 and 1997, combined.</li>

 <li>Find the total number of line items on orders with priority 3-MEDIUM supplied by suppliers from CANADA. Groups these line items based on the year of the order from o orderdate. Print the year and the count. Check the substr function in SQLite.</li>

</ol>

In order to complete the lab you have to perform the following tasks:

<ol>

 <li>Write the SQL statement corresponding to every query in the file test/x.sql, where x is the number of the query above. Every query goes into its separate file. These are the only files you have to modify and submit in this assignment.</li>

 <li>You can check the correctness of your queries by executing the command ./test.sh in the terminal. You have to be in the main lab folder. The expected output is available in results/x.res, where x is the number of the query. The output produced by your code is available in output/x.out. They have to match for every query, e.g., res has to match with 1.out.</li>

 <li>In case there are any errors, repeat the process from step 1 for the incorrect queries.</li>

 <li>The submission consists of a compressed zip file that contains the files in the test The name of the file has to be lab-3.zip. When you create the file, include the folder test into the compression, not every file test/x.sql separately.</li>

</ol>

<em>Lab 3                                                                                                                                                                                                   </em>2