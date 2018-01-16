# How to Create a Database in Dirigible
## Prerequisites
* Have a project created in Dirigible. For reference you may read [How to Create a Project in Dirigible](https://github.com/dirigiblelabs/curriculum/blob/master/IvetaChampoeva/Documentation/Basic%20Steps/Dirigible%20Basics%20-%20Create%20Project.md)
## Overview
After executing the following steps you will have a new database for your project, that can store the needed information for developing.
## Steps
1. Right click on you project **New > Data Structure**
2. Choose **Relational Database Table**.
3. Start adding all the columns that you should have in your table, by clicking **Add**
> For each column you can choose the type, length, if null values are allowed, if it is a primary key and if you want it to have a default value. 
4. When you created all the necessary columns, choose a name for your table and click **Finish**
5. Right click on your project and choose **Publish**. That will make your new table available outside your design area.
6. (Optional) To execute queries in your tables go to the upper menu **other... > Open Perspective > Database**. In the bottom panel you have a **SQL Console** in which you can execute the queries you want.
7. You can fill your table by right clicking on your project and choosing **New > Data Structure > Delimiter Seperated Values Sample Data**. Next you choose by name the table that you want to fill. After you have finished adding rows in you tables you should right click on your project and choose **Publish** to make the information available outside your design area.
