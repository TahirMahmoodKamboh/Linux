Perfect! We can put all the **Chapter 5.1 – Directory Navigation command tables** into a **Markdown (`.md`) file** format. I’ll include **all commands (`pwd`, `ls`, `cd`) with descriptions and extended examples** in clean tables.

Here’s the **ready-to-use Markdown content**:

---

```markdown
# Chapter 5.1 – Directory Navigation

## 1. `pwd` – Print Working Directory

| Command | Description | Example |
|--------|-------------|---------|
| `pwd`  | Displays the absolute path of the current working directory | `pwd` |
**Example Output:**  
```

/home/tahir

```

---

## 2. `ls` – List Directory Contents

| Command | Description | Example |
|--------|-------------|---------|
| `ls` | Lists files and directories in the current directory | `ls` |
| `ls -l` | Long listing with permissions, owner, size, and date | `ls -l` |
| `ls -a` | Lists all files including hidden files | `ls -a` |
| `ls -lh` | Long listing with human-readable sizes | `ls -lh` |
| `ls -lt` | Sorts files by modification time | `ls -lt` |
| `ls -lr` | Lists files in reverse order | `ls -lr` |
| `ls -la` | Combines long listing with hidden files | `ls -la` |
| `ls /etc` | Lists contents of another directory | `ls /etc` |
| `ls *.conf` | Lists files matching a pattern | `ls *.conf` |
| `ls -d */` | Lists only directories | `ls -d */` |
| `ls -ld linux-labs` | Shows detailed info of a directory itself, not its contents | `ls -ld linux-labs` |

---

## 3. Absolute vs Relative Paths

| Type | Description | Example |
|------|-------------|---------|
| Absolute Path | Path starting from root `/` | `/var/log` |
| Relative Path | Path relative to current directory | `../log` |

---

## 4. `cd` – Change Directory

| Command | Description | Example |
|--------|-------------|---------|
| `cd /path` | Changes directory using an absolute path | `cd /var/log` |
| `cd ..` | Moves to the parent directory | `cd ..` |
| `cd ../..` | Moves up two directory levels | `cd ../..` |
| `cd` | Changes to the home directory | `cd` |
| `cd ~` | Explicitly changes to the home directory | `cd ~` |
| `cd -` | Switches to the previous directory | `cd -` |
| `cd ~/Documents` | Navigates using home shortcut | `cd ~/Documents` |
| `cd linux-labs/nav` | Navigates using a relative path | `cd linux-labs/nav` |
| `cd /` | Moves to the root directory | `cd /` |

---

## 5. Listing Other Directories

| Command | Description | Example |
|--------|-------------|---------|
| `ls /path` | Lists contents of another directory without changing location | `ls /etc` |
| `ls /var/log` | Lists contents of `/var/log` | `ls /var/log` |

---

## 6. Tab Auto-Completion

| Feature | Description | Example |
|--------|-------------|---------|
| Tab completion | Automatically completes commands or paths to save typing | Type `cd /va` + [Tab] → auto-completes to `/var` |

---

## 7. `clear` – Clear Terminal Screen

| Command | Description | Example |
|--------|-------------|---------|
| `clear` | Clears all previous output for a clean terminal | `clear` |

---

## **Key Notes**

- Use `pwd` to know your current directory.  
- `ls` is your primary command to explore files and directories.  
- `cd` is used for navigation – remember shortcuts like `cd ~` and `cd -`.  
- `ls -ld` is useful to check **directory permissions** without listing its contents.  
- Tab auto-completion and `clear` improve terminal efficiency.
```

---

This `.md` file is **ready to save as `Chapter_5.1_Directory_Navigation.md`**.

It includes:

* All commands (`pwd`, `ls`, `cd`)
* Absolute and relative paths
* Extended `ls` examples, including `ls -ld`
* Tab completion and clear

---

If you want, I can **also create Markdown tables for Chapter 5.2 (File & Directory Creation) next**, in the **same clean format** ready to add to the same `.md` file.

Do you want me to do that?
