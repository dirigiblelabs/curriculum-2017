# Create a Data Structure

Follow these steps to create a data structure for your Eclipse Dirigible project.

## Prerequisites

* Have a project created in Eclipse Dirigible Web IDE.

## Context

Applications need persistent storage to optimally operate with data. First you should create the definition of your data structures. You can do that easily in the Eclipse Dirigible Web IDE following a few steps.   

## Procedure

1. Open Eclipse Dirigible Web IDE and navigate to **Workspace explorer**
2. Select the project for which you want to create a data structure. Right-click on the project and choose **New > Data Structure** from the drop-down list.
3. Select a Template Type from the dialog window.
4. Add all the necessary properties for your data structure by clicking **Add** button. Enter the desired attributes for your column definition in the newly opened window and save it by clicking **OK**. Repeat this step as many times as you need to define the set of column definitions.

> You must define an attribute with name 'ID' as primary key by selecting the corresponding checkbox.

5. When you are ready with the design of your data structure click **Next** and enter appropriate name for your file, click **Finish** to save it.

## Results

Your data structures is saved and linked to the project. You can associate it with table in relational databases, but it is stored in JSON format.

## Next steps

* Create a scripting service



