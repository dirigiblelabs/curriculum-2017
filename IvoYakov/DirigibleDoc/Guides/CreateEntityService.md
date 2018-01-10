# Create an Entity Service
In general, the Entity Service is a fully capable RESTful service as it is defined by REST architectural style for performance, scalability, simplicity, and so on. It exposes the CRUD operations of a given domain model object. Underneath it,the database store is connected as a data transfer layer. In this guide you will learn how to create an Entity Service that works with your Data Structures.

## Prerequisites
You must have a Data Structure Created.</br>
> Follow the steps in the [Create a Database Table](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/Guides/CreateDatabaseTable.md) task to create a Database Table

## Steps
1. Create a Scripting Service.</br>
_Right-click_ on your project in the **Workspace** heirarchy and select **New > Scripting Service** and _click_ **Next**.
2. Select a Service Template.</br>
From the list in the popup _select_ **JavaScript Entity Service on Table** and _click_ **Next**.
3. Connect the Service to your Table.</br>
From the list of tables _select_ the name of the table that you created in the previous task and _click_ **Next**
4. Select a location for your service and name it.</br>
a) In the popup _find_ **<project_name>/ScriptingServices** and _select_ it.</br>
b) In the lower part of the popup _write_ your Scripting Service's name. It should be a *.js file.
5. _Click_ **Finish**.

## Result
Now that you are done, you should see your Scripting Service in the workspace heirarchy under **<project_name>/ScriptingServices/<project_name>**.</br>
> There should be 4 files in that location:</br>
> **<service_name>.entity**</br>
> **<service_name>.js**</br>
> **<service_name>.swagger**</br>
> **<service_name>_lib.js**</br>

_For more information see:_</br>
[Scripting Services](http://www.dirigible.io/help/scripting_services.html)</br>
[Entity Service](http://www.dirigible.io/help/entity_service.html)

## Navigation
Guide: [Understanding Dirigible](https://github.com/dirigiblelabs/curriculum/edit/master/IvoYakov/DirigibleDoc)
</br>
1. [Create a Project in Dirigible.](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateProject.md)
2. [Create a Database Table.](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateDatabaseTable.md)
3. [Create an Entity Service for the Database Table.](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/Guides/CreateEntityService.md)
4. [Create a User Interface for the Service.](https://github.com/dirigiblelabs/curriculum/tree/master/IvoYakov/DirigibleDoc/Guides/CreateUserInterface.md)
