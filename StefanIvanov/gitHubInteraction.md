# Eclipse Dirigible - GitHub Interaction
In this tutorial, you will learn how to share your Eclipse Dirigible project with a GitHub repository, how to pull and push changes from/to GitHub.


## Prerequisites

Go to https://github.com/ and log in to your account or sign up if you don't have account. Log in Dirigible Web IDE.

## Procedure

We will show you how to make a new project in the Dirigible Web IDE. If you want to do it for existing project, miss steps 2. and 3.

To create and upload new project, follow the steps:

1. Click + >  **New repository**, enter Repository name 
2. Click **Create repository**. Copy the URL, showing in the **Quick setup box**.
3. Open the Dirigible Web IDE in the Workbench persepective. 
4. Click **New** > **Project**, Enter project name. 
5. Click **Next** and choose **Blank Application** > **Finish**.
6. Right-click on the project name, **New** > **Scripting Service**. Select **Hello world service (JavaScript)** > **Next**. Enter File Name and click **Finish**.
7. Right-click on the project name, **Team** > **Share**. Paste the URL, copied on step 1 in the field Location. Enter Commit message, Username, Password and Email. Click **Ok**. You can see your uploaded project in the GitHub repository.

#### When you make changes on your project in GitHub

Right-click on the project name, **Team > Pull > Ok**. Your changes are made in the project in Dirigible Web IDE.

#### When you make changes on your project in Dirigible Web IDE
1. Right-click on the project name, **Team > Push**. 
2. Enter **Commit message**, **Username**, **Password** and **Email**. 
3. Click **Ok**. 
Your changes are made in the project in GitHub.
