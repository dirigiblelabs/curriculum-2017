# Creating a Database Table

The term Data Structures reffers to the domain model of the application you create. In Dirigible Data Structures are persistent data storage, such as databases. The following tutorial will provide a simple example of creating a table in a Relational database, with which your project can store data and modify it.

## Prerequisites
You must have an empty Dirigible Project Created.</br>
Go back to the [previous task](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/Guides/CreateProject.md) to find out how to create one.

## Steps

1. Create a new Data Structure.</br>
a) _Right-click_ on your **Project Name** in the heirarchy.</br>
b) _Select_ **New > Data Structure** and from the list _select_ **Relation Database Table**.


2. Add columns to the table.</br>
a) In the lower left corner of the popup _click_ **Add**.</br>
b) _Write a name_ for the column, then _specify it's data type_. </br>
c) When desired columns are added _click_ **Next**.</br>
d) You will be prompted to _write a name_ for your table.</br>

3. Add sample data to the table.</br>
a) _Right-click_ your **Project Name** in the heirarchy and _select_ **New/Data Structure**.</br>
b) _Select_ **Delimeter Segmented Value Sample Data** and then _select_ the table you created from the list.</br>

4. _Right-click_ on your **project name** in the heirarchy and _select_ **Publish**.


## Result

Once the table is created, you can wirte an SQL Query to it.
* On the top of the screen, next to Workspace, _click_ on **other > Database Perspective**.
* Now _write_ an SQL Query to your table in the **SQL Console**.

## Navigation
Guide: [Understanding Dirigible](https://github.com/dirigiblelabs/curriculum/edit/master/IvoYakov/DirigibleDoc)
</br>
1. [Create a Project in Dirigible.](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateProject.md)
2. [Create a Database Table.](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateDatabaseTable.md)
3. [Create an Entity Service for the Database Table.](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/Guides/CreateEntityService.md)
4. [Create a User Interface for the Service.](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateUserInterface.md)
