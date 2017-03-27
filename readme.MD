## Ruby & Rails Starter Guide
*adapted from Rails Girls*

#### Creating the application

* Creating a directory for your project
<pre>mkdir projects</pre>
* Go into the directory
<pre>cd projects</pre>
* Create a new application
<pre>rails new railsgirls</pre>
* Go into the app folder
<pre>cd railsgirls</pre>
* Start Rails Server
<pre>rails server</pre>

#### Creating the Scaffold
*the scaffold will generate a starting point with CRUD*

* Creating a scaffold for your model
<pre>rails generate scaffold idea name:string description:text picture:string
</pre>
* Update database and restart server
<pre>rake db:migrate
rails server</pre>
