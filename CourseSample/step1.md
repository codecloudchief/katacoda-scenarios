In Linux operating system you should know the directory where you are and as what user you have logged in to the system.

These two determines what level of access you have been provided, for example whether you are an adminstritative user or normal user. 

Administrative privileges are given through a utility called as sudo

## Current working direcoty

Know the directory with the command `pwd`{{execute}}

Within the root of a repository, a course has been created called `uilayouts`. The contents of the course have been defined as `katacoda-scenario-examples/uilayouts-pathway.json`{{open}}.

Within the JSON file, the courses element defines each scenario. For example:

<pre class="file">
{
    "course_id": "uilayout-terminal",
    "title": "Scenario with Terminal UI",
    "description": "Katacoda Scenario Example"
},
</pre>

The **course_id** is the scenario name directory within the course directory. For example `ls katacoda-scenario-examples/uilayouts/uilayout-terminal`{{execute}}. The **title** and **description** are shown on the course page.