# Create an Entity Service
In general, the Entity Service is a fully capable RESTful service as it is defined by REST architectural style for performance, scalability, simplicity, and so on. It exposes the CRUD operations of a given domain model object. Underneath it,the database store is connected as a data transfer layer. In this guide you will learn how to create an Entity Service that works with your Data Structures.

## Prerequisites
You must have a Data Structure Created.</br>
Follow the steps in the [previous task](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/Guides/CreateDatabaseTable.md) to create a Database Table

## Steps
#### 1. Create a Scripting Service
* Right-click on your project in the **Workspace** heirarchy and select **New > Scripting Service** and click **Next**.
#### 2. Select a Service Template
* From the list in the popup select **JavaScript Entity Service on Table** and click **Next**.
#### 3. Connect the Service to your Table
* From the list of tables select the name of the table that you created in the previous task and click **Next**
#### 4. Select a location for your service and name it
* In the popup find **<project_name>/ScriptingServices** and select it.
* In the lower part of the popup write your Scripting Service's name. It should be a *.js file.
#### 5. Click Finish

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
[Next Task](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/Guides/CreateUserInterface.md)</br>
[Previous Task](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/Guides/CreateDatabaseTable.md)</br>
[Back to Main](https://github.com/dirigiblelabs/curriculum/blob/master/IvoYakov/DirigibleDoc/)
