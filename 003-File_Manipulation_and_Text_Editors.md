# Chapter 3 – File Manipulation and Text Editors

## 3.1 Viewing File Contents

| Command | Description | Example |
|--------|-------------|---------|
| `cat filename` | Display the full content of a file | `cat file.txt` |
| `less filename` | View file content page by page | `less file.txt` |
| `head -n 5 filename` | Show first 5 lines of a file | `head -n 5 file.txt` |
| `tail -n 5 filename` | Show last 5 lines of a file | `tail -n 5 file.txt` |
| `tail -f filename` | Monitor file in real-time (logs) | `tail -f /var/log/syslog` |

---

## 3.2 Creating and Editing Files

| Command/Editor | Description | Example |
|----------------|-------------|---------|
| `touch filename` | Create an empty file | `touch notes.txt` |
| `nano filename` | Open file in nano editor (simple) | `nano notes.txt` |
| `vim filename` | Open file in Vim editor (advanced) | `vim notes.txt` |
| `echo "text" > filename` | Write text to a file (overwrite) | `echo "Hello" > file.txt` |
| `echo "text" >> filename` | Append text to a file | `echo "World" >> file.txt` |

**Nano Editor Basics:**  
- `Ctrl + O` → Save file  
- `Ctrl + X` → Exit editor  
- `Ctrl + K` → Cut line  
- `Ctrl + U` → Paste line  

**Vim Basics:**  
- Press `i` → Enter insert mode  
- Press `Esc` → Exit insert mode  
- `:w` → Save  
- `:q` → Quit  
- `:wq` → Save & quit  

---

## 3.3 Copying, Moving, and Deleting Files

| Command | Description | Example |
|--------|-------------|---------|
| `cp source dest` | Copy file or directory | `cp file.txt backup.txt` |
| `mv source dest` | Move or rename file | `mv file.txt oldfile.txt` |
| `rm filename` | Delete file | `rm file.txt` |
| `rm -r directory` | Delete directory recursively | `rm -r old_folder` |
| `mkdir dirname` | Create directory | `mkdir new_folder` |
| `mkdir -p dir1/dir2` | Create nested directories | `mkdir -p parent/child` |

---

## 3.4 File Permissions Overview

| Command | Description | Example |
|--------|-------------|---------|
| `ls -l` | Show file permissions, owner, and group | `ls -l file.txt` |
| `chmod 755 filename` | Change file permissions | `chmod 755 script.sh` |
| `chown user:group filename` | Change file ownership | `chown tahir:tahirs file.txt` |
| `ls -ld directory` | Check directory permissions | `ls -ld linux-labs` |

---

## 3.5 Searching Text in Files

| Command | Description | Example |
|--------|-------------|---------|
| `grep "text" filename` | Search for text inside a file | `grep "error" syslog.log` |
| `grep -i "text" filename` | Case-insensitive search | `grep -i "error" syslog.log` |
| `grep -r "text" /path` | Search recursively in directories | `grep -r "TODO" ~/projects` |

---

## Key Notes

- Use `cat`, `less`, `head`, `tail` to view files.  
- `nano` is beginner-friendly; `vim` is advanced but very powerful.  
- File operations (`cp`, `mv`, `rm`, `mkdir`) allow efficient file and folder management.  
- File permissions control who can read, write, or execute files.  
- `grep` is a powerful tool to search text inside files and directories.  
```
