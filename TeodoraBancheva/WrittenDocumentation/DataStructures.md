#Dirigible - Basics - 1. Data Structures

###**Context**

The Dirigible environment allows you to make and use your own *data structures* by following the next steps.

###**Prerequisites**

* ####**Creating a new project**

 * Right-click on the Workspace Explorer -> __*New*__ -> __*Project*__
 * A window will pop up where you can _**Enter the name**_ of your project and then click  __*Next* __
 * Choose a *Project Template* -> __*Blank Application* __-> __*Finish*__

The project will appear in the Workspace Explorer.

###**Procedure**

* ####**Creating a new data structure**

 * Right-click on the name of your project -> __*New* __-> __*Data Structure*__
  * Choose from the *Available Templates* -> __*Relational Database Table*__ -> __*Next*__
  * Click on the button __*Add*__ which is placed at the lower left corner in order to add columns to your data structure
  * Add all the columns you want by filling the fields for the column __*Name, Type, Length, Default Value*__ and also checking the boxes to determine if the column would be a __*Primary Key*__ and if it should contain only __*Not Null*__ values 
  * After you've created all of the columns click __*Next*__
  * In the next window that pops up enter a __*File Name*__ -> __*Finish*__  The table and it's columns' properties will appear in JSON format
   * Right-click on the name of your project -> __*Publish*__

* ####**Manipulating the data structure**

 * Click on the button __*other...*__ which is next to the *Workspace* one -> Choose __*Database*__  *Perspective* ->  __*OK*__ 
 
 An SQL console will apear where you can write *queries* and execute them by clicking __*Query*__. 
 >The result will always be an empty set because there is nothing yet in the database.

* ####**Adding a table that is alredy set**
 
  *  Right-click on the name of your project -> __*New* __-> __*Data Structure*__
  * Choose from the *Available Templates* -> __*Delimiter Separated Values Sample Data *__ -> __*Next*__
  * A window will pop up where you can choose __*Available tables*__ -> *Pick one* -> __*Next*__ -> __*Finish*__
  * Right-click on the name of your project -> __*Publish*__

 Now you can write and execute queries that will have results because the table is not empty.

###**Next Steps**
* You can also check how to create Scripting Services on Dirigible. See [_Dirigible - Basics - 2. Scripting Services/Procedure_][1]
[1]:https://github.com/dirigiblelabs/curriculum/tree/master/TeodoraBancheva/WrittenDocumentation/ScriptingServices.md
