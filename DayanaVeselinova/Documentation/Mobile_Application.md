## Using Eclipse Dirigible for Mobile Applications

### Create project with Data Structure:
1. *Open* **Eclipse Dirigible**.
2. On your *left* in the **Workspace Explorer**, *click* **New->Project**. 
3. Next, *enter* **project name** and *click* **Next**. 
4. *Choose* **Blank Application** from the given options and *click* **Finish**. 
5. *Expand* your project folder. *Right-click* on its name, **New->Data Structure**. 
6. *Choose* **Relational Database Table** and then, *click* **Next**.
7. In the *down-left* corner of the popup window, *click* **Add** button. 
8. *Design* your columns - *enter* name, *set* type, length and/or default value of the column and tick the checkboxes 
you need. *Click* **OK** when you are done. 
*Repeat* this action as many times you need. *Click* **Next** when you have entered all your columns. 
9. *Enter* **File Name** with **.table** extnesion. *Click* **Finish**.

### Creating Scripting Service:
1. *Expand* **Data Structures** on the **Workspace Explorer** under your project name. 
2. *Right-click* on your project, **New->Scripting Service**. 
3. *Choose* **JavaScript Entity Service on Table** and then, *click* **Next**. 
4. *Find* your project name from the list and *click* on it. Then, *click* **Next**. 
5. *Enter* **File Name** with **.js** extension. *Click* **Finish**.

### Creating Entity file:
1. On your *left*, in the **Workspace Explorer**, *find* folder **ScriptingServices**, *expand* it. 
2. *Right-click* on the **Entity file**, **Generate->User Interface for Entity Service**. 
3. *Choose* **Mobile Create Entities**. *Click* **Next**. 
4. *Choose* the columns you want and *click* **Next**.
5. *Change* the labels as they will appear in the application later. 
6. *Enter* **File Name** with **.js** extension. *Enter* **Package Name** (1). *Click* **Next**.
7. *Enter* **Page Title**. 
8. *Click* **Finish** when you are done. 

### Creating Mobile Application:
1. On your *left* in the **Workspace Explorer**, *expand* **MobileApplications** folder. 
2. *Double click* on the name you gave for the entity **.js** file. 
3. *Find* variable **successMessage** and *enter* the message you want. 
![First Image](https://github.com/dirigiblelabs/curriculum/blob/master/DayanaVeselinova/Documentation/1.PNG)

4. *Under* the folder **ScriptingServices**, *right-click* on the **entity file**, **Generate->User Interface for Entity Service**. 
5. *Choose* **Mobile List and Manage Entities**. *Click* **Next**. 
6. *Choose* the columns you want and *click* **Next**. 
7. *Enter* **Package Name** (2) and *enter* **File Name** with **.js** extension. *Click* **Next**.
8. *Enter* **Page Title**. *Click* **Finish**. 

### Preview the application:
1. On your *left* in the **Workspace Explorer**, *find* **package.json**, *click* on it. 
2. *Click* on the **http link** in the **Preview** section.
3. **AirServer** popup window will appear. Then, a popup window with **Tabris.js** will appear.
![Second Image](https://github.com/dirigiblelabs/curriculum/blob/master/DayanaVeselinova/Documentation/2.PNG).
4. *Change* the package name with (1).

![Third Image](https://github.com/dirigiblelabs/curriculum/blob/master/DayanaVeselinova/Documentation/3.PNG)

5. Another popup window will appear and will *prompt* you to *enter* **name** and **age**. 
6. *Click* **Save** and the **successMessage** will appear.
7. To see your database, *change* the **package name** to **Package Name** from (2).




 

