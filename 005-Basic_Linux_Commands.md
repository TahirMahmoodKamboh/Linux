Below is a **concise command-focused content outline for Chapter 5 (Basic Linux Commands)**. This is suitable for a syllabus, slide agenda, or course outline where only **what will be covered** is required.

---

## **Chapter 5: Basic Linux Commands – Covered Commands**

### **1. Directory Navigation**

* `pwd` – show current directory
* `ls` – list files and directories
* `cd` – change directory

---

### **2. File and Directory Creation**

* `touch` – create empty files
* `mkdir` – create directories

---

### **3. File and Directory Operations**

* `cp` – copy files and directories
* `mv` – move or rename files
* `rm` – remove files and directories

---

### **4. Viewing File Contents**

* `cat` – display file contents
* `less` / `more` – paginated file viewing
* `head` – view first lines of a file
* `tail` – view last lines of a file

---

### **5. Command Help and Documentation**

* `man` – command manual pages
* `--help` option – quick command help

---

### **6. Command Basics**

* Command syntax (command + options + arguments)
* Using wildcards (`*`, `?`)
* Tab auto-completion
* Command chaining (`&&`)

---

### **Chapter Outcome**

By the end of this chapter, learners will be able to **navigate the Linux file system and perform basic file management from the command line**.

---

If you want, I can:

* Reduce this to a **one-slide summary**
* Align it with **RHCSA objectives**
* Add **examples per command (one-liners)**
* Provide a **print-friendly version**

Just let me know your preference.


Below are **hands-on labs for Chapter 5: Basic Linux Commands**. These labs are designed to be **practical, command-driven, and verifiable**, suitable for beginners while still aligning with real server usage.

---

# Chapter 5 – Hands-On Labs

**Topic: Basic Linux Commands**

**Prerequisites**

* Linux system (Ubuntu preferred)
* Non-root user with sudo access
* Terminal access

---

## **Lab 5.1: Understanding Your Location**

**Objective:** Learn how to identify your current directory.

### Tasks

1. Open the terminal.
2. Display your current working directory.

### Commands

```bash
pwd
```

### Expected Output

* A full path, e.g.:

```text
/home/tahir
```

---

## **Lab 5.2: Listing Files and Directories**

**Objective:** Learn to list directory contents using different options.

### Tasks

1. List files in the current directory.
2. List all files including hidden files.
3. List files in long format.

### Commands

```bash
ls
ls -a
ls -l
```

### Verification

* Hidden files start with `.`
* Permissions, owner, size, and date appear with `-l`

---

## **Lab 5.3: Navigating Directories**

**Objective:** Practice directory navigation.

### Tasks

1. Move to the `/etc` directory.
2. Return to your home directory.
3. Move one directory up.

### Commands

```bash
cd /etc
cd ~
cd ..
```

---

## **Lab 5.4: Creating Directories**

**Objective:** Create and manage directories.

### Tasks

1. Create a directory named `linux-labs`.
2. Create subdirectories `lab1`, `lab2` inside it.

### Commands

```bash
mkdir linux-labs
mkdir linux-labs/lab1 linux-labs/lab2
```

### Verification

```bash
ls linux-labs
```

---

## **Lab 5.5: Creating Files**

**Objective:** Create empty files.

### Tasks

1. Create a file named `file1.txt`.
2. Create multiple files at once.

### Commands

```bash
touch file1.txt
touch file2.txt file3.txt
```

---

## **Lab 5.6: Copying Files and Directories**

**Objective:** Copy files and directories.

### Tasks

1. Copy `file1.txt` to `lab1`.
2. Copy the entire `lab1` directory to `lab2`.

### Commands

```bash
cp file1.txt linux-labs/lab1/
cp -r linux-labs/lab1 linux-labs/lab2/
```

---

## **Lab 5.7: Moving and Renaming Files**

**Objective:** Move and rename files.

### Tasks

1. Rename `file2.txt` to `notes.txt`.
2. Move `notes.txt` to `lab2`.

### Commands

```bash
mv file2.txt notes.txt
mv notes.txt linux-labs/lab2/
```

---

## **Lab 5.8: Deleting Files and Directories**

**Objective:** Safely remove files and directories.

### Tasks

1. Delete `file3.txt`.
2. Delete directory `lab1`.

### Commands

```bash
rm file3.txt
rm -r linux-labs/lab1
```

> Warning: `rm -r` permanently deletes data.

---

## **Lab 5.9: Viewing File Contents**

**Objective:** Display file contents using different commands.

### Tasks

1. Add text to a file.
2. View the file using different commands.

### Commands

```bash
echo "Linux is powerful" > info.txt
cat info.txt
less info.txt
```

Exit `less` using `q`.

---

## **Lab 5.10: Viewing File Head and Tail**

**Objective:** View specific portions of a file.

### Tasks

1. Create a file with multiple lines.
2. Display first and last lines.

### Commands

```bash
for i in {1..20}; do echo "Line $i" >> lines.txt; done
head lines.txt
tail lines.txt
```

---

## **Lab 5.11: Command Help**

**Objective:** Learn how to get help.

### Tasks

1. View manual for `ls`.
2. Display short help.

### Commands

```bash
man ls
ls --help
```

Exit `man` using `q`.

---

## **Lab 5.12: Combining Commands**

**Objective:** Practice command chaining.

### Tasks

1. Create a directory and move into it in one line.
2. Create a file and list it.

### Commands

```bash
mkdir practice && cd practice
touch demo.txt && ls -l
```

---

## **Lab Completion Checklist**

You should be able to:

* Navigate directories confidently
* Create, copy, move, and delete files
* View file contents using multiple commands
* Use help and manuals effectively

---


