# Dirigible - Basics - 2. Scripting Services

### **Context**

The Dirigible environment allows you to create  and use your own *scripting service* by following the next steps.

### **Prerequisites**

* Create a **project** in the Workspace Explorer. See [*Dirigible - Basics - 1. Data Structures/ Prerequisites/ Creating a new project*][1]
*  Create a **data structure** in the project. See [*Dirigible - Basics - 1. Data Structures/ Procedure/ Creating a new data structure*][1]
 
### **Procedure**
 
1. Right-click on the name of the project -> __*New*__ -> __*Scripting Service*__
2. From the *Available Templates* choose  __*Javascript Entity Service on Table*__
3. Choose a table which will be used during generation from the __*Available Tables and Viwes*__  -> Click __*Next*__
4. In the __*File Name*__ field enter the name of the scripting service -> Click __*Finish*__

> In the folder __*Scripting Services*__ in your project you will have the following files:
> * *.entity* file
> * *.js* file
> * *.swagger* file
> * *_lib.js* file

### **Results**

You can check the results by clicking on the __*.js*__ file. Then in the __*Preview*__ window you will be able to see the data from your table in JSON format.
    
### **Next Steps**
* You can also check how to create User Interface in your Project. See [_Dirigible - Basics - 3. User Interfaces/Procedure_][2]

[1]: https://github.com/dirigiblelabs/curriculum/tree/master/TeodoraBancheva/WrittenDocumentation/DataStructures.md
[2]: https://github.com/dirigiblelabs/curriculum/tree/master/TeodoraBancheva/WrittenDocumentation/UserInterfaces.md
