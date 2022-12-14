# Overview

Slurm is an open source, fault-tolerant, and highly scalable cluster management and job scheduling system for large and small Linux clusters. 
Slurm requires no kernel modifications for its operation and is relatively self-contained. As a cluster workload manager, Slurm has three key functions. 
- First, it allocates exclusive and/or non-exclusive access to resources (compute nodes) to users for some duration of time so they can perform work. 
- Second, it provides a framework for starting, executing, and monitoring work (normally a parallel job) on the set of allocated nodes. 
- Finally, it arbitrates contention for resources by managing a queue of pending work.



### How to use this guidebook?
The compiled material represents the necessary package of knowledge required for an ISSAI researcher.  We recommend to go through the sections in the incremetal order, one by one.

How to start?
- If you own a Windows machine, please start with [Section-0.1](docs/00-Setup/01-Setup-Windows.md) to install Windows Subsystem for Linux (WSL), and then launch the WSL terminal and proceed with [Section-0.2](docs/00-Setup/02-Remote-Connect.md). 
- If you are a Linux user, begin with [Section-0.2](docs/00-Setup/02-Remote-Connect.md). 
- If you have an Apple computer, use the default terminal. macOS supports all standard UNIX commands. In practice, most common LINUX commands are suitable for Mac. But if you have access to a remote Linux server/machine, please connect to it and then proceed with [Section-0.2](docs/00-Setup/02-Remote-Connect.md). 

# Table of Contents

- [Chapter-0-Setup](docs/00-Setup)
  
  - [Section-0.1-Setup-Windows](docs/00-Setup/01-Setup-Windows.md)
  - [Section-0.2-Remote-Connect](docs/00-Setup/02-Remote-Connect.md)

- [Chapter-1-Working-With-Shell-Part-I](docs/01-Working-With-Shell-Part-I)

  - [Section-1.1-Introduction-to-Shell](docs/01-Working-With-Shell-Part-I/01-Introduction-to-Shell.md)
  - [Section-1.2-Basic-Commands](docs/01-Working-With-Shell-Part-I/02-Basic-Commands.md)
  - [Section-1.3-Command-Line-Help](docs/01-Working-With-Shell-Part-I/03-Command-Line-Help.md)
  - [Section-1.4-Bash-Shell](docs/01-Working-With-Shell-Part-I/04-Bash-Shell.md)

- [Chapter-2-Linux-Core-Concepts](docs/02-Linux-Core-Concepts)

  - [Section-2.1-The-Linux-Kernel](docs/02-Linux-Core-Concepts/01-The-Linux-Kernel.md)
  - [Section-2.2-Working-With-Hardware](docs/02-Linux-Core-Concepts/02-Working-with-hardware.md)
  - [Section-2.3-Lab-Linux-Kernel](docs/02-Linux-Core-Concepts/03-Lab-Linux-Kernel.md)
  - [Section-2.4-File-Types](docs/02-Linux-Core-Concepts/04-File-Types.md)
  - [Section-2.5-Filesystem-Hierarchy](docs/02-Linux-Core-Concepts/05-Filesystem-Hierarchy.md)
  
- [Chapter-3-Package-Management](docs/03-Package-Management)

  - [Section-3.1-Package-Management-Distribution](docs/03-Package-Management/01-Package-Management-Distribution.md)
  - [Section-3.2-APT](docs/03-Package-Management/02-APT.md)
  - [Section-3.3-Lab-APT](docs/03-Package-Management/03-Lab-APT.md)


- [Chapter-4-Working-With-Shell-Part-II](docs/04-Working-With-Shell-Part-II)

  - [Section-4.1-File-Compression-and-Archival](docs/04-Working-With-Shell-Part-II/01-File-Compression-and-Archival.md)
  - [Section-4.2-Searching-For-Files-and-Patterns](docs/04-Working-With-Shell-Part-II/02-Searching-for-files-and-patterns.md)
  - [Section-4.3-IO-Redirection](docs/04-Working-With-Shell-Part-II/03-IO-Redirection.md)
  - [Section-4.4-Vi-Editor](docs/04-Working-With-Shell-Part-II/04-Vi-Editor.md)
  - [Section-4.5-Lab-VI-Editor](docs/04-Working-With-Shell-Part-II/05-Lab-VI-Editor.md)

- [Chapter-5-Security-and-File-Permissions](docs/05-Security-and-File-Permissions)

  - [Section-5.1-Linux-Accounts](docs/05-Security-and-File-Permissions/01-Linux-Accounts.md)
  - [Section-5.2-File-Permissions](docs/05-Security-and-File-Permissions/02-File-Permissions.md)
  - [Section-5.3-Connect-SSH](docs/05-Security-and-File-Permissions/03-SSH.md)
  - [Section-5.4-Transfer-Data-Rsync](docs/05-Security-and-File-Permissions/04-Rsync.md)
  - [Section-5.5-Cronjob](docs/05-Security-and-File-Permissions/05-Cronjob.md)
  - [Section-5.3-Using the SSH Config File](docs/05-Security-and-File-Permissions/03-SSH.md)

- [Chapter-6-Remote-Work](docs/08-Remote-Work)
  - [Section-6.1-Tmux](docs/08-Remote-Work/01-Tmux.md)
  - [Section-6.2-Remote-Interpreter-Pycharm](docs/08-Remote-Work/02-Remote-Interpreter-Pycharm.md)
  - [Section-6.3-Remote-Development-In-Visual-Studio](docs/08-Remote-Work/03-Remote-Development_Visual_Code.md)
