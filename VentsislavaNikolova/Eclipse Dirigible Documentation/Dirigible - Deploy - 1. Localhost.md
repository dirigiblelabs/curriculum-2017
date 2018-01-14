# Dirigible - Deploy - 1. Localhost

## Setup on Tomcat

Start with the Home page of ***Eclipse Dirigible***. Select **Getting Started**.
![Image of Home page](https://github.com/dirigiblelabs/curriculum/blob/master/VentsislavaNikolova/Eclipse%20Dirigible%20Documentation/Pictures/Getting%20started.png)

On ***On Tomcat Server*** select **Set It Up**.

![Image of Tomcat](https://github.com/dirigiblelabs/curriculum/blob/master/VentsislavaNikolova/Eclipse%20Dirigible%20Documentation/Pictures/SetItUp.png)

From the newly opened window (**Setup on Tomcat**) select **Tomcat** (*link to Tomcat web page*).

![Tomcat](https://github.com/dirigiblelabs/curriculum/blob/master/VentsislavaNikolova/Eclipse%20Dirigible%20Documentation/Pictures/Tomcat.png)

To download select From the **Download** side menu ***Tomcat 8***. Select the version for you computer. Download and install the software.

![Download](https://github.com/dirigiblelabs/curriculum/blob/master/VentsislavaNikolova/Eclipse%20Dirigible%20Documentation/Pictures/Download.png)

***Next steps***

Return to **Setup on Tomcat** page, where downloaded Tomcat.
1. Download **Dirigible** from the given link.
2. Select rhe link in **Releases** section.
3. Select ***M20161014-1717*** from the section **Latest Downloads**.
4. To download the file select ***tomcat/allinone/ROOT.war*** from the first row in **Tomcat** section.
5. Copy the downloaded file from the place you saved it.
6. Find where yoy install Tomcat and go to ***Apache Softwate Foundation -> Tomcat -> webapps***
7. Delete files in webapps folder. You may have to provide Administrator premission for this.
8. Paste the file you downloaded and copied earlier.
9. Go to ***Apache Softwate Foundation -> Tomcat -> conf***.
10. On **tomcat-users.xml** file select *right-click->Edit with Notepad++*.
11. From **Setup on Tomcat** page copy the fowolin lines

![](https://github.com/dirigiblelabs/curriculum/blob/master/VentsislavaNikolova/Eclipse%20Dirigible%20Documentation/Pictures/copy.png)

12. Replace the fowollin lines in the opened file in Notepad++ with the copied ones.

![](https://github.com/dirigiblelabs/curriculum/blob/master/VentsislavaNikolova/Eclipse%20Dirigible%20Documentation/Pictures/replace.png)

13. Save the changes.
14. Select **Stop Service** with right-click on *Apache Tomcat* icon on Taskbar.
15. Select **Start Service** with right-click on *Apache Tomcat* icon on Taskbar.
16. In address bar write *http://localhost:8080*.
17. Enter your username and password and you're ready to go. 

