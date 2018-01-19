# **Create a Data Structures**

Follow these steps in order to create a simple data structure for your Eclipse Dirigible application.

### Procedure
**1. Crating new project**
1. Right-click in Workspace Explorer and create your **new project**.
2. Name your project.
3. Select the **blank application template** and choose Finish.

**2. Create a new data structure**
1. Right-click on the project and create **new data structure**.
2. Create a **rational database table**
3. Now **add** all necessary properties.
4. Define an **ID attribute** as a primary key.
5.	**Name** your table.
> The new table definitions will be in JSON format.

**3.** Right-click on your project -> **Publish.**

**4. Open the database view**
1. Click the button **Other...**
2. Now you see **Open Perspective** window.
3. Choose **Database**

**5.**	Type the **SELECT * FROM...** command in the **SQL Console** window. No result will show up because the database is empty. Another **data structure** has to be added.

**6. Create DSV template**
1. Right-click on the project and create **new data structure**.
2. Select the **Delimiter Separated Values Sample Data** and choose Next.
3. Find your table and **add** it to your project.

**7. Publish** your project once again.

**8.** Open the **database view**.

**9.** Try again the **SELECT * FROM...** command in the SQL Console window.

**This time the query is successful!**

**Next step**
1. [**Create _Scripting Services_**](https://github.com/dirigiblelabs/curriculum/tree/master/KalinaGeorgieva/ScriptingServices.md).
2. [**Create _User Interfaces_**](https://github.com/dirigiblelabs/curriculum/tree/master/KalinaGeorgieva/UserInterfaces.md).
