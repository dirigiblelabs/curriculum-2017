# <i>Eclipse Dirigible</i> 

Eclipse Dirigible™ is a Cloud Development Platform providing development tools and runtime environment. It supports full development life-cycle of on-demand applications by leveraging in-system programming models and rapid application development techniques. Eclipse Dirigible can be used by students and developers.

![alt text](https://github.com/dirigiblelabs/curriculum/blob/master/ElenaFoteva/Dirigible%20Documentation/dirigibleB.jpg)

## Advanced uses of Eclipse Dirigible

This documentation contains the following sections:
* GitHub Interaction - share your Eclipse Dirigible project with a GitHub repository; pull and push changes
* Launchpad Templates - create launchpad items for your Eclipse Dirigible project
* Transport Content in Eclipse Dirigible - transport content from one Dirigible acount to another

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
