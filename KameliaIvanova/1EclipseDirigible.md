# **Eclipse Dirigible**


## **Background**

Dirigible project came out of an internal SAP initiative to address the extension and adaptation use-cases related to SOA and Enterprise Services. On one hand in this project were implied the lessons learned from the standard tools and approaches so far and on the other hand, there were added features aligned with the most recent technologies and architectural patterns related to Web 2.0 and HTML5. This made it complete enough to be used as the only tool and environment needed for building and running on-demand applications in the cloud.

## **Scope** 

Full development lifecycle of on-demand applications leveraging In-System Programming Model and Rapid Application Development techniques:

* Database modeling and management;
* RESTful services authoring using various dynamic languages;
* User interface – pattern-based generation as well as custom forms and reports;
* Injected services;
* Role based security;
* External services integration;
* Testing;
* Debugging;
* Documentation;
* Extensions management;
* Operations and monitoring;

## **Overview**

Dirigible is an open source project that provides Integrated Development Environment as a Service (IDEaaS) as well as runtime containers integration for the running applications. The environment itself runs directly in browser and therefore does not require additional downloads and installations. It packs all the needed components, which makes it self-contained and well integrated software bundle that can be deployed on any Java based Web Server.

Target applications built with Dirigible are atomic yet self-contained cloud based modules that cover end-to-end vertical scenarios. These applications comply with the Dynamic Applications concepts and structure.


## **Architecture**

Dirigible architecture follows the well proven principles of simplicity and scalability in the classical service-oriented architecture.

The design-time and the runtime components are well separated. They interact with each other through a dedicated repository where the only linking point is the content itself. At design-time programmers and designers use the Web-based integrated development environment based on the Eclipse Remote Application Platform (RAP). Leveraging this robust and powerful framework the tooling can be easily enhanced using well-known APIs and concepts - SWT, JFaces, OSGi, extension points, etc.

The Repository is the container of the project artifacts. It is a generic file-system like content repository built on a relation database (via JDBC).

On top are the Dirigible's containers for services execution depending on the scripting language and purpose - Rhino, jRuby, Groovy, Camel, CXF, etc.

The runtime can scale independently by the design time part, and even can be deployed without design time at all (for productive landscapes).

Depending on the target cloud platform, Dirigible can be integrated to use the services provided by the underlying platform.

![architecture](http://www.dirigible.io/help/images/architecture.png)


### **Other Tutorials** 
* [Creating a New Project ](2CreatingNewProject.md)

* [Encoding And Decoding URLs](3EncodingAndDecodingURLs.md)
