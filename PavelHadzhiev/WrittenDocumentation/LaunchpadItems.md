# Creating Launchpad Items with Eclipse Dirigible

In this tutorial you will learn how to create launchpad items for your Eclipse Dirigible projects.

## Prerequisites

- You must have Eclipse Dirigble deployed either on [SAP Cloud Platform][1] or [Locally on a Tomcat server][2].

## Creating Launchpad Items

1. In the Dirigible IDE, create a project by selecting *New > Project* in the Workspace Explorer.
2. Name your project.
3. Choose the Blank project template. Click *Finish*.
4. Expand your project from the workspace explorer.
5. Right-click on the *WebContent* folder and select *New > User Interface*.
6. Select *Launchpad*. Click *Next*.
7. Give your page a title. Click *Next*.
8. Select target location and file name. Choose *Finish*.
9. Repeat steps 5-8 but this time select *Launchpad Item* instead of *Launchpad*. 

To preview them, open the .html file of the Launchpad (named at step 8.).

## Customizing Launchpads

1. Go to the *ScriptingServices* folder.
2. Go to the folder named after the page title of your Launchpad. 
3. Go to the extension folder.
4. Edit the Service endpoint implementation files. 

You can change the properties (title, description, color and so on) of a Launchpad item by going to its .js file and chaning the value for its corresponding field.
Save any changes you have made by and preview them by opening the Launchpad .html file.

[1]: https://github.com/dirigiblelabs/curriculum/blob/master/PavelHadzhiev/WrittenDocumentation/SAPHCPDeployment.md
[2]: https://github.com/dirigiblelabs/curriculum/blob/master/PavelHadzhiev/WrittenDocumentation/LocalhostDeployment.md
