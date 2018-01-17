# Deploying Eclipse Dirigible™ on SAP Cloud Platform Cockpit

In this tutorial you will learn how to start developing with Eclipse Dirigble, deployed on the SAP Cloud Platform.

1.[Deploy it.](#deploying-eclipse-dirigible)
2.[Configure it.](#configuring-eclipse-dirigble)
3.[Start using it.](#starting-eclipse-dirigble)

## Prerequisites

- You must have an account in the SAP Cloud Platform. To create a free account go to https://account.hanatrial.ondemand.com/ and click *Register*.

## Deploying Eclipse Dirigble

1. Download the latest release from the [Dirigible][1] website.
2. Go to the [SAP HANA Cloud Platform Cockpit][2] and sign into your account.
3. Click your account ID to enter your personal developer account.
4. Go to *Applications -> Java Applications -> Deploy Application*.
5. At *WAR File Location*, click *Browse* and navigate to the *ROOT.war* file you downloaded in step 1.
6. Choose an appropriate Application Name (for example - *dirigible*).
7. Click the dropdown list at *Runtime Name* and choose *Java Web Tomcat 8*.
8. Click *Deploy* and wait for the deployment process to finish.
9. Click *Start* and wait for the application to start.

## Configuring Eclipse Dirigble

After [deploying](#deploying-eclipse-dirigible) the Dirigible application, you need to complete these configuration steps.

1. In your free developer account, go to *Applications -> Java Applications* and click on the Dirigible application.
2. Go to *Security -> Roles*.
3. Click on the *Operator* role and click the *Assign* button of the *Individual Users* table.
4. Enter your account ID. To see your account ID, click on the profile icon in the top right corner.
5. Repeat steps 3. and 4. for the *Developer* role.

## Starting Eclipse Dirigble

Once you have [deployed](#deploying-eclipse-dirigible) and [configured](#configuring-eclipse-dirigble) the Dirigible application you can start developing with it by following these steps.

1. In your free developer account, go to Applications -> Java Applications and click on the Dirigible application.
2. Click on the link under Application URLs.
3. Go to *Develop -> Web IDE*.

You can now start developing. For any further help, refer to the [Official Documentation][3].

[1]: http://download.eclipse.org/dirigible/
[2]: https://account.hanatrial.ondemand.com/
[3]: http://www.dirigible.io/help/
