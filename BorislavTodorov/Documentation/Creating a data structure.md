<h1>Creating a data structure</h1>
<h1>Prerequisites</h1>
<p><a href="https://github.com/dirigiblelabs/curriculum/blob/master/BorislavTodorov/Documentation/Creating%20a%20project.md">Creating a project</a></p>
<h1>Context</h1>
<p>In the context of a cloud toolkit, the term Data Structures refers to the domain model of an application. The actual entities in a domain model directly correspond to the underlying database entities, that is, tables and views. There is no additional abstract layer between the code of your application and the actual model in the target storage.</p>
<h1>Procedure</h1>
<p>1. Navigate to the Workspace Explorer view in the Eclipse Dirigble Web IDE.</p>
<p>2. Right-click on your project and select <b>New</b>><b>Data Structure</b>.</p>
<p>3. A <b>Create Data Structure</b> window will appear.</p>
<p>4. To add column click on <b>Add</b>. You can choose:</p>
<p>&nbsp;&nbsp;&nbsp;4.1 What the name of column will be.</p>
<p>&nbsp;&nbsp;&nbsp;4.2 Its type: VARCHAR, CHAR, INTEGER, BIGINT, SMALLINT</p>
<p>&nbsp;&nbsp;&nbsp;4.3 Its length in characters.</p>
<p>&nbsp;&nbsp;&nbsp;4.4 Whether the column is NULL.</p>
<p>&nbsp;&nbsp;&nbsp;4.5 Whether it is a primary key or not.</p>
<p>&nbsp;&nbsp;&nbsp;4.6 Its default Values. Click <b>OK</b> afterwards.</p>
<p>5. After you are done adding columns click on <b>Next</b>.</p>
<p>6. You will be prompted to add a <b>File Name</b>, which will be the name of this table.</p>
<p>7. Click on <b>Finish</b> after you are done.</p>

<p>Warning:&nbsp;Table Model is a JSON formatted *.table descriptor. It represents the layout of the database table, which will be created during the activation process.</p>
