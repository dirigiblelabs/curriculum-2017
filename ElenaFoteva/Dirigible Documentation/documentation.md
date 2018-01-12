# <i>Eclipse Dirigible</i> 

Eclipse Dirigible™ is a Cloud Development Platform providing development tools and runtime environment. It supports full development life-cycle of on-demand applications by leveraging in-system programming models and rapid application development techniques. Eclipse Dirigible can be used by students and developers.

![alt text](https://github.com/dirigiblelabs/curriculum/blob/master/ElenaFoteva/Dirigible%20Documentation/dirigibleB.jpg)

## Advanced uses of Eclipse Dirigible

This documentation contains the following sections:
* Mobile Applications - create native mobile applications with Eclipse Dirigible and Tabris.js
* GitHub Interaction - share your Eclipse Dirigible project with a GitHub repository; pull and push changes
* Launchpad Templates - create launchpad items for your Eclipse Dirigible project

### Dirigible - Mobile Applications

#### Preparation
Before starting the procedure you should:
1. Launch Dirigible Web IDE
2. Download Tabris.js form Google Play or Apple Store

#### Procedure
1. Make a new project in the Dirigible Web IDE
* Open the Dirigible Web IDE in the Workbench persepective
* Click **New** > **Project**, enter name for your project in *Enter project name*. Click **Next** and choose **Blank Application** > **Finish**
2. Create new data structure
* Right-click on the project name, **New** > **Data Structure**
* Select **Relatonal Database Tabel** > **Next**
3. Add column
* After **Next** from the previos step click **Add**. Eneter name in *Name*, type in *Type*, fill the other fields and click **OK**
4. Add more columns and proceed
* repeat step 3 with the other necessary properties for your table
* click **Next**. Enter name for your table in *File name* and click **Finish**
5. Create Scripting Service
* Right-click on the project name, **New** > **Scripting Service**
* Choose **JavaScrip Entry Service on Table** > **Next**. Select the name of your table and click **Next**. Enter name for the scripting service in *File name* (for example - something.js) and click **Finish**
6. Generate the UI of your entry service
* Unfold **ScriptingServices** 
* Unfold and package created in step 5
* Right-click on something.entry > **Generate** > **User Interface for Entry Services**. Select **Mobile Create Entries** and click **Next**
* Label all avaliable table properties accordingly and click **Next**. Enter name in *File name* and change format to .js Enter package name in *Package name* and click **Next**
* Enter title in **Page Title** and click **Finish**
* You can edin the newly created .js file
7. Generte UI for another entry service
* repeat step 6
8. Tests with Tabris.js mobile framework
* Unfold the packages created in steps 6 and 7
* Choose one of the created (for example - first) and select the package.json file in it. Click **Preview**. **Tabris.js** will open in a second.
* Write the name of the package you choosed after "/mobile/" and before "/package.json" in **Local Tabris.js script by URL**. The mobile application should work as you expected


### Eclipse Dirigible - GitHub Interaction

#### Preparation
Before starting the procedure you should:
1. **Sign in** in your GitHub account(or **Sign up**, if you do not have one)
2. Launch Dirigible Web IDE

#### Procedure
1. Create new GitHyb repository and copy the URL
* Go to your GitHub account
* Click **+** > **New repository**, enter name for your repository in *Repository name* and click **Create repository**
* Copy the URL, from the *Quick setup box*
2. Make a new project in the Dirigible Web IDE
* Open the Dirigible Web IDE in the Workbench persepective
* Click **New** > **Project**, enter name for your project in *Enter project name*. Click **Next** and choose **Blank Application** > **Finish**
3. Set up the project
* Right-click on the project name, **New** > **Scripting Service**
* Select **Hello world service (JavaScript)** > **Next**. Enter name for the file in *File Name* and click **Finish**
4. Upload the project in GitHub
* Right-click on the project name, **Team** > **Share**
* Paste the URL, from step 1 in the field *Location*
* Enter *Commit message*, *Username*, *Password* and *Email*. Click **Ok**

#### Interaction between GitHub and Dirigible Web IDE
1. Apply changes from GitHub to Dirigible Web IDE
* Right-click on the project name, **Team** > **Pull** > **Ok**
2. Apply changes from Dirigible Web IDE to GitHub
* Right-click on the project name, **Team** > **Push**. Enter *Commit message*, *Username*, *Password* and *Email*. Click **Ok**


### Eclipse Dirigible - Launchpad Templates

#### Preparation
1. Launch Dirigible Web IDE

#### Procedure
1. Make a new project in the Dirigible Web IDE
* Open the Dirigible Web IDE in the Workbench persepective
* Click **New** > **Project**, enter name for your project in *Enter project name*. Click **Next** and choose **Blank Application** > **Finish**
2. Create User Interface
* Unfold the project
* Right-click **Web content** > **New** > **User interface**
* Select **Launchpad Item** and click **Next**
* Enter title in *Page Title* and click **Next**
*	Enter name in *File Name* and click **Finish**
3. Add more User Interfaces
* repeat step 2
4. Preview the launchpad items
*  Right-click **Web content** > **index.html**
5. Customize the launchpad of your project
* Right-click **ScriptingServices** 
* select User Interfcace > **extension**
* modify something
6. Save changes and view them in **index.html**
