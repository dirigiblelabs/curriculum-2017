# Create an Entity Management User Interface

## Why do you need a user interface to manage entities?

In order to let the user manipulate data in your database, you will need a user interface to manage entities like data structures and scripting services.

## Requirements

1. Have a project created in the Dirigible Web IDE.
2. Have at least one Data Structure created.
3. Have at least one Scripting Service created.

## How to create an entity management user interface?

1.  Navigate to the **Workspace Explorer** view in the Dirigible Web IDE where your project is.
2. Go to **Project Name > Scripting Services > Project Name**.
3. Right-click on a _.entity_ file of your choice. A dropdown menu appears.
4. Select **Generate > User Entity for Entity Service**.
5. Select the _List and Manage Entity_  template from template types from the list. Click **Next**.
6. Select every field you would like to be able to manage through the generated user interface. Click **Next**.

  > NOTE: You can also specify what label can be used for every field and change the widget's data type.

7. Write a file name for your user interface. Then choose **Next**.
8. After that, enter a title for your page. Click **Finish**.

## Where to find your entity management user interface?

Generated User Interface files are basic _.html_ files, which will be at **Project Name > WebContent > Project Name** in the **Workspace Explorer** view.
