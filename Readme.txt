1.) git init-> Powers your folder to be managed by git and initialises a new empty repository.It also creates a .git folder that has all the relevant logic to manage versions of your project


2.) Working Area-> There can be a bunch of files that are not currently handled by git.It means that changes does or to be done in those files are not managed by git yet. A file which is in working area is considered to be not in staging area.When we do 'git status' and we see a bunch of 'untracked files' then these are actually called to be in the working area.

3.) Staging Area -> What all files are going to be part of the next next version that we will create This staging area is the place where git knows what changes will be done form the last version to the next version

4.) Repository Area -> This area actually contains the details of all you previous registered version. And the files in this area,git already manages them and knows their version history

5.) 'git add < file> -> moves files from wroking area to staging area

6.) git rm --cached -> moves file back from staging area to working area

7.) commit - Commit is a particular version of the project.It captures a snapshot of the project's staged changes and creates a version out of it.

8.) git commit -> registers staging changes to a commit

9.) git log -> list downs all the commits of the respository

10.) git retore -> It removes all files changes from the staging area to be committed.This can be useful,if we did some dirty piece of code and now no more want it.Instead of deleting every change line by line we can restore it or you can say retore last clean version of the file.

11.) git restore --staged -> it removes file from chnages from staging area to the working area. This only works if changes are in your staging area.

12.) Diff between git rm and git restore Ans: If you want to move the whole file back to the untracked state, then we do git rm otherwise if we just want the changes to be move in working area and staging area then we do git restore.
