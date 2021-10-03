<hr>
**| [Home](https://rgwebster3.github.io/index.html) | [Code review](https://rgwebster3.github.io/code_review.html) | [Enhancement One](https://rgwebster3.github.io/enhancement_one.html) | [Enhancement Two](https://rgwebster3.github.io/enhancement_two.html) | [Enhancement Three](https://rgwebster3.github.io/enhancement_three.html) |**
<hr>

### Enhancement Three
<br>

The artifact I chose for my Computer Science Capstone is a program that I developed in my CS-410 Software Reverse Engineering course during the 24EW5 term. It is a rudimentary client management application that displays a client and choice of selected service. It also allows the user to change the client’s selected service between brokerage or retirement. I selected this item as my artifact mainly because I found considerable satisfaction in developing a functional program that shared some commonalities with my current career. The planned enhancement to this program will demonstrate my proficiency with databases.

The objective I had for enhancement three was to create a connection to a SQLITE3 database and pass data to the pandas dataframes I created in milestone two. I also wanted to showcase my skills by creating a connection to a SQL Server database I created in my home lab. I created two distinct classes for my etl transactions. Each will use the appropriate syntax for performing CRUD operations in either the SQLITE3 or SQL Server database environment. In my startup class, the database connection is defined by commenting out the unused connection. If a SQL Server database is to be used then one would only need to modify the connection details in the database_etl_sqlserver.py file ensuring that the schema maintains alignment. Using a SQL database also allowed an opportunity to create a user table and the ability to authenticate on the combination of username and password, something the original program did not do.

One challenge I faced while working on this enhancement was to use the correct syntax in my SQL CRUD operations to mitigate the possibility of SQL injection attacks. After reading through various resources, I found that the use of parameterized SQL statements was best practice and therefore implemented it into the codebase. 
Overall, I have met all of my objectives for all three enhancements and am happy with the final product.

<br>
Repository - **[Enhancement Three](https://github.com/rgwebster3/CS499-Enhancement-Three)**
