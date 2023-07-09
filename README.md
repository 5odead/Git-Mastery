# Git-Mastery
## What is Git

Git is a distributed revision control and source code management system with an emphasis on speed. Git was initially designed and developed by Linus Torvalds for Linux kernel development. **Version Control System (VCS)** is software that helps software developers to work together and maintain a complete history of their work.

Functions of a VCS −

- Allows developers to work simultaneously.
- Does not allow overwriting each other’s changes.
- Maintains a history of every version.

Types of VCS −

- Centralized version control system (CVCS).
A centralized version control system (CVCS) uses a central server to store all files and enables team collaboration. But the major drawback of CVCS is its single point of failure, i.e., failure of the central server. Unfortunately, if the central server goes down for an hour, then during that hour, no one can collaborate at all. And even in the worst case, if the disk of the central server gets corrupted and proper backup has not been taken, then you will lose the entire history of the project.
- Distributed/Decentralized version control system (DVCS).
DVCS clients not only check out the latest snapshot of the directory but they also fully mirror the repository. If the server goes down, then the repository from any client can be copied back to the server to restore it. Every checkout is a full backup of the repository.

## Why Git?

- **Free and open source**
Git is released under GPL’s open-source license. It is available freely over the Internet.
- ****Fast and small****
Git does not rely on the central server; that is why, there is no need to interact with the remote server for every operation. The core part of Git is written in C, which avoids runtime overheads associated with other high-level languages. Though Git mirrors the entire repository, the size of the data on the client side is small.
- ****No need for powerful hardware****
- ****Security****

<h2> Git Terminologies </h2>

Working Directory <br>
Inside Project Folder where we actually work, we keep all files and perform many operations like addition, update, and deletion of files.

Staging Area <br>
The staging area is like a rough draft space. Files that are going to be a part of the next commit
go into the staging area

Stage <br>
To stage a file is simply to prepare it finely for a commit.

Commit <br>
To commit is to save all currently staged changes of the project. Commits are created to capture the current state of a project.

Repository <br>
A directory or storage space where your projects can live. Sometimes GitHub users shorten this to “repo.” It can be local to a folder on your computer, or it can be a storage space on GitHub or another online host.

![git local operations](https://github.com/5odead/Git-Mastery/assets/71369187/676ce373-7413-4b06-aa1e-1de1cbc91cd4)

