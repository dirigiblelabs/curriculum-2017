# Create a Data Structure

Follow these steps in order to create a simple data structure for your Dirigible application.

## Prerequisites

* Have a project created in the Dirigible Web IDE.

## Context

Every application needs some form of persistence in order to hold the data it manipulates and works with. But before we are able to create, update, delete or do anything that involves data, we must first define our data structures that will comprise our application's data model. Think of data structures as your tables in a database.

## Procedure

1. Navigate to the **Workspace Explorer** view in the Dirigble Web IDE where your project files reside.
2. Right-click on your project. A dropdown menu appears.
3. Select **New > Data Structure**.
4. In the newly opened dialog select a Template type. Choose **Next**.

  > What kind of template you choose depends on the situation, but in most cases what you'll need is a *Relational Database Table*.

5. It's time to define what properties your data structure will have. This is done in a SQL-style manner by defining the characteristics for each column/property of your data structure. Click **Add**. A new dialog appears.
6. Fill out all the information regarding the column - *Name*, *Type*, *Length* and etc. In order to add this column definition click **OK**.
7. Add as many column definitions as you would like. Then click **Next**.
8. Choose an appropriate file name for your data structure. After you're done choose **Finish**.

  > **NOTE**: All data structure files should end with *.table* postfix. For example: *students.table*

## Results

Your newly generated Data Structure files will be stored at <b>*Project Name*>DataStructures>*Project Name*</b> in the **Workspace Exlorer** view.

## Next steps

1. [Create a Scripting Service][1]
2. [Create a User Interface][2]

[1]: https://github.com/dirigiblelabs/curriculum/tree/master/NikolayMateev/WrittenDocumentation/Dirigible-Basics/ScriptingServices.md
[2]: https://github.com/dirigiblelabs/curriculum/tree/master/NikolayMateev/WrittenDocumentation/Dirigible-Basics/UserInterfaces.md
