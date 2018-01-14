# Makers for Entities

## Create project

1. Create new project with the option *New -> Project* in *Workspace Explorer*

2. Enter name of your project(*Example:Hotels*) and click *Next*

3. Select *Blank Application* and click *Finish*


## Create Data Structures

1. Right click on your project *New -> Data Structure*

2. Select *Relational Database Table* and choose *Next*

3. Add needed table properties

  - define an ID attribute as a Primery key
   
  - define latitude and longtitude properties for 
   the location of the markers

4. Name your Database(*Example: Hotels.table*) and click *Finish*

5. Right click on your project *-> Publish*

6. Create new *Data Structure* 

7. Select *DSV* template and click *Next*

8. Find your table and add it to the project

9. Edit the *.dsv* file by adding the locations with their coordinates

      1|Sevilla Hotel|37.3891|-5.9844
      
      2|King Louis Hotel|48.7980|2.3089
      
      3|Pleasant Hill Hotel|40.4645|-73.7944
      
      4|Bulgarian rose Hotel|42.6427|24.8063

10. Save the changes and publish your project once again.

## Create Scripting Service

1. *New -> Scripting Service* 

2. Select *CRUD Service on Table* and click *Next*

3. Find your table and add it to the project

4. Enter name of the service and click *Finish*

5. Locate your entity in the scripting service folder

## Generate User Interfaces for Entity Services

1. Right click *Generate -> User Interface for Entity Service*

2. Select *List and Manage Entity* and choose *Next*

3. Select the visible fields and edit the labels

 - *The labels will be part of your web page UI*
   
4. Set the page title and click *Next*

5. Name the file and click *Next*

6. Now you can manage the data, displayed in the Preview tab.

7. Create new *User Interface for Entity Service*

8. Choose *Markers for Entities* and click *Next*

9. Select the visible fields and edit the labels

10. Set the *Page title* and choose *Next*

11. Name the file and click *Finish*

12. Now you can notice that it is not working. To make it work
you need to add your application to the *.html* file and save it.

13. You can preview the result.







