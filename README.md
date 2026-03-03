# Project : Linux User and File Permission Management

## Project Description

This project focuses on managing users, groups, and file permissions in a Linux environment. It demonstrates how to control access to files and directories using Linux commands to ensure system security.

---

## Skills Gained

• managing users and group permissions  
• Managing directory permission  
• managing file permission  
• control access to files  
• control access to directories  

---

## 1. Types of Files

### 1. User Defined Files:
User Defined Files are created by user which are human readable

### Types of User Defined Files:

1. Normal File : It create by touch vim cat nano  
2. Directory File : It create by mkdir  
3. Link File : create by ln  

There are two types of link file:

• Hard Link : Link count 2 or more and they look like normal which first character in permission string is -  

• Soft Link: Link count 1 and the first character in the permissions string is l  

---

### 2. System Defined Files:
System Defined file are created by system  

### Types of System Defined Files:

1. Character File : The first character in the permissions string is c  
2. Block files: The first character in the permissions string is b  
3. Socket file: The first character in the permissions string is s  
4. Pipe file: The first character in the permissions string is p  

---

## 2. Types of Permission

1. Owner Permission  
2. Group Permission  
3. Others Permission  

---

• ls -ltr sample : It use for see the permission of file  

![Image](image1.png)

---

• ls -ltr -d project: It use for see the permission of directory  

![Image](image2.png)

---

• Hardlink has link count 2 and it looks like normal  

![Image](image3.png)

---

• Softlink has link count 1 and it start with lr  

![Image](image4.png)

---

• Directory file string with d  

![Image](image5.png)

---

• Normal Files strating with -  

![Image](image6.png)

---

• Link Count is incresing when we perform some action in directory  

For Example: When we add directory in directory, So link count is increase  

![Image](image7.png)

---

• when we add file in directory , link count doesn’t increase  

![Image](image8.png)

---

• 5th field is indicated as size of file  

![Image](image9.png)

---

## NAME : VAISHNAVI MULE
