<h1>Git Self Tutorial</h1>

### Starting Git
***
- <span style="color:violet">**mkdir Test**</span> <pre>create a git directory (folder) named Test </pre>
after this you shoud cd to this directory

***

- <span style="color:violet">**git init**</span> <pre>Initialize git repo in "PC PATH" </pre>
it also creates hidden directory .git, use <span style="color:green">**ls -a**</span> to view all files

***

### Workflow and Snapshots

***
- <span style="color:violet">**git add file.extension**</span> <pre>add a file in the staging area before commiting. Commiting can also be done without <span style="color:violet">add
git add .</span> will add all files in repo</pre>
<span style="color:green">Deleting files:</span> after deleting files in the repo we can use <span style="color:green">add deleted_file</span> and this file we be removed from a staging area

- <span style="color:violet">**git status**</span> <pre>after any file modifications we can check the status of the repo ad track files </pre>
Note that after any modification of files after creation we need to use <span style="color:green">git add modified_file</span> to refresh the status!

- <span style="color:violet">**git commit -m "message"**</span> <pre>commit to permanently store the snapshot in the repo</pre>