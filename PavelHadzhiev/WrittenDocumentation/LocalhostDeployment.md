# Deploying Eclipse Dirigible™ on localhost

In this tutorial you will learn how to deploy Eclipse Dirigible locally. For the purpose you will set up a Tomcat server.

## Setting up Tomcat 8

Complete the following steps to configure Tomcat 8 on your computer.

1. Download and install [Tomcat 8][1]. There are no specific steps required during installation.
2. Download the latest release from the [Dirigible][2] website.
3. Go to the Apache Tomcat installation folder. Open the webapps folder and delete its contents.
4. Copy the ROOT.war file from 2. and paste it in the webapps folder.
5. Wait for the ROOT folder to appear.
6. Return to the installation folder. Go to the conf folder and open the tomcat-users.xml file for editing.
7. Replace the file contents with the fragment from Step 2. in the [Tomcat Setup][7] page.
8. Reboot Apache Tomcat to apply the changes.

## Running Eclipse Dirigible WEB IDE

Now that your Tomcat is configured, complete the following steps to start developing with Dirigible;

1. Open your preferable browser and go to http://localhost:8080.
2. Enter your Dirigible username and password.
3. Go to Develop -> Web IDE. Your Tomcat configuration is completed.

[1]: https://tomcat.apache.org/download-80.cgi/
[2]: http://download.eclipse.org/dirigible/
[7]: http://www.dirigible.io/help/setup_tomcat.html
