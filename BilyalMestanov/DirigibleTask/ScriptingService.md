# Creating a Scripting Service

## Context

Scripting services allow you to write custom JavaScript code that can be executed when an endpoint of your application is accessed.



## Prerequisites

- Eclipse Dirigible IDE

- Existing project

- Existing table




## Procedure

1. Open Eclipse Dirigible IDE
2. Under the `Workspace Explorer` tab locate the root folder of your project.
3. Right-click on the root folder.
4. A drop-down will appear. Select `New > Scripting Service`.
5. The window will now prompt you to select a template for your service. Select `JavaScript Entity Service on Table`  and click `Next`.
6. Locate the `File Name` field at the bottom of the window and give your service a name. 
7. Click `Finish`.



## Result

4 new files will be generated for you: 

* `<Root>/Scripting Services/<Your project name>/<Your service name>.js `
* `<Root>/Scripting Services/<Your project name>/<Your service name>.entity `
* `<Root>/Scripting Services/<Your project name>/<Your service name>.swagger `
* `<Root>/Scripting Services/<Your project name>/<Your service name>_lib.js `




## Navigation

- [Intro](README.md)


- [Creating a New Project](NewProject.md)
- [Creating a Data Structure ](DataStructure.md)
- [Creating a Scripting Service](ScriptingService.md)
- [Creating User Interfaces](UserInterfaces.md)
- [Creating Wiki Pages](WikiPages.md)