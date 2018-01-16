# Create a Scripting Service

In order to create a _scripting service_ for your application in Dirigible you must take the following steps.

## Why do you need a scripting service?

During the development, you can use rich set of APIs, which give you access to the database and HTTP layer, utilities, and to the direct Java APIs underneath.

Support for creating unit tests is important and is therefore integrated as an atomic part of the scripting support itself - you can use the same language for the tests as the one for the services themselves.


## Requirements
In order to create a scripting service in Eclipse Dirigible you must:

1. Have a project created in the Dirigible Web IDE.
2. Have at least one Data Structure created.


## How to create a scripting service?

1. Navigate to the **Workspace Explorer** view in the Dirigible Web IDE where your project is.
2. **Right-click** on your project. A dropdown menu appears.
3. Select **New -> Scripting Service**. A new dialog appears.
4. Select one of the _Template types_ from the list. Choose **Next**.

  > NOTE: The scripting service you create depends on the situation, however in most cases what you will need is a _JavaScript Entity Service on Table_.

5. Choose a table from the available ones that you want to create a scripting service for. Then click **Next**.
6.  Write a file name for your scripting service. After you are done click **Finish**.


##  Where to find your scripting service?

Generated Scripting Service files will be at **Project Name -> ScriptingServices -> Project Name** in the **Workspace Explorer** view.
