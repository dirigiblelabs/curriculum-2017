## Dirigible - Mobile Applications

### Preparation
Before starting the procedure you should:
1. Launch Dirigible Web IDE
2. Download Tabris.js form Google Play or Apple Store

### Procedure
1. Make a new project in the Dirigible Web IDE
* Open the Dirigible Web IDE in the Workbench persepective
* Click **New** > **Project**, enter name for your project in *Enter project name*. Click **Next** and choose **Blank Application** > **Finish**
2. Create new data structure
* Right-click on the project name, **New** > **Data Structure**
* Select **Relatonal Database Tabel** > **Next**
3. Add column
* After **Next** from the previos step click **Add**. Eneter name in *Name*, type in *Type*, fill the other fields and click **OK**
4. Add more columns and proceed
* repeat step 3 with the other necessary properties for your table
* click **Next**. Enter name for your table in *File name* and click **Finish**
5. Create Scripting Service
* Right-click on the project name, **New** > **Scripting Service**
* Choose **JavaScrip Entry Service on Table** > **Next**. Select the name of your table and click **Next**. Enter name for the scripting service in *File name* (for example - something.js) and click **Finish**
6. Generate the UI of your entry service
* Unfold **ScriptingServices** 
* Unfold and package created in step 5
* Right-click on something.entry > **Generate** > **User Interface for Entry Services**. Select **Mobile Create Entries** and click **Next**
* Label all avaliable table properties accordingly and click **Next**. Enter name in *File name* and change format to .js Enter package name in *Package name* and click **Next**
* Enter title in **Page Title** and click **Finish**
* You can edin the newly created .js file
7. Generte UI for another entry service
* repeat step 6
8. Tests with Tabris.js mobile framework
* Unfold the packages created in steps 6 and 7
* Choose one of the created (for example - first) and select the package.json file in it. Click **Preview**. **Tabris.js** will open in a second.
* Write the name of the package you choosed after "/mobile/" and before "/package.json" in **Local Tabris.js script by URL**. The mobile application should work as you expected
