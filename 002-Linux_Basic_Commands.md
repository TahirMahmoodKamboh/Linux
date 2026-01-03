# Chapter 2 – Linux Basic Commands

## 2.1 Viewing Current Directory and Contents

| Command | Description | Example |
|--------|-------------|---------|
| `pwd` | Shows current working directory | `pwd` |
| `ls` | Lists files and directories in current directory | `ls` |
| `ls -l` | Long listing with permissions, owner, size, date | `ls -l` |
| `ls -a` | List all files including hidden ones | `ls -a` |
| `ls -lh` | Human-readable sizes | `ls -lh` |

---

## 2.2 Changing Directories

| Command | Description | Example |
|--------|-------------|---------|
| `cd /path` | Move to directory using absolute path | `cd /var/log` |
| `cd ..` | Move to parent directory | `cd ..` |
| `cd ../..` | Move up two levels | `cd ../..` |
| `cd` or `cd ~` | Move to home directory | `cd` |
| `cd -` | Move to previous directory | `cd -` |

---

## 2.3 Viewing File Contents

| Command | Description | Example |
|--------|-------------|---------|
| `cat filename` | Display full content of a file | `cat file.txt` |
| `less filename` | View content page by page | `less file.txt` |
| `head -n 5 filename` | Show first 5 lines | `head -n 5 file.txt` |
| `tail -n 5 filename` | Show last 5 lines | `tail -n 5 file.txt` |
| `tail -f filename` | Monitor file updates in real-time | `tail -f /var/log/syslog` |

---

## 2.4 Creating, Copying, Moving, and Deleting Files

| Command | Description | Example |
|--------|-------------|---------|
| `touch filename` | Create an empty file | `touch file.txt` |
| `cp source dest` | Copy file or directory | `cp file.txt backup.txt` |
| `mv source dest` | Move or rename file | `mv file.txt file_old.txt` |
| `rm filename` | Delete file | `rm file.txt` |
| `rm -r directory` | Delete directory recursively | `rm -r test_dir` |
| `mkdir dirname` | Create directory | `mkdir new_folder` |
| `mkdir -p dir1/dir2` | Create nested directories | `mkdir -p parent/child` |

---

## 2.5 Searching and Finding Files

| Command | Description | Example |
|--------|-------------|---------|
| `find /path -name filename` | Search for file in directory tree | `find /home -name file.txt` |
| `grep "text" filename` | Search text inside file | `grep "error" syslog.log` |
| `grep -i "text" filename` | Case-insensitive search | `grep -i "error" syslog.log` |
| `locate filename` | Quickly find file using database | `locate file.txt` |

---

## 2.6 Viewing System Information

| Command | Description | Example |
|--------|-------------|---------|
| `whoami` | Show current user | `whoami` |
| `id` | Show user ID and groups | `id` |
| `uname -a` | Show system/kernel information | `uname -a` |
| `df -h` | Show disk usage in human-readable form | `df -h` |
| `free -h` | Show memory usage | `free -h` |
| `uptime` | Show system uptime | `uptime` |

---

## 2.7 File Permissions

| Command | Description | Example |
|--------|-------------|---------|
| `ls -l` | Show file permissions | `ls -l file.txt` |
| `chmod 755 file` | Change file permissions | `chmod 755 script.sh` |
| `chown user:group file` | Change file ownership | `chown tahir:tahirs file.txt` |

---

## Key Notes

- `pwd`, `ls`, and `cd` are essential for navigation.  
- `cat`, `less`, `head`, `tail` help view file contents efficiently.  
- `touch`, `cp`, `mv`, `rm`, and `mkdir` are for file and directory management.  
- `find` and `grep` are powerful tools for searching files and text.  
- Always check permissions using `ls -l`; modify carefully with `chmod` and `chown`.  
```
