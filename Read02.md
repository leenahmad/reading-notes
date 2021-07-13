# Git 

### what is the Git?

Git  is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows (thousands of parallel branches running on different systems).

Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development. Since 2005, Junio Hamano has been the core maintainer. As with most other distributed version control systems, and unlike most client–server systems, every Git directory on every computer is a full-fledged repository with complete history and full version-tracking abilities, independent of network access or a central server. Git is free and open-source software distributed under GNU General Public License Version 2.

Git is a free, open-source version control software. It was created by Linus Torvalds in 2005. This tool is a version control system that was initially developed to work with several developers on the Linux kernel.

This basically means that Git is a content tracker. So Git can be used to store content — and it is mostly used to store code because of the other features it provides.


![Git](https://i.morioh.com/2019/11/11/1f265e2d4c43.jpg)

### Git Commands 

![Git](https://miro.medium.com/max/720/1*PHuNOhupnXwBWWUtYuieag.jpeg)


# Version Control 


Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time.


### Type VCS 

### 1. Local Version Control System

A local version control system is a local database located on your local computer, in which every file change is stored as a patch. Every patch set contains only the changes made to the file since its last version. In order to see what the file looked like at any given moment, it is necessary to add up all the relevant patches to the file in order until that given moment.

The main problem with this is that everything is stored locally. If anything were to happen to the local database, all the patches would be lost. If anything were to happen to a single version, all the changes made after that version would be lost.

Also, collaborating with other developers or a team is very hard or nearly impossible.

![LVS](https://serengetitech.com/wp-content/uploads/2020/12/local-version-control.png)

### 2. Centralized Version Control System

A centralized version control system has a single server that contains all the file versions. This enables multiple clients to simultaneously access files on the server, pull them to their local computer or push them onto the server from their local computer. This way, everyone usually knows what everyone else on the project is doing. Administrators have control over who can do what.

This allows for easy collaboration with other developers or a team.

The biggest issue with this structure is that everything is stored on the centralized server. If something were to happen to that server, nobody can save their versioned changes, pull files or collaborate at all. Similar to Local Version Control, if the central database became corrupted, and backups haven't been kept, you lose the entire history of the project except whatever single snapshots people happen to have on their local machines.

The most well-known examples of centralized version control systems are Microsoft Team Foundation Server (TFS) and SVN.

![CVS](https://serengetitech.com/wp-content/uploads/2020/12/Centralized-Version-Control-System.png)

### 3. Distributed Version Control System 

With distributed version control systems, clients don’t just check out the latest snapshot of the files from the server, they fully mirror the repository, including its full history. Thus, everyone collaborating on a project owns a local copy of the whole project, i.e. owns their own local database with their own complete history. With this model, if the server becomes unavailable or dies, any of the client repositories can send a copy of the project's version to any other client or back onto the server when it becomes available. It is enough that one client contains a correct copy which can then easily be further distributed.

Git is the most well-known example of distributed version control systems.

![DVS](https://serengetitech.com/wp-content/uploads/2020/12/distributed-version-control.png)




[Read more about Git](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)