# User Management Practice

This file documents user management commands.

## Creating User
Command:
useradd vinit

Example:
$ ls /home
vinit

---

## Default User Settings
Command:
cat /etc/default/useradd

Description:
Shows default configuration for new users.

---

## Custom Home Directory
Command:
useradd -d /test/user1 user1

Example:
$ ls /test
user1

---

## Deleting User
Command:
userdel -rf vinit

Description:
Deletes user and home directory.

---

## Objective
This practice demonstrates basic Linux user administration.
