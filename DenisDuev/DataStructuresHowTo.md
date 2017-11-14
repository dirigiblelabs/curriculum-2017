#1.	Analyze the video tutorial (5 min): a. Who are its target viewers? What is their level of competence? What are their main goals? #
	- The target viewers are developers
	- they are at the begging level of competence in Dirigible
	- To learn how to work with data structures, and see an example
#2.	Imagine this video is screen capture sent to you by your product owner. Create a written version of this tutorial (15 min). 
Prerequisites: Set up Dirigible and open Dirigible workspace#
	1.	In the **Workspace Explorer** pane -> right click -> new -> Project
	2.	In the newly opened window go to **Enter project name** -> name your project -> click next
	3.	Then you have to choose **Project Template** -> click on **Blank Application** -> choose **finish** button
	4.	Now you can see your project appear in **Workspace Explorer** -> right click on the project -> choose **New** -> choose **Data Structure**
	5.	A new screen appears called **Create Data Structure** -> from **Available Templates** choose **Relational Database Table** – click **next**
	6.	Now you have to add all necessary table properties. -> click on button **Add**
	7.	A new window appears called **Add Column**:
		a)	enter “ID” in **Name** filed (define an ID attribute as a primary key)
		b)	b) choose **Type** INTEGER
		c)	check **Not Null?** Checkbox
		d)	check **Primary Key?** Checkbox
		e)	click **ok**
	8.	Repeat **step 7** and add more columns (for example FIRST_NAME, LAST_NAME, AVARAGE_GRADE, BIRTH_DATE – please note the correct data types for this fields)
	9.	After entering all field -> click **next**
	10.	In the next screen edit the **File Name** (students.table) -> click **finish**
	11.	The table opens automatically and it is in JSON format
	12.	Now publish your project -> in **Project Explorer** -> right click on project name -> **Publish**
	13.	Open the database view -> in the upper corner choose other -> in the newly opened windows choose **Database perspective** -> click **ok**
	14.	An SQL console appear at the bottom of the screen -> write a query -> enter **SELECT * FROM STUDENTS** -> click button **Query**
	15.	No result showed up -> we have to add another **Data Structure** -> repeat **step 4** and add new Data Structure -> choose **Delimiter Separated Values Sample Data** -> click **next**
	16.	From all available table find your table -> mark it -> click **next** to add it to your project -> click **finish**
	17.	Repeat **step 12** and publish your project
	18.	Repeat **steps 13 and 14** -> now the entries appear