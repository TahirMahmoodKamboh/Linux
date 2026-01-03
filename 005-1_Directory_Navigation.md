Below are **focused, step-by-step hands-on labs for Chapter 5.1: Directory Navigation**. These labs are **simple, practical, and assessment-ready**, suitable for beginners and classroom delivery.

---

## **Chapter 5.1 – Directory Navigation**

**Commands Covered:** `pwd`, `ls`, `cd`

**Prerequisites**

* Linux system (Ubuntu or similar)
* Terminal access
* Logged in as a normal user

---

## **Lab 5.1.1: Identify Current Working Directory**

**Objective:** Learn how to check your current location in the filesystem.

### Steps

1. Open the terminal.
2. Run the following command:

```bash
pwd
```

### Expected Result

* Output similar to:

```text
/home/tahir
```

---

## **Lab 5.1.2: List Directory Contents**

**Objective:** Learn to view files and directories.

### Steps

1. List contents of the current directory:

```bash
ls
```

2. List all files including hidden files:

```bash
ls -a
```

3. List files in long format:

```bash
ls -l
```

### Expected Result

* Hidden files start with `.`
* Permissions, owner, and size are shown in long format

---

## **Lab 5.1.3: Change Directory Using Absolute Path**

**Objective:** Navigate using full paths.

### Steps

1. Move to the `/etc` directory:

```bash
cd /etc
```

2. Confirm your location:

```bash
pwd
```

---

## **Lab 5.1.4: Change Directory Using Relative Path**

**Objective:** Navigate relative to current directory.

### Steps

1. From `/etc`, move to its parent directory:

```bash
cd ..
```

2. Verify location:

```bash
pwd
```

---

## **Lab 5.1.5: Navigate to Home Directory**

**Objective:** Quickly return to home directory.

### Steps

1. Use shortcut to return home:

```bash
cd ~
```

or

```bash
cd
```

2. Verify:

```bash
pwd
```

---

## **Lab 5.1.6: Navigate Multiple Levels**

**Objective:** Practice multi-level navigation.

### Steps

1. Create directories:

```bash
mkdir -p linux-labs/nav
```

2. Navigate into the directory:

```bash
cd linux-labs/nav
```

3. Move back two levels:

```bash
cd ../..
```

---

## **Lab 5.1.7: List Contents of Another Directory**

**Objective:** View directory contents without changing location.

### Steps

```bash
ls /etc
ls /var/log
```

---

## **Lab 5.1.8: Use Tab Auto-Completion**

**Objective:** Improve speed and accuracy.

### Steps

1. Type:

```bash
cd /va
```

2. Press `Tab`
3. Complete the command and press Enter.

---

## **Lab 5.1.9: Clear Terminal and Review**

**Objective:** Improve terminal usability.

### Steps

```bash
clear
```

---

## **Assessment Task (Optional)**

1. Navigate to `/var`
2. List its contents in long format
3. Return to your home directory

**Expected Commands**

```bash
cd /var
ls -l
cd ~
```

---

## **Lab Outcome**

After completing these labs, learners will be able to:

* Identify their location in Linux filesystem
* Navigate using absolute and relative paths
* Efficiently list directory contents
* Use shortcuts and tab completion

---


