# How to Create a User Interface in Dirigible
## Prerequisites
* Have a database created in your project in Dirigible. For reference you may read [How to Create a Database in Dirigible](https://github.com/dirigiblelabs/curriculum/blob/master/IvetaChampoeva/Documentation/Basic%20Steps/Dirigible%20Basics%20-%20Create%20Database.md)
* Have a scripting service created in your project in Dirigible. For reference you may read [How to Create a Scripting Service in Dirigible](https://github.com/dirigiblelabs/curriculum/blob/master/IvetaChampoeva/Documentation/Basic%20Steps/Dirigible%20Basics%20-%20Create%20Scripting%20Service.md)
## Overview
After executing the following steps you will have a sample User Interface generated for your project.
## Steps to create a UI representing your database table
1. Go to your **ScrptingService**, expand it and find \*.entity file
2. Right click on the file **Generate -> User Interface for Entity Service**
3. Select the wanted template for the UI
4. Choose which columns you want to be shown
5. Input a name for the html file that will be generated
6. Choose a title for the html page and click **Finish**
## Steps to create a UI representing your project
1. Go to your **Web Content**, right click **New > User Interface**
2. Choose **Index Page with Main Menu, Header and Footer** form the templates.
3. Input a name for the html file
> By deault it is index.html, you may leave at that, as it is an appropriate name for a main page
4. Choose a title for your html page and click **Finish**
5. (Optional)You can view the UI, by going to the main html file. Copy the URL from **Preview** and open it.
6. You can easily connect the html file for the Scripting Service to the main html page, by exploring the generated content and applying little corrections.
> For example, you can add it to the main menu. In **Web Content**, go to main.menu file and add an object for tab, with property **link** and value \*.html
