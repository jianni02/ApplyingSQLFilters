<h1>Applying SQL Filters Project</h1>


<h2>Description</h2>
The project involves investigating potential security issues related to login attempts and employee machines by applying SQL filters to retrieve records from various databases. The SQL filters utilized to filter and obtain necessary information included AND, OR, NOT, and LIKE.



<brf />



<h2>Walk-through:</h2>

<p align="center">
<h3>Retrieve after hours failed Login Attempts</h3>
<p style="font-weight:normal"> I used the AND operator, which specifies that both conditions must be met simultaneously: login attempts made after hours (18:00:00) and unsuccessful login attempts.
</p>

<<img src= https://imgur.com/VRmz6Ku.png height="80%" width="80%" alt="After Hours"/>
<br />
<h3>Retrieve Login Attempts on Specific Dates:</h3>
<p>I used the OR operator to retrieve all login attempts from two specific dates: 2022-05-09 and 2022-05-08.
</p>
<img src=https://imgur.com/Zqahadw.png height="80%" width="80%" alt="Specific Dates"/>

<h3>Retrieve Login Attempts Outside of Mexico:</h3>
<p>I used NOT to negate the condition of login attempts from Mexico and utilized LIKE to search for a pattern within the column, which includes potential variants of Mexico listed in logs (e.g., Mex).
</p>
<img src=https://imgur.com/tzIAU3h.png height="80%" width="80%" alt="Outside Mexico"/>

<h3>Retrieve Employees in Marketing:</h3>
<p>By using the = operator, I could specify that I wanted to filter information about employees only from the Marketing department. Additionally, using the LIKE operator allowed me to find patterns that filtered for all East offices.
</p>
<img src=https://imgur.com/UhRUWBI.png height="80%" width="80%" alt="Marketing"/>

<h3>Retrieve Employees in Finance or Sales:</h3>
<p>Using the OR operator specifies that either condition can be met, such as receiving employee information from either the finance or sales departments.</p>
<img src=https://imgur.com/Lqz8GAB.png height="80%" width="80%" alt="Finance or Sales"/>
<h3>Retrieve All Employees not in IT:</h3>
<p>Using the NOT operator negates the condition of receiving employees who work in the IT department, resulting in retrieving information about other departments instead.
</p>
<img src=https://imgur.com/zVlJ1DT.png height="80%" width="80%" alt="Not IT"/>

<h3>Summary</h3>
<p>In this project, I utilized AND, OR, and NOT logical operators within real-world examples of SQL queries. Tasks included investigating login attempts from a specified date to retrieving department-specific employee information. This enabled me to gain practical experience in generating SQL strings and using operators to filter out necessary information based on the context.
</p>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
