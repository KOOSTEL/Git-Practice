<h1>Git Self Tutorial</h1>

<h6>PREAMBLE<p>This is made only for myself to study Git and Markdown, so do not use it as a guide, as it was created by someone with no experience in Git.<h6>

### Starting Git

***

- **mkdir** *foldername* <pre>create a git directory (folder) named _foldername_ </pre>
after this, you shoud `cd` to this directory - this is where the .git folder (hidden by default) <ins>will</ins> be placed

***

- **git init** <pre>Initialize a Git repository in the current path </pre>
This also creates a hidden .git directory. Use `ls -a` to view all files


***

- **git config --global user.name "Your Name"** 
- **git config --global user.email your<span>@</span>email.com**<pre>Set your global Git username and email</pre> use `git config user.name` and `git config user.email` to get info about name and email

***

### Workflow and Snapshots

***

- **git add file.extension** <pre>Add a file to the staging area before committing</pre>
`git add .` will add all files in the repository <p>
Deleting files: after deleting files in the repo we must use `add` _`deleted_file`_ and this file we be removed from a staging area (refresh status)

***

- **git status** <pre>after any file modifications we can check the status of the repo and track files </pre>
Note that after modifying files, you must run `git add` _`modified_file`_ to refresh the status!

***

- **git commit -m "message"** <pre>commit to permanently store the snapshot in the repo </pre>
`git commit -am` for adding all modified/deleted tracked files and commit them with this message

***

### Pushing Code to GitHub

***

after `git add` and `git commit` we can push (upload) the code to a remote repository on GitHub (first create one in GitHub)

- **git remote add origin *repo-url*** <pre>This command links your local Git repository to a remote repository e.g. on GitHub </pre>
`git remote remove origin` Unlinks the remote repository

***

- **git push origin master** or **git push origin main**<pre>pushes files to the GitHub repo</pre>

***

### Other Modifications on Files

***

- **git mv** _**old_filename**_ _**new_filename**_ <pre>rename file</pre>

***

### Cloning Branching Pulling

TODO 

### Deleting commits etc.
