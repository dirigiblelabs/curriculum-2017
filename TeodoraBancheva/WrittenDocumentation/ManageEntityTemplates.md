# Managing Entity Template

### **Context**

The Dirigible environment allows you to generate the *user interface* of your project by also using the *Manage Entity template*. You will be able to *create* new instances, *delete* ones and *change* the properties of the instances in your database.

### **Prerequisites**

* Create a **project** in the Workspace Explorer. See [*Creating a new project*][1].
* Create a **data structure** in the project. See [*Creating a new data structure*][1].
* Create a **scripting service** in the project. See [*Creating Scripting Services*][2].
* Create a **user interface** in the project. See [*Creating User Interfaces*][3].
 
### **Procedure**

1. Right-click on the __*.entity*__ file in the __*Scripting Services*__ folder > __*Generate*__ > __*User Interface for Entity Service*__.
2. From the available templates choose  __*List Entities*__ > Click __*Next*__.
3. Mark the check-box of the columns of your table that  you want to be shown or select all by clicking the __*Select all*__ button.
* In the __*Widget*__ field you can change the type of the column from *text* to *date*, *dropdown*, *list*, etc.
* In the __*Label*__ field you can change the name that will be shown above each column.
When you've made the changes click __*Next*__.

4. Enter the  __*File name*__  > Click __*Next*__ > Enter the  __*Page Title*__ > Click __*Finish*__.

 >In the __*Web Content*__ folder the following files will be generated:
  > * *footer.html* file
  > * *header.html* file
  > * *index.html* file
  > * *main.menu* file
  > * *.html* file
  > * *_manage.html* file

### **Results**

You can check the results by clicking on the __*_manage.html*__ file, then on the __*Preview*__ window. You will be able to change the properties of the instances in your database,to create new instances and to delete ones by clicking on __*New*__ or on the entity instance and then on __*Edit*__ or __*Delete*__.

### **Next Steps**
 You can also check how to create a *wiki page* for your project. See how to [Write Documentation][4]

[1]: https://github.com/dirigiblelabs/curriculum/tree/master/TeodoraBancheva/WrittenDocumentation/DataStructures.md
[2]: https://github.com/dirigiblelabs/curriculum/tree/master/TeodoraBancheva/WrittenDocumentation/ScriptingServices.md
[3]: https://github.com/dirigiblelabs/curriculum/tree/master/TeodoraBancheva/WrittenDocumentation/UserInterfaces.md
[4]: https://github.com/dirigiblelabs/curriculum/tree/master/TeodoraBancheva/WrittenDocumentation/Documentation.md
