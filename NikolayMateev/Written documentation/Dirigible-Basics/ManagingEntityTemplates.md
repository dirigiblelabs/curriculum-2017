# Create an Entity Management User Interface

Follow these steps in order to create a user interface to manage entities in your Dirigible application.

## Prerequisites

* Have a project created in the Dirigible Web IDE.
* Have at least one Data Structure created.
* Have at least one Scripting Service created.

## Context

Having data structures and scripting services is great. But there's no value in those things without generating some kind of user interface which allows the user to manipulate data in the database.

## Procedure

1. Navigate to the **Workspace Explorer** view in the Dirigble Web IDE where your project files reside.
2. Go to <b>*Project Name* > Scripting Services > *Project Name*</b>.
3. Right-click on a *.entity* file of your choice. A dropdown menu appears.
4. Select **Generate > User Entity for Entity Service**.
5. Select the *List and Manage Entity* template from the available list. Click **Next**.
6. Select all the fields you would like to be able to manage through the generated user interface. Choose **Next**.

  > You can additionally specify what label should be used for each field and also change the widget's data type.

7. Choose an appropriate file name for your user interface. Then choose **Next**.
8. Finally, enter a title for your page. Click **Finish**.

## Results

Your newly generated User Interface files are basic *.html* files, which will be stored at <b>*Project Name* > WebContent > *Project Name*</b> in the **Workspace Exlorer** view.

## Next steps

1. [Create Documentation for you application][1]


[1]: https://github.com/dirigiblelabs/curriculum/tree/master/NikolayMateev/WrittenDocumentation/Dirigible-Basics/ApplicationDocumentation.md
