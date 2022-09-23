# Git

## What is Git?

Git is a system of Snapshopts, Local Operations, Traking changes, Loss of Data and States .

Firstly Git USes to things in order to manage files and collaboration with a team of developers.

## CVS

The first system is called *CVCS* (Centralized Version Control System). This system is invovles a single sever storing all changes and file versions, which can allow other clinents access to them. This smoothed the collaboration process which allowed programmer to ahve more knowledge of team members' activities woth ceratin files and gave admins. more control over divvying up revision privileges.

## DVCS

The second system is call *DVCS* (Distributed Version Control systems). This system addresses the major vulnerability of the CVS: the sever as a single point of failure. If CVS crashes, collaborators can't work with each other on a file or save changes and new versions. Also if a corruption of cecentral database’s hard disk, without backing it up, all work will be lost. So DVCS allows people to create mirrored repositories. This mirror is essentially a data backups and DVCS can mirror repos. multiple times. This makes it so programmers are able to complete projects, which allows for use of various simultaneous workflows.

### Snapshots

Git is a DVCS that stores data in a file system made up of snapshot. Each time you save a changed version of your project, called commit, Git creates a snapshot of the file and stores a reference to it. If the file has not been altered, Git only stores a reference to the already-stored identical version of it.

### Local Operations 

Git mostly relies on local operation because most neccessary info. can be found in local resources. This allow for process conveniency because a project's history is on the local disk. This eliminates the the need to get history info. from a server so you can keep working when not online.

### Tracking Changes 

Git basically detect file corruption or loss of info. in tranit since every single change applied to any file or directory is tracked by Git.

### Loss of Data

Git is set up to minimize the possibility of the corruption of files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is commited to be lost.

### States

Files in Git can be in three main states: committed, modified, and staged.

- Commited means the data is securely stored in a local database

- Modified means the file has been changed but not commited

- Staged means you flagged a file's changed version to be commited in the next snapshot.

Today we learned how to connect VSCode to Github through our terminal. First we have to make a folder.

- ls

- cd projects

- ls

- cd courses

- mkdir 102

 Now we can start three step process.

- Cloning

- Commiting

- Push

Cloning is a simple process where you take the link of your repository in Github by typing the followingin your terminal.

- ls

- cd projects

- cd courses

- ls

- cd 102

Once you have made it to the folder you created at the beginning type.

git clone "github link to repository"

**Never** change anything in Github after you do the step above.

Moving on to commiting. Commiting basically updates anything you do in VSCode to Github. Type the code below in your terminal.

- git status (this allow you to see if anything has changed)

- git commit -m "this is a message you type in the terminal to tell what you've changed in detail" (avoid punuation in the messag).

- git commit -a (this applies all change to your code in GitHub)

-git push origin main(this relays all changes to Github)

[Back to home page](../README.md)