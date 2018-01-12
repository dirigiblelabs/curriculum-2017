## Eclipse Dirigible - GitHub Interaction

### Preparation
Before starting the procedure you should:
1. **Sign in** in your GitHub account(or **Sign up**, if you do not have one)
2. Launch Dirigible Web IDE

### Procedure
1. Create new GitHub repository and copy the URL
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

### Interaction between GitHub and Dirigible Web IDE
1. Apply changes from GitHub to Dirigible Web IDE
* Right-click on the project name, **Team** > **Pull** > **Ok**
2. Apply changes from Dirigible Web IDE to GitHub
* Right-click on the project name, **Team** > **Push**. Enter *Commit message*, *Username*, *Password* and *Email*. Click **Ok**
