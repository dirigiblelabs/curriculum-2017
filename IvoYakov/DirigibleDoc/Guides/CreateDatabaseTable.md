# Creating a Database Table

The term Data Structures reffers to the domain model of the application you create. In Dirigible Data Structures are persistent data storage, such as databases. The following tutorial will provide a simple example of creating a table in a Relational database, with which your project can store data and modify it.

## Prerequisites
You must have an empty Dirigible Project Created.</br>
Go back to the [previous task](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/Guides/CreateProject.md) to find out how to create one.

## Steps

1. Create a new Data Structure.</br>
a) Right-click on your **Project Name** in the heirarchy.</br>
b) Select **New > Data Structure** and from the list choose **Relation Database Table**.


2. Add columns to the table.</br>
a) In the lower left corner of the popup click **Add**.</br>
b) Write a name for the column, then specify it's data type. </br>
c) When desired columns are added press **Next**.</br>
d) You will be prompted to write a name for your table.</br>

3. Add sample data to the table.
a) Right-click your **Project Name** in the heirarchy and select **New/Data Structure**.</br>
b) Select **Delimeter Segmented Value Sample Data** and then select the table you created from the list.</br>

4. Publish your project. Right-click on your project name in the heirarchy and select **Publish**.


## Result

Once the table is created, you can wirte an SQL Query to it.
* On the top of the screen, next to Workspace, click on **other > Database Perspective**.
* Now write an SQL Query to your table in the **SQL Console**.

## Navigation
Guide: [Understanding Dirigible](https://github.com/dirigiblelabs/curriculum/edit/master/IvoYakov/DirigibleDoc)
</br>
1. [Create a Project in Dirigible.](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateProject.md)
2. [Create a Database Table.](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateDatabaseTable.md)
3. [Create an Entity Service for the Database Table.](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/Guides/CreateEntityService.md)
4. [Create a User Interface for the Service.](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateUserInterface.md)
