#Dirigible - Basics -  Scripting Services

Steps to create a scripting service for your Dirigible application.

## Requirment

* Have a project created in the Dirigible Web IDE. [See steps][]
* You must have at least one Data Structure created. [See steps][]

## Procedure

1. Move mouse to the **Workspace Explorer** view in the Dirigible Web IDE.

2. Right-click on your project > drop down menu will appear.

3. Select **New > Scripting Service**. A new dialog appears.

4. Select a template from the available list, then click **Next**.

5. Choose a table which will be used during generation from the **Available Tables and Viwes**  -> Click **Next**.

6. In the *File name* field enter the name of the scripting service then click **Finish**.

   > Example: In the folder **Scripting Services** will appear following files (if we choose javascript entity service on table)
   >
   > * *.swagger* file
   > * *.entity* file
   > * *.js* file
   > * *_lib.js* file

## Result

Generated Scripting Service files will be stored at __*Project Name > ScriptingServices > Project Name*__

