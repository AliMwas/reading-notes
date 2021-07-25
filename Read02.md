# Remote repository (Git)

 ### Version Control 
 Version Control is a system that allows you to switch back and forth between different versions of a file or a group of files by tracking changes. Version control allows you to restore files or projects to previous versions, track and compare changes, and roll back to previous versions. With the help of a version control system (VCS), errors in files can be corrected quickly. 
 Types of version control :

 * Local version control 

 * Centralized version control 

 * Distributed version control 


 What is git? 

 Git is a DVCS, which stores data in a file system composed of snapshots. Every time you save a modified version of the project (called commit), Git creates a snapshot of the file and stores a reference to it. If the file hasn't changed, Git only stores a reference to the same version that has been stored.



![](https://miro.medium.com/max/910/1*Wjxx83j-qyiNvFBy1yOA1w.jpeg)


 ### Tracking and Staging a New File

**All Files**

Track all files in a repository by using the following command:

$ git add *
*After using these commands, files are tracked and staged for committing.

After adding a new file called EXAMPLE, you would see information regarding changes to be committed when using the git status command:

$ git status

On branch master

**Changes to be committed:**

  (use "git reset HEAD ..." to unstage)
new file: EXAMPLE
This information tells us that there are changes to be committed and that the file has been staged.


**Committing All Changes**
$ git commit -a
*This command commits a snapshot of all modifications to tracked files in the working directory.

Pushing Changes
Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.

