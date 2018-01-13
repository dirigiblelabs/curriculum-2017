# Install Dirigible on SAP HANA Cloud Platform
=====================

##### Dirigible is a cloud development toolkit providing both development tools and runtime environment. It supports full development life-cycle of on-demand applications by leveraging in-system programming models and rapid application development techniques.

### Prerequisites 
- Trial account at SAP HANA Cloud – [how to Sign Up for developer account (free)](https://help.hana.ondemand.com/help/frameset.htm?65d74d39cb3a4bf8910cd36ec54d2b99.html)

### Download Dirigible war
1. Go to [http://download.eclipse.org/dirigible/](http://download.eclipse.org/dirigible/) latest release
1. In the section HANA Cloud Platform download “All-in-one WAR” (~53MB) [http://download.eclipse.org/dirigible/drops/R-2.1-201510071717/sap/allinone/dirigible.war](http://download.eclipse.org/dirigible/drops/R-2.1-201510071717/sap/allinone/dirigible.war)
1. Save the war file locally

### Deploy and start your instance of the Dirigible in the cloud
#### Procedure

1. Go to your SAP HANA Cloud Cockpit on trial landscape: https://account.hanatrial.ondemand.com. Ok it could be also paid one http://hana.ondemand.com . The trial has all the functionality you need for educational purpose.
1. Log on with your HCP credentials (if you did not already do it)
1. Go to Java Application menu and click Deploy. (if you have already deployed an application your screen might be slightly different, just click Deploy application)
1. Upload dirigible war, chose Runtime name: ”Java Web”, and click deploy.
1. After the dirigible.war is deployed (it may take 1 minute), then start it.
Just press OK. Another way to start the application is to press the start button in the Application menu
1. When the application is started, click on the application – this will open the application dashboard. Now you can see some more application details
1. Assign yourself the Operator and Developer role using the Roles menu for this application
For more details about assigning roles you can follow: [Managing Roles](https://help.hana.ondemand.com/help/frameset.htm?db8175b9d976101484e6fa303b108acd.html)
1. Access the application URL in the Overview tab:
Use your SAP HANA account credentials to access the application. And good luck with your projects in Dirigible.