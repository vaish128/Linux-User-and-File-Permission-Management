# Project 3: Linux User and File Permission Management

## Project Description
This project focuses on managing users, groups, and file permissions in a Linux environment. It demonstrates how to control access to files and directories using Linux commands to ensure system security.

---

## Skills Gained
- Managing users and group permissions
- Managing directory permissions
- Managing file permissions
- Controlling access to files
- Controlling access to directories

---

## 1. Types of Files

### 1.1 User Defined Files
User-defined files are created by users and are human readable.

#### Types:
1. **Normal File** – Created using:
   `touch`, `vim`, `cat`, `nano`

2. **Directory File** – Created using:
   `mkdir`

3. **Link File** – Created using:
   `ln`

##### Types of Links:

- **Hard Link**
  - Link count: 2 or more
  - Looks like a normal file
  - First character in permission string: `-`

- **Soft Link (Symbolic Link)**
  - Link count: 1
  - First character in permission string: `l`

---

### 1.2 System Defined Files
System-defined files are created by the system.

#### Types:
- **Character File** → First character: `c`
- **Block File** → First character: `b`
- **Socket File** → First character: `s`
- **Pipe File** → First character: `p`

---

## 2. Types of Permissions

1. Owner Permission
2. Group Permission
3. Others Permission

---

## Checking File Permissions

### View File Permission
Use:
`ls -ltr sample`

📷 Output:
![File Permission Output](image1.png)

---

### View Directory Permission
Use:
`ls -ltr -d project`

📷 Output:
![Directory Permission Output](image2.png)

---

## Important Observations

- Hard link has link count 2 and looks like normal file.
- Soft link has link count 1 and starts with `lr`.
- Directory files start with `d`.
- Normal files start with `-`.
- Link count increases when a directory is added inside a directory.
- Link count does NOT increase when a file is added.
- The 5th field in `ls -ltr` output indicates file size.

---

## Student Details
**Name:** Vaishnavi Mule
