# Create a Scripting Service

Follow these steps in order to create a scripting service for your Eclipse Dirigible application.

## Prerequisites

* [Have a project created in the Eclipse Dirigible Web IDE][3]
* [Have at least one Data Structure created][4]

## Context

The primary language used to implement services in Eclipse Dirigible is JavaScript. You can write your algorithms in *\*.js* files.

## Procedure


1. Navigate to the **Workspace Explorer** view in the Eclipse Dirigble Web IDE where your project files reside.
2. Right-click on your project. A dropdown menu appears.
3. Select **New > Scripting Service**. A new dialog appears.
4. Select a template from the available list. Click **Next**.

  > **JavaScript Entity Service on Table** is the most common type of scripting service you'll be creating.

5. The generated scripting service has to know with which database table to communicate and make requests to. So choose from the available tables the one you want to create a scripting service for. Then click **Next**.
6. Choose an appropriate file name for your scripting service. After you're done choose **Finish**.


## Results

Your newly generated Scripting Service files will be stored at <b>*Project Name* > ScriptingServices > *Project Name*</b> in the **Workspace Exlorer** view.


## Next steps

1. [Create a User Interface][1]
2. [Create an Entity Management User Interface][2]

[1]: https://github.com/dirigiblelabs/curriculum/tree/master/NikolayMateev/WrittenDocumentation/Dirigible-Basics/UserInterfaces.md
[2]: https://github.com/dirigiblelabs/curriculum/tree/master/NikolayMateev/WrittenDocumentation/Dirigible-Basics/ManagingEntityTemplates.md
[3]: https://github.com/dirigiblelabs/curriculum/tree/master/NikolayMateev/WrittenDocumentation/Dirigible-Basics/ProjectCreation.md
[4]: https://github.com/dirigiblelabs/curriculum/tree/master/NikolayMateev/WrittenDocumentation/Dirigible-Basics/DataStructures.md
