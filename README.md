# GIT HUB

#### What is Version Control?

- A software utility that tracks and manages changes to a
  filesystem.
- Also known as revision control or source control system
- It's a management of changes to documents, computer
  programs, large websites and other collection of
  information
- A software utility that tracks and manages changes to a
  filesystem.
- Also known as revision control or source control system
- It's a management of changes to documents, computer
  programs, large websites and other collection of
  information

# VCS Kind of Database

- vcs options include Git, Mercurial, SVN and preforce.
- You can think of a vcs as a kind of "database".
- It lets you save a snapshot of your complete project at any
  time you want
- When you later take a look at an older snapshot your vcs
  shows you exactly how it differed from the previous one

<img src="./images/img.jpg">

# VCS is independent

VCS is independent of kind of project / technology / framework you're working with

- it works just as well for and HTML website as it does for a design project or Iphone App
- it lets you work with any tool you like ; it does not care what kind of text editor , graphics program , file manager or other tool you use

# Why Use VCS: Collaboration

- without a VCS in place , your probably working together in a shared in a shared folder on the same set of files.
- And you have to coordinate with others so that they don't work on same file, it will be very difficult to manage.
- what a VCS, everybody on the team is able to work absolutely freely - on any file at any time.
- the VCS will later allow you to merge all the changes into a common version.

# Why use VCS: Storing Version

### Storing Versions (Properly)

- Saving a version of your project after making changes is an essential habit. But without a VCS, this becomes tedious and confusing very quickly
- How much do you save? Only the changed files of rhe complete project.
- How do you name these version? "my App_2013-11-34_v23"
- the most important question: How do you know what exactly is different in these versions?

### Why Use a version control System.

- Version control system acknowledgement that here is only one project
- Therefore ,there only the one version on your disk that you'r currently working on.
- Everything else - all the past versions and variants - are neatly packed up inside the VCS.
- When you need it , you can request any version at any time and you'll have snapshot of the complete project right at hand

### Why use VCS: Restoring Previous Version

- Restoring Previous Version;

* Being able to restore the previous version of a file whole project.
* if the changes you've made.![Learn Version Control with Git_ A step-by-step course for the complete beginner](https://user-

* lately prove to be garbage, you can simply undo them in a few clicks.

### Why use a version Control System.

- understanding What happened
  -Every time you save a new version of your project, your vsc require you to provide a short description of what was changed.

### Why Use a Version Control System.?

Backup.

- A side-effect of using a distributed VCS like Git is that it can act as a backup.
- every team member has a full- blown repository of that project on his disk.
- if central server break down (and your backup drives fail) all you need for recovery is one of your teammates local Git repository

### Different Types of VCS.

#### VSS VISUAL SOURCE SAFE

Microsoft version control program , Oriented towards small software development projects.
its problem is that any one work in file if he will lock but it is good but is not reliable in now area age.

### SVN (APACHE SUBVERSION)

- SVN IS THE ABBREVIATED FRO MOF APACHE SUBVERSION AND IS A POPULAR VERSION CONTROL SYSTEM.

- but is the problem is that every user has the partial copy of the code , if you will change the code you will send to the central and receive from the central
- it is centralized version control system.

### GIT

- git is a distributed version control system for tracking changes in source code during software development.
  It is designed for coordinate work among programmers, but it can be used to track changes in any set of files.

### CVCS

- centralized Version Control System

### DVCS

- Distributed version control system
  git is Distributed version control system
  when you working on Git you have a copy of code etc , you can upload your copy of code .
- you can push pull and update the code.
  <img src="/images/img1.png" alt="DVCS"/>

- if the central server gets crashed at any point of time, the lost data can easily recovered from any one of the contributors local repository.

# Installation and Basic workflow.

#### installing and basic setup of Git

[ https://git-scm.com/downloads](https://git-scm.com/downloads);

installation Guide Windows;
[https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

installation Guide Linux;
[https://git-scm.com/download/linux](https://git-scm.com/download/linux)

installation Guide Window;
[https://git-scm.com/download/win](https://git-scm.com/download/win)

### Configuring Git

A couple of very basic configurations should be made before you get started.
You should set your name and email address as well as enable coloring to pretty
up command outputs:

```js
 git config --global user.name “Hassanhabibtahir”
 git config --global user.email “Hassanhabib@thir.org”
 git config --global color.ui auto
```

Basics Operations in Git are.

- initialize
- Add
- Commit
- Pull
- Push

Advanced Operations in Git are

- Branching
- Merging
- Rebasing

### Repository

Think of a repository as a kind of database where you your VCS as a kind of database where your VCS stores all the versions and metadata that accumulate in the course of your project.
In Git the repository is just a simple hidden folder name ".git"

### Staging Area;

staging area is a virtual place that collects all the files you want to include in next comment.
In Git, simple making some changes does not mean they are automatically committed.
<img src="/images/staging.png" alt="staging area"/>

### Stating with an un versioned ,Local Project

- Open terminal and create directory on your machine
- C:\Users\myproject
- Go into directory in terminal
- initialize repository in this directory
- 1 git init
- 2 this will create .git hidden folder in your directory which will make your current folder, a git repository
- 3 create first.text
- 4 git status show you untracked files
- 5 Add these files to your staging area.
  - tow way to add files to staging area
  * git add first.text
  * git add .
