# Creating User Interfaces

### **Context**

The Dirigible environment allows you to manage the *user interface* of your project by following the next steps.

### **Prerequisites**

* Create a **project** in the Workspace Explorer. See [*Creating a new project*][1].
* Create a **data structure** in the project. See [*Creating a new data structure*][1].
* Create a **scripting service** in the project. See [*Creating Scripting Services*][2].
 
### **Procedure**
1. Right-click on the __*.entity*__ file in your project > __*Generate*__ > __*User Interface for Entity Service*__.
2. From the available templates choose  __*List Entities*__ > Click __*Next*__.
3. Mark the check-box of the columns of your table that  you want to be shown or select all by clicking the __*Select all*__ button> Click __*Next*__.
4. Enter the  __*File name*__  > Click __*Next*__ > Enter the  __*Page Title*__ > Click __*Finish*__.
5. Right-click on the folder __*Web Content*__ > __*New*__ > __*User Interface*__.
6. From the available templates choose __*Index Page with Main Menu, Header and Footer*__ > Click __*Next*__.
7. Enter the  __*File name*__  > Click __*Next*__ > Enter the  __*Page Title*__ > Click __*Finish*__.

	> In the __*Web Content*__ folder the following files will be generated:
    > - *footer.html* file
    > - *header.html* file
    > - *index.html* file
    > - *main.menu* file
    > - *.html* file

8. Click on the __*main.menu*__ file so that you can edit it until it looks like this: 

```
    [
        {
          "name": "Welcome",
          "link": "index.html",
          "subMenu": []
        },
        {
          "name": "...",    // the name of your project
          "link": "...html",
          "subMenu": []
        }
    ]
 ```
  
9. Click the __*Save*__ button on top of the *Workspace Explorer*.

### **Results**

You can check the results by clicking on the __*index.html*__ file, then in the __*Preview*__ window right-click on the link > __*Go to that url*__. The browser will open the .html file and you will be able to see your database.

### **Next Steps**
 You can also check how to manage entities in the user interface of your project. See [_Managing Entity Template][3].

[1]: https://github.com/dirigiblelabs/curriculum/tree/master/TeodoraBancheva/WrittenDocumentation/DataStructures.md
[2]: https://github.com/dirigiblelabs/curriculum/tree/master/TeodoraBancheva/WrittenDocumentation/ScriptingServices.md
[3]: https://github.com/dirigiblelabs/curriculum/tree/master/TeodoraBancheva/WrittenDocumentation/ManageEntityTemplates.md
