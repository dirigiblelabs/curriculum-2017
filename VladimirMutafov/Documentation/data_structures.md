## Create a data structure
To create a data structure for your application, follow these simple steps.

## Prerequisites
- Have an existing project in the Dirigible Web IDE

## Context
Most of the software applications need some kind of storage or persistency layer. Before we can manipulate our application's data, we must first define a data structure which models it. 
You can think of Dirigible's Data Structures as tables in a relational database, they simply describe what kind of data we are going to store and what properties does it have.

## Procedure

### Creating a data structure
1. _Right-click_ on your project. A dropdown should appear.
2. _Select_ the **New -> Data Structure** option.
3. In the popup window, choose **Relational Database Template** and _click_ **Next**.
4. In the newly opened form, you can define what properties your data structure will have. _Click_ **Add**. A new dialog should appear.
5. Provide information about the column - **Name**, **Length**, etc. To add this column definition, _click_ **Ok**.
6. You may add more columns and when you are finished, _click_ **Next**.
7. _Choose_ a name for your data structure. _Choose_ **Finnish**.

>NOTE: Every data structure you create should end with a .table postfix. For example, cars.table

### Publishing your data structure
1. _Navigate_ to the **Workspace Explorer**
2. _Right-click_ on your project and select **Publishing**

## Results
Your newly generated Data Structures can be found at **Project Name -> DataStructures -> Project Name** in the **Workspace Exlorer** view.

## Next steps
1. Create a Scripting Service
2. Create a User Interface
