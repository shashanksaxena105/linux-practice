# Linux User Management Practice

This file documents my hands-on practice with user and account management in Linux during my system administration training.

## Creating a User
Command:
useradd username  

Example:
$ useradd punit  

Description:
Creates a new user account in the system.

---

## Setting User Password
Command:
passwd username  

Example:
$ passwd punit  

Description:
Sets or changes the password for a user.

---

## Deleting a User
Command:
userdel username  

Example:
$ userdel student

Description:
Deletes a user account.

---

## Deleting User with Home Directory
Command:
userdel -r username  

Example:
$ userdel -r student

Description:
Deletes the user along with home directory and mail spool.

---

## Locking and Unlocking a User
Commands:
usermod -L username  
usermod -U username  

Example:
$ usermod -L kavi
$ usermod -U kavi

Description:
Locks and unlocks a user account.

---

## Creating User with Custom Home Directory
Command:
useradd -d /test/user1 user1  

Description:
Creates a user with a custom home directory.

---

## Checking Home Directories
Command:
ls /home  

Description:
Lists all user home directories.

---

## Objective
This practice demonstrates my understanding of Linux user account creation, deletion, password management, and account control operations.
