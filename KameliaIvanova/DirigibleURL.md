# **Background:**

Dirigible project came out of an internal SAP initiative to address the extension and adaptation use-cases related to SOA and Enterprise Services. On one hand in this project were implied the lessons learned from the standard tools and approaches so far and on the other hand, there were added features aligned with the most recent technologies and architectural patterns related to Web 2.0 and HTML5. This made it complete enough to be used as the only tool and environment needed for building and running on-demand applications in the cloud.

# **Scope:** 

Full development lifecycle of on-demand applications leveraging In-System Programming Model and Rapid Application Development techniques:

Database modeling and management;
RESTful services authoring using various dynamic languages;
User interface – pattern-based generation as well as custom forms and reports;
Injected services;
Role based security;
External services integration;
Testing;
Debugging;
Documentation;
Extensions management;
Operations and monitoring;

# **Architecture**

Dirigible architecture follows the well proven principles of simplicity and scalability in the classical service-oriented architecture.

The design-time and the runtime components are well separated. They interact with each other through a dedicated repository where the only linking point is the content itself. At design-time programmers and designers use the Web-based integrated development environment based on the Eclipse Remote Application Platform (RAP). Leveraging this robust and powerful framework the tooling can be easily enhanced using well-known APIs and concepts - SWT, JFaces, OSGi, extension points, etc.

The Repository is the container of the project artifacts. It is a generic file-system like content repository built on a relation database (via JDBC).

On top are the Dirigible's containers for services execution depending on the scripting language and purpose - Rhino, jRuby, Groovy, Camel, CXF, etc.

The runtime can scale independently by the design time part, and even can be deployed without design time at all (for productive landscapes).

Depending on the target cloud platform, Dirigible can be integrated to use the services provided by the underlying platform.


# **Url**

Url object is used to encode/decode text in the application/x-www-form-urlencoded
MIME format.

#**Version 3.x**
Module: utils/v3/url
Alias: utils/url
Definition: https://github.com/eclipse/dirigible/issues/25
Source: /utils/v3/url.js
Facade: UrlFacade
Status: alpha

# **Basic Usage**

    var url = require('utils/v3/url');
    var response = require('http/v3/response');

    response.println(url.encode('<![CDATA[<meta http-equiv="refresh" content="0;url=javascript:document.vulnerable=true;">]]>'));
    response.println(url.decode('%3C%21%5BCDATA%5B%3Cmeta+http-equiv%3D%22refresh%22+content%3D%220%3Burl%3Djavascript%3Adocument.vulnerable%3Dtrue%3B%22%3E%5D%5D%3E'));

    response.flush();
    response.close();


