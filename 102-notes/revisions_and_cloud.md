# Revisions and the Cloud

## Version Control 
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

### Three types of Version Control 
1. Local Version Control
- A Local VCS entails one database on your hard disk that stores changes to files.

2. Centralized Version Control
- This system entails a single server storing all changes and file versions, which can be accessed by various clients. 

3. Distributed Version Control
- DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

## What Is Git?
**Git** is a type of **Version Control**, or DVCS to be exact, that stores data in a file system made up of snapshots.

## Setting up a Git Repository 

### Importing
To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

1. Switch to the target project’s directory
Example:

```
$ cd test (cd = change directory)
```

2. Use the git init command

```
$ git init
```

### Cloning
You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

```
$ git clone https://github.com/test
```

To clone a repository into a directory with another name of your choosing, use the following command format:

```
$ git clone https://github.com/test mydirectory
```

## Remote Repositories 
In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.

[<== back](https://nickdeans.github.io/reading-notes/)
