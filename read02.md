# Version Control  
## Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.
- Local Version Control  : Many years ago, programmers created Local Version Control systems. A Local VCS entails one database on your hard disk that stores changes to files.
- Centralized Version Control :The need for collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System (CVCS). This system entails a single server storing all changes and file versions, which can be accessed by various clients 
- Distributed Version Control : A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions.
## what is Git? 
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it.
- Snapshots
- Local Operations
- Tracking Changes
- Loss of Data
- States
## Files in Git can reside in three main states:
- committed.
- modified .
- staged.
![git states](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)
## Git can be installed in three ways:

1.Install as a package  
2.Install via another installer  
3.Download and compile the source code.  
Git Website

You can also download Git by visiting this link and following the posted directions:(http://git-scm.com/download/mac)
## Default Text Editor
Without configuration of a default text editor, Git will use the system’s default editor–most likely Vim. To configure a different text editor, such as Emacs, type the following into your Terminal or Command Line:

>$ git config --global core.editor emacs

## Check Settings
>$ git config --list

user.name=Jane Smith

user.email=example@email.com

color.status=auto

color.branch=auto

color.interactive=auto

...
# Workflow
Local Repository Structure
The local Git repository has three components:

1.Working Directory: The actual files reside here.  
2.Index: The area used for staging  
3.Head: Points to the most recent commit  
![Workflow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)


