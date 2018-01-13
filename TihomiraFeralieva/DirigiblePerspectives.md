# Eclipse Dirigible Perspectives
=====================

![alt text](./workspace.png)

##### The Database perspective contains tools for inspection and manipulation of the artifacts within the underlying relational database. You have direct access to the default target schema assigned to your account in the cloud platform. From the Database Browser you can expand the schema item and see the list of all tables and views created either via the [models](http://www.dirigible.io/help/data_structures.html) or directly via SQL script.

## Database
### Possible actions
- *Open Definition* - presents the columns layout.
- *Show Content* - generates a select statement in the SQL Console and executes it.
- *Export Data* - exports the data from the table or view in **.dsv** format.
- *Delete* - - removes physically the table from the database.

Another tool in the **Database** perspective is a very generic but powerful one - [SQL Console](http://www.dirigible.io/help/sql_console.html).


## Debugging Perspective
- *Sessions* - contains all debug execution sessions.
- *Variables/Values* - contains the variables and their values, available in the current scope of execution.
- *File/Row/Source* - contains information about the position of the already set *Breakpoints*.

### Available Commands
- Step Into Step Into
- Step Over Step Over
- Continue Continue
- Skip All Breakpoints Skip all breakpoints

## Registry
The **Registry** is the entry point for searching and browsing for service end-points, as well as for monitoring and administration at runtime. Technically, it is a space within the *Repository* where all the [published](http://www.dirigible.io/help/publishing.html) artifacts are placed. To access the user interface, you can point to the runtime context; the default one is “dirigible”.
### End-Points
From the index page of the *Registry*, you can navigate to the corresponding sub-pages for browsing the raw content of the *Repository*, published [user interfaces](http://www.dirigible.io/help/web_content.html), [documentation](http://www.dirigible.io/help/wiki_content.html) of the applications, lookup of the [scripting services](http://www.dirigible.io/help/scripting_services.html) and the integration services endpoints.

### Monitoring Tools
The last phase of the applications lifecycle includes administration and monitoring.

Via the *Registry* interface, you can navigate to the monitoring tools including:
- Hit Count Statistics
- Response Time Statistics
- Memory Allocations
- Log Traces

The URIs on which you want to collect information about the request parameters have to be registered in the **Manage Access Locations** section.

## Repository Perspective
The **Repository** perspective gives access to the raw structure of the underlying *Repository* content. There you can inspect at low level the project and folder structure, as well as the artifacts content, in the read-only plain editor.
The *Resource History* view lists the most recent versions of the main artifact. It plays the role of a local file history. If the *Repository* component does not target the version control system by itself, you should rely on the [Git](http://www.dirigible.io/help/git.html) integration for secure resource management.
The history of the *Repository* is automatically cleared up after a certain period of time.

## Workspace Perspective
This is the place where you actually develop your dynamic Web applications. This perspective contains all views and editors that may help you in the overall implementation, from domain models via services to the user interface.
The main view opened by default in this perspective is the *Workspace Explorer*, a standard view on the projects in your [workspace](http://www.dirigible.io/help/workspace.html). It shows the folder structure and the contained resources.
There is a context menu assigned to the project node.
Through this context menu, you can create new artifacts:

- [Project](http://www.dirigible.io/help/dynamic_applications.html)
- [Data Structure](http://www.dirigible.io/help/data_structures.html)
- [Scripting Service](http://www.dirigible.io/help/scripting_services.html)
- [User Interface](http://www.dirigible.io/help/web_content.html)
- [Wiki Page](http://www.dirigible.io/help/wiki_content.html)
- [Integration Service](http://www.dirigible.io/help/integration_services.html)
- [Test Case](http://www.dirigible.io/help/test_cases.html)

or just regular ones:

- File
- Folder

When selecting an artifact, you can use the *Open* or *Open With* actions to load its content in the corresponding editor, for example, [Source Editor](http://www.dirigible.io/help/source_editor.html).
