
# Create a User Interface
Now you will learn how to create a User Interface, so the users can easily interact with your application.
## Overview
User Interface is the what users see in an application. It helps them to easily interact with the API. Eclipse Dirigible have the functionality to automatically create User Interface.
## Prerequisites
-	Log in Eclipse Drigible IDE.
-	Existing project.
-	Existing database table.
-	Existing scripting service.
## Procedure
1.	In **Workspace Explorer** find the following file: \<Your project name>/Scripting Services/\<Your project name>/\<Your service name>.entity.
2.	Right click on the file, then **Generate > User Interface for Entity Service**.
3.	A pop-up with a list of templates will show. 
4.	Select **List Entities** and click **Next**.
5.	Click on **Select All** to choose all fields and click **Next**.
6.	Fill **File Name** with a name for your User Interface and click **Next**.
7.	Fill **Page Title** field and click **Finish**. Then a file will be generated under **WebContent** folder.
8.	Go to **WebContent** folder, right click on it and choose **New -> User Interface**.
9.	In the pop-up select **Index Page with Main Menu, Header and Footer** and click **Next**.
10.	Click **Next** again.
11.	Fill the **Page Title** field and click **Finish**. Then new files will be generated in the **WebContent** folder.
12.	Click on **main.menu** file and replace the name and link of the second record with yours. It should look like this: 
 ![Image](https://github.com/dirigiblelabs/curriculum/blob/master/LuchezarSerdarski/mainMenu.png)
13.	Click on the **Save** button in the top left corner.
## Results
Now you have a User Interface for your entity.

## Other tutorials
[Create Data Structure](https://github.com/dirigiblelabs/curriculum/blob/master/LuchezarSerdarski/CreateDataStructure.md)

[Create Scripting Services](https://github.com/dirigiblelabs/curriculum/blob/master/LuchezarSerdarski/CreateScriptingServices.md)
