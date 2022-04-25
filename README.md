->**Sumerize your project and what problem it was solving?**

This project focuses on internal management system of oil refinery company on a large scale. In this project the oil refinery comany it was designed for has seven hierarchies named <br />
CEO <br />
Director <br />
Administrator <br />
Manager Management <br />
Manager Accountant <br />
Manager HR <br />
Employee <br />
Each hierarchy has its own login system and menu through which they can perform different functions. Oil refinery company has four plants located in different locations. This project includes employee attendance system, login system, salary calculator and plant management system. 

->**What did you do particularly well?**

In this project file handling is mostly used. It reads, parses, manipulates and save large ammount of data for different purposes life attendance records and plant information.

->**Where could you enhance your code? how would these improvements make your code more efficient, secure and so on.**

This code needs alot of improvements to make it run smoother and make is secure. <br />
Refactoring the core: There is still alot of code being reused and can be made into functions.<br />
Using database instead of text file: At the time of development due to lack of knowledge text file was used to store data while DBMS is more efficient and secure.<br />
Extra code: There is some extra code that is not nessessary and can be removed.

->**Which piece of code did you find most chellanging to write and how did you overcome this? What tools or resources are you adding to your support network**

Most chellanging parts were implementing employee attendance and salary calculation. Since file handling was being used so it was alot harder to edit data in it. Salary needed to be calculated based on working days. To solve this problem credit hour system was implemented. When attendance of an employee was marked then credit hours for that day would be set to 9 while on absent it would be set to 0. Salary was calculated be adding all the working hours in a month and multiplied by rate per hour.

->**What courses from this project will be particularly tranferable to other projects or course work?**

File handling is the core of this project. It is a pretty useful skill and can be used in many cases.

->**How did you make this program readable, maintainable and adaptable?**
To maintain readability the code is seperated into cpp and header file. Comments are added to prototypes reminding its functionality.
