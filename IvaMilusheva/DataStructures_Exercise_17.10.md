# Creating Data Structures

*Note:	**Target viewers** – everyone, with different level of competence, their main goals are to make their first data structure in Dirigible*

## 1.	Create new project

a.	*Right click* on the *Workspace Explorer -> New -> Project* 

![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/new-project-2.PNG "newproject")

b.	Enter name of your project 

![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/enter-nameoftheproject-3.PNG "nameoftheproject")

c.	Choose a template (*Blank Application*)  

![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/choose-blankapplication-4.PNG "blankapplication")


## 2.	Create Data Structure

a.	*Right click* on your project *-> New -> Data Structure* (you can see your project in your workspace) 
 
 ![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/new-dataStructure-5.PNG "newdatastr")
 
b.	Choose a *Relational Database Table*

![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/relation-database-table-6.PNG "relationalDBTable")

c.	Add the columns you want (which are representing variables) with name, type, length, default value, do contain primary key or don’t and is it null or not. 
 
 ![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/addCol.PNG "columns")
 
d.	Choose *Next* and make a file name which is similar to table name(*Example: STUDENTS(tablename) -> students.table(filename)*)

e.	This current file is in JSON format and represents your database

f.	*Right click* on your project *-> Publish*
 
 ![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/publishJson.PNG "publishJSON")
 
## 3.	Manipulate with your database

a.	*Right click* on your project *-> New -> Data Structure*

b.	Choose *Delimiter Separated Values Sample Data*
 
 ![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/Delimitersep___.PNG "delimeterseparated")
 
c.	Click *Next* and find your already created database.
  
  ![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/chooseYourDB.png "findDB")
  
d.	*Right click* on your project *-> Publish*

e.	On the top you can see *others…* choose *Database*
 
![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/others.png "others")

![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/Other_DB.PNG "DB")

f.	Now you have a *SQL Console* to manipulate your first database
 
## 4.	Test

a.	Try the database with the command **SELECT * FROM STUDENTS**

   •	*Pay attention that STUDENTS is just an example of the name of your database*

b.	Now you probably see every column you added to your database at the beginning
 
 ![image](https://github.com/dirigiblelabs/curriculum/blob/master/IvaMilusheva/Images/SELEct.PNG "exmapleofsqlcommands")

## Задача 

## 1. **cloud computing** 

Това е вид информационна технология, която представлява мрежа от компютри, използвани за споделени ресурси, софтуер или информация. Споделянето на тази информация и използването на тази технология става чрез интернет. 

### First definition
	Това е термин от областта на информационните технологии, означаващ използването на споделени ресурси, софтуер и информация, като предоставяни на компютри и други устройства по мрежа (чрез Интернет).


### Second definition
	"Облачните услуги" се доставят чрез Интернет. Те са технологични услуги произведени от мрежа от компютри (компютри свързани в клъстър), а не от отделни, самостоятелни физически компютърни инстанции. Тези компютри обединяват изчислителните си ресурси в единна система (Компютърен облак). Компютърният облак (на английски език "Compute Cloud" или "Cloud Computing") има два основни компонента - "Сървъри за изчислителни процеси" (Processing Nodes) и "Масив/Мрежа за съхранение на данни" (Storage Area Network).
