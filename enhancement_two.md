<hr>
**| [Home](https://rgwebster3.github.io/index.html) | [Code review](https://rgwebster3.github.io/code_review.html) | [Enhancement One]() | [Enhancement Two]() | [Enhancement Three]() |**
<hr>

### Enhancement Two
<br>

The artifact I chose for my Computer Science Capstone is a program that I developed in my CS-410 Software Reverse Engineering course during the 24EW5 term. It is a rudimentary client management application that displays a client and choice of selected service. It also allows the user to change the client’s selected service between brokerage or retirement. I selected this item as my artifact mainly because I found considerable satisfaction in developing a functional program that shared some commonalities with my current career. The planned enhancement to this program will demonstrate my proficiency with algorithms and data structures.

The objective I had for this enhancement was to utilize a list and subsequent pandas data frame to manage and display the client list. The original program simply used string variable assignments to store client details to include a selected service. This method did not seem appropriately efficient and would prove to be a resource hog as the client list scaled up. I have met my objective and have implemented the client list and pandas dataframe. While coding this feature it became apparent that I needed to create an algorithm to validate the client id input the user enters when editing or deleting. I needed to ensure that the input was within the lower and upper bounds of the pandas dataframe to mitigate errors and ensure proper functionality.

The biggest challenge I found while working on this enhancement was obtaining the proper index of the record that was to be edited or deleted. My form requires that the user enters the ID of the client they want to maintenance. At first, I thought I could just use the displayed row number minus one to get the correct index in the dataframe. This works if the client list is displayed with incremental ID so that if a client is added or deleted the ID for all clients is incrementally updated. I then thought to just return the index of the row where the user entered ID matches a record in the ID column. This algorithm worked perfectly after some trial and error with some Pandas syntax.

<br>
Repository - **[Enhancement Two](https://github.com/rgwebster3/CS499-Enhancement-Two)**
