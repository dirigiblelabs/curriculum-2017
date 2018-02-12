# **Create a Data Structures**

Folow these steps in order to create a simple data structure for your Eclipse Dirigible application.

### Procedure
**1. Creating new project.**
1. Right-click on **Workspace Explorer** and create new project, folowing the path **New -> Project**.
2. Enter name for your projecte in **Enter project name** field.
3. Select the **Blank application** template and choose **Finish**.

**2. Create new data structure.**
1. Right-click on the project and create new data structure, folowing the path **New -> Data Structure**.
2. Create a **Rational Database Table**.
3. To add all necessary properties,choose **Add**.
4. Define **Primary key**.
5. Enter name for your file in **File Name** field.
> The new table definitions will be in JSON format.

**3.** Right-click on your project and choose **Publish**.

**4. Open the database view**.
1. Click on **Other...**
2. Now you should be seeing **Open Perspective** window.
3. Choose **Database**.

**5.**	Type the **SELECT * FROM...** command in the **SQL Console** window. No result will show up because the database is empty. Another data structure has to be added.

**6. Create DSV template**.
1. Right-click on the project and create new data structure, folowing the path **New -> Data Structure**.
2. Select the **Delimiter Separated Values Sample Data** and choose **Next**.
3. Find your table and add it to your project by choosing **Add**.

**7.** Publish your project once again.

**8.** Open the database view.

**9.** Try again the **SELECT * FROM...** command in the **SQL Console** window.

**This time the query shoud be successful!**

**Next step**
1. [**Create Scripting Services**](https://github.com/dirigiblelabs/curriculum/tree/master/KalinaGeorgieva/ScriptingServices.md).
2. [**Create User Interfaces**](https://github.com/dirigiblelabs/curriculum/tree/master/KalinaGeorgieva/UserInterfaces.md).
