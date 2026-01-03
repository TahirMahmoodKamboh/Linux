***Linux***

- Is an OS (Operating System)
- Is open source.
- Created in 1991.
- Linus Torvalds a Finnish (from Finland) Software engineer created Linux in 1991.
- Linus Torvalds began developing the kernel as a student at the University of Helsinki.
- Linux Torvalds wanted a free UNIX-like system for his personal computer.
- Code is publicly available, and users can modify and expand it
- Supports multiple users and multi-tasking.
- Is built to handle networking.
- Provides system tools and utilities.

Linux is an operating system that is freely distributable under the terms of the Gnu is
Not Unix (GNU) General Public License (GPL). It is open source because it provides
the source code for the core functionality of an operating system, called a kernel,
and users can modify and expand it. As a result, many distributions of Linux are
available today.

Linux Benefits
Is modular
Is stable
Is commonly used as a server operating system
Is also used as a desktop operating system.

| Concept | Description | Example/Notes |
|---------|-------------|---------------|
| Linux | An open-source, Unix-like operating system kernel | Linux kernel version: `uname -r` |
| Linux OS | A complete operating system built around the Linux kernel and user-space tools | Ubuntu, Fedora, CentOS, Debian |

**Command Example:**
```bash
uname -a
````

* Displays kernel name, version, architecture, and system info

---

## 1.2 Linux Distributions

| Distribution         | Description                                   | Example Use           |
| -------------------- | --------------------------------------------- | --------------------- |
| Ubuntu               | User-friendly, popular for desktops & servers | `apt` package manager |
| CentOS / Rocky Linux | Enterprise-grade, RHEL compatible             | Server deployments    |
| Debian               | Stable, community-driven                      | Desktop or server     |
| Fedora               | Cutting-edge, latest packages                 | Developers            |
| Arch Linux           | Minimalistic, rolling release                 | Experienced users     |

**Command to check distro:**

```bash
cat /etc/os-release
```

---

## 1.3 Linux vs Other Operating Systems

| Feature         | Linux                         | Windows         | macOS               |
| --------------- | ----------------------------- | --------------- | ------------------- |
| Kernel          | Monolithic                    | Hybrid          | Hybrid              |
| Open Source     | Yes                           | No              | Partially           |
| File System     | Ext4, XFS, Btrfs              | NTFS            | APFS, HFS+          |
| Package Manager | `apt`, `yum`, `dnf`, `pacman` | Installer/Store | Homebrew, App Store |
| Command Line    | Bash, Zsh, Fish               | CMD, PowerShell | Terminal (Zsh/Bash) |
| Cost            | Free                          | Paid            | Paid                |

---

## 1.4 Linux Kernel and User Space

| Component  | Description                                                 |
| ---------- | ----------------------------------------------------------- |
| Kernel     | Core of Linux; manages hardware, memory, processes, devices |
| User Space | Programs, libraries, shells that interact with kernel       |
| Shell      | Command interpreter for user interaction (`bash`, `zsh`)    |

**Example:**

```bash
echo $SHELL
```

* Shows which shell you are using

---

## 1.5 Basic Terminal Introduction

| Concept           | Description                           | Example             |
| ----------------- | ------------------------------------- | ------------------- |
| Terminal          | Text interface to interact with OS    | Open `Terminal` app |
| Command           | Instruction given to shell            | `ls`, `pwd`, `cd`   |
| Prompt            | Shows the shell is ready              | `tahir@Linux:~$`    |
| Home Directory    | Default directory when terminal opens | `cd ~`              |
| Current Directory | Where the terminal is currently       | `pwd`               |

**Basic Commands to Try:**

```bash
pwd     # show current directory
ls      # list files in current directory
cd ~    # go to home directory
whoami  # show current user
```

---

## Key Notes

* Linux is an open-source, Unix-like OS with a kernel and user-space components.
* There are many distributions; some are user-friendly (Ubuntu), some enterprise-focused (CentOS/Rocky).
* The kernel handles hardware and processes; the shell allows command-line interaction.
* Terminal is the primary interface for Linux beginners; `pwd`, `ls`, `cd`, and `whoami` are essential commands to start.

```
