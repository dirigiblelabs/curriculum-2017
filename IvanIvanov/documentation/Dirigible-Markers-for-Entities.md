# Eclipse Dirigible - Markers for Entities

In this tutorial, you will learn how to create map markers for entity in Eclipse Dirigible. For more information, you can watch [**this video**](https://www.youtube.com/watch?v=0NqG9c1Zaeo&list=PLNKd01MEkVeJYLtQ2S4HZyDQ1turGCZwr&index=4).


### Prerequisites
* *Log in* [Dirigible Web IDE](http://dirigible.eclipse.org/).

### Table Of Contents

| Step	        | Name          |
| :------------:|:--------------|
| 1. | Relational Database Table |
| 2. | Delimiter Separated Values Sample Data |
| 3. | CRUD Service on Table (JavaScript) |
| 4. | List and Manage Entity |
| 5. | Markers for Entities |


### Procedure
To try the option, follow the steps:
1. Open the Dirigible Web IDE in the Workbench persepective. 
	1. Click *New* > *Project*, enter name of the project in field **Enter project name**.
	2. Click *Next* and choose *Blank Application* > *Finish*.
2. Right-click on the project name, *New* > *Data Structure*.
	1. Select **`Relational Database Table`** and click **Next**. 
	2. Click *Add* and enter *Name*, choose *Type*. You can enter *Length*, and other options.  
	3. Click *Ok*.
	4. To add more columns, repeat step 2. You should add colums, which will contain coordinates. For example:
```
| LAT | DOUBLE | 0 | true | false |
| LNG | DOUBLE | 0 | true | false |
```
3. When you're ready, click *Next* > enter **File Name** > *Finish*.
4. Right-click on the project name > *Publish*.
5. Right-click on the project name, *New* > *Data Structure*.
 	1. Select **`Delimiter Separated Values Sample Data`** > *Next*. 
 	2. Find the name of your project from *Available Tables* and click on it.
 	3. Click *Next* > *Finish*.
6. Enter the information, according the columns, you created on step 2. You must use **|** separator between the columns.

7. Right-click on the project name > *Publish*.
8. Right-click on the project name, *New* > *Scripting Service*. 
	1. Select **`CRUD Service on Table (JavaScript)`** > *Next*. 
	2. Select your project from *Available Tables*. 
	3. Click *Next* and enter **File Name**.
	4. Click *Finish*.
9. Unfold the project > *ScriptingServices* > project > *entity*.
	1. Right-click on the created entity > *Generate* > *User Interface for Entity Service*. 
	2. Select **`List and Manage Entity`**. 
	3. Click *Next* and *Select All*. 
	4. You can change fields' *Label*. 
	5. Click *Next* and enter **Page Title**.
	6. Click *Next* and enter **File Name**.
    7. Click *Finish*.
10. You can see your html by double click on the tab *Preview*.
11. Unfold the project > *ScriptingServices* > project > **entity**. 
	1. Right-click on the created entity > *Generate* > *User Interface for Entity Service*. 
	2. Select **`Markers for Entities`**. 
	3. Click *Next* and *Select All*.
	4. You can change fields' *Label*. 
	5. Click *Next* and enter **Page Title**.
	6. Click *Next* and Enter **File Name**.
	7. Click *Finish*.
	8. The map file opened. You should change `YOUR_APP_KEY` in the script tag for googleapis.
12. Save the changes. See again your changes by double click on the tab *Preview*. The map with markers will show.
13. If you want to connect the map to some item in *index.html*:
	1. Navigate to project > *ScriptingServices* > project > *extension* > *Management.js*.
	2. Change *CONST HTML_LINK = "* the name of your manage entity file, created on step 9 *.html "*
	3. Navigate to project > *ScriptingServices* > project > *extension* > *Map.js*
	4. Change *CONST HTML_LINK = "* the name of your map file *.html "*.
	5. Save the changes.
14. Now you can open **index.html**.
