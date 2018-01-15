##Dirigible - Mobile Applications

Here you will learn how to create native mobile applications with Eclipse Dirigible and Tabris.js. 
For this walkthrough, you need to download Tabris.js from Google Play or Apple Store.

##*Create project with Data Structure:*

1.	Create new Eclipse Dirigible project by clicking **New -> Project** and name it in the selected space.
2.	Select the **Blank application** template in the New Project Wizard.
3.	Click **Finish**.
4.	Expand your project folder. Click on its name, select **New->Data Structure**.
5.	Choose **Relational Database Table**. 
6.	Click **Next**.
7.	Click the **Add** button in the down-left corner of the popup window.
8.	Define an ID attribute as a primary key and add all the other necessary table properties /Name, Type, Length, etc./ Click **OK** when you are done. Do this as many times as you need. 
9.	Click **Next** when you are done.
10.	Name your table in the down-left corner of the popup window.
11.	Click **Finish**.

##*Create Scripting Service:*
1.	Expand your project folder.
2.	Click on its name, select **New->Scripting Service**.
3.	Choose **JavaScript Entity Service** on Table. Click **Next**.
4.	Select your table and add it to the project /click **Next**/.
5.	Name the scripting service in the down-left corner of the popup window.
6.	Click **Finish**.

##*Create Entity file:*
1.	Find folder **ScriptingServices** in the Workspace Explorer and expand it.
2.	Click the Entity file.
3.	Select **Generate->User Interface** for Entity Service.
4.	Click **Mobile Create Entities**.
5.	Click **Next**.
6.	Label all available table properties accordingly.
7.	Click **Next**.
8.	Change the file format to .js and name it. You can do that in the down-left corner of the popup window.
9.	Click **Next**.
10.	Enter Page Title.
11.	Click **Finish**.
##*Creating Mobile Application:*
1.	Expand **MobileApplications** folder from the Workspace Explorer on your left.
2.	Click on the name you gave for the entity .js file.
3.	Find **var successMessage** and enter any message you want.
4.	Generate the UI for anither entity service:click on the entity file,** Generate->User Interface** for Entity Service.
5.	Select Mobile List and Manage Entities.
6.	Click **Next**.
7.	Select all table properties.
8.	Click **Next**.
9.	Enter Package Name and File Name with .js extension. 
10.	Click **Next**.
11.	Enter Page Title. 
12.	Click **Finish**.
##*Testing with the help of the Tabris.js mobile framework:*
1.	Find and click on package.json, in the Workspace Explorer on your left.
2.	Click on the http link in the Preview section.
3.	Change the package name with register in the popup Tabris.js window.
4.	In the next popup window enter name and age.
5.	Click **Save** and the successMessage will appear.
6.	To see your database, change the package name to manage.
7.	You can always edit the registration details any time you want.
