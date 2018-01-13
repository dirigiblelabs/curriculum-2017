# Eclipse Dirigible<sup>TM</sup>

## Description


Dirigible is an open source project that provides Integrated Development Environment as a Service (IDEaaS) as well as runtime containers integration for the running applications. The environment itself runs directly in browser and therefore does not require additional downloads and installations. It packs all the needed components, which makes it self-contained and well integrated software bundle that can be deployed on any Java based Web Server.<br>
Target applications built with Dirigible are atomic yet self-contained cloud based modules that cover end-to-end vertical scenarios. These applications comply with the Dynamic Applications concepts and structure.



![img](https://github.com/dirigiblelabs/curriculum/blob/master/PerihanAsanova/Dirigible_Pros_Cons.png)



## Dirigible Web IDE

You can get Eclipse Dirigable from [here](http://dirigible.eclipse.org/).<br>
Enter your nickname and be in the Workbench persepective.

# Dirigible - Mobile Application

It is easy to create a mobile application using Eclipse Dirigible. <br>
Follow steps bellow to create your first mobile application: 

## - Create a project for your application

1. Open your Dirigible IDE.
2. Navigate to the Workspace Explorer view.
3. Choose <b> New </b> -> <b>Project</b>. 
4. A new dialog window appears.
5. Enter your project name and click <b> Next </b>.
6. Select <b>Blank Application</b>.
7. Click <b>Finish</b>.

## - Create a Data Structure

1. Navigate to the Workspace Explorer and find your project.
2. Right-click on your project. 
3. Select <b> New </b> -> <b>Data Structure</b>.
4. A new dialog window appears. 
5. Select <b>Relational Database Table</b>. 
6. Click <b> Next </b>.
7. To define columns for your database, click <b>Add</b>.
8. Enter the information for the column.
9. Click <b>OK</b>. 
10. Repeat step 7. to add more columns. When you are ready,  Click <b>Next</b>.
11. Give a name to your data structure - it shoud end with suffix <b>.table</b> <br>For example: <i>employee.table</i>
12. Click <b>Finish</b>.

You can find your Data Structure files here: <br>
<b>Project Name</b>-><b>DataStructures</b>-><b>Project Name</b>.

## - Create a Scripting Service
1. Navigate to the Workspace Explorer and find your project.
2. Right-click on your project. 
3. Select <b> New </b> -> <b>Scripting Service</b>.
4. A new dialog window appears. 
5. Select <b>JavaScript Entity Service on Table</b>. 
6. Click <b> Next </b>.
7. From the list with database tables, select which one do you want to use.
8. Click <b> Next </b>.
9. Give a name to your scripting service - it shoud end with suffix <b>.js</b> <br>For example: <i>employee.js</i>
10. Click <b>Finish</b>.

You can find your Scripting Service files here: <br>
<b>Project Name</b>-><b>ScriptingServices</b>-><b>Project Name</b>.

## - Generate User Interface for Entity Service 
### Mobile Create Entities
1. Go to <b>Project Name</b>-><b>ScriptingServices</b>-><b>Project Name</b>. Drop down. 
2. Find a file with <b>.entity</b> extension <i>(project name.entity)</i>
3. Right-click on the file.
4. Select <b>Generate</b>.
5. Select <b>User Interface for Entity Service</b>.
6. Choose <b>Mobile Create Entities</b> from the new window.
7. Click <b>Next</b>.
8. Check the checkboxes you see.
9. [optional] Edit your column name by clicking on it in the <b>Label</b> tab.
10. Click <b> Next </b>.
11. Give a name to your user interface - it shoud end with suffix <b>.js</b> <br>For example: <i>register.js</i>
12. Your package name should be like your user interface name (register).
13. Click <b>Next</b>.
14. Give a name to your page title.
15. Click <b>Finish</b>.

You can find your User Interface files here: <br>
<b>Project Name</b>-><b>MobileApplications</b>-><b>Package Name (register)</b>.



## - Generate User Interface for Entity Service 
### Mobile List and Manager Entities
1. Go to <b>Project Name</b>-><b>ScriptingServices</b>-><b>Project Name</b>. Drop down. 
2. Find a file with <b>.entity</b> extension <i>(project name.entity)</i>
3. Right-click on the file.
4. Select <b>Generate</b>.
5. Select <b>User Interface for Entity Service</b>.
6. Choose <b>Mobile List and Manager Entities</b> from the new window.
7. Click <b>Next</b>.
8. Check the checkboxes you see.
9. Click <b> Next </b>.
10. Give a name to your user interface - it shoud end with suffix <b>.js</b> <br>For example: <i>manage.js</i>
11. Your package name should be like your user interface name (manage).
12. Click <b> Next </b>.
13. Give a name to your page title.
14. Click <b>Finish</b>.

You can find your User Interface files here: <br>
<b>Project Name</b>-><b>MobileApplications</b>-><b>Package Name (manage)</b>.

## - Create Documenatation for your application
1. Navigate to the Workspace Explorer and find your project.
2. Right-click on your project.
3. A dropdown menu appears.
4. Select <b>New</b> -> <b>Wiki Page</b>. 
5. A new dialog appears.
6. Select a template type for your documentation. Choose Next.
7. Choose <b>Markdown Notation Guide</b>. 
8. Click <b>Next</b>.
9. Give a name to your documentation - it shoud end with suffix <b>.md</b> <br>For example: <i>help.md</i>
10. Give a name to your page title.
11. Click <b>Finish</b>.

> Dirigible - Fast Prototyping in Front of Your Customer


