# How to create a Mobile Application in Dirigible
## Prerequisites
1. Have a database created in your project. Follow this simple [tutorial](https://github.com/dirigiblelabs/curriculum/blob/master/IvetaChampoeva/Documentation/Basic%20Steps/Dirigible%20Basics%20-%20Create%20Database.md)
2. Have a scripting service created in your project. Follow this simple [tutorial](https://github.com/dirigiblelabs/curriculum/blob/master/IvetaChampoeva/Documentation/Basic%20Steps/Dirigible%20Basics%20-%20Create%20Scripting%20Service.md)
3. Understand how to create different types of UIs. Follow this simple [tutorial](https://github.com/dirigiblelabs/curriculum/blob/master/IvetaChampoeva/Documentation/Basic%20Steps/Dirigible%20Basics%20-%20Create%20User%20Interface.md)
## Overview
After executing the following steps you will have a sample Mobile Application generated.
## Steps
1. Create an User Interface for the \*.entity file in *Scripting Service*. When you choose the template click on **Mobile Create Entities**. This will let your create new records in the chosen table.
> When you name the new file, change its format to .js and rename the package to make it unique
2. Create an User Interface for the \*.entity file in *Scripting Service*. When you choose the template click on **Mobile List and Manage Entities**. This will let your view and update existing records in the chosen table.
> When you name the new file, change its format to .js and rename the package to make it unique
3. View your mobile application UIs by expanding *MobileApplications*. Then you choose a package and click on the file package.json. In the **Preview** section of the bottom panel, you can copy an URL.
4. Open any kind of mobile device simulator on your computer and paste the copied URL. To change it to the different UI you have previously created replace the *<unique_package_name>* in the URL with another existing package.
