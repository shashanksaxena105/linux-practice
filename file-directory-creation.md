# File and Directory Creation Practice

This file documents my practice of creating files and directories in Linux.

## Creating Directory in Home
Command:
mkdir data

Example:
$ mkdir data
$ ls
data

Description:
Creates a directory named data in the current location.

---

## Creating Directory in Root (/)
Command:
mkdir /fedora

Example:
$ mkdir /fedora
$ ls /
fedora

Description:
Creates a directory directly under root filesystem.

---

## Creating Nested Directories
Commands:
mkdir /linux
mkdir /linux/fedora

Example:
$ ls /linux
fedora

Description:
Creates parent and child directories.

---

## Creating File
Command:
touch /linux/abc

Example:
$ ls /linux
abc  fedora

Description:
Creates an empty file named abc.

---

## Objective
This practice demonstrates file and directory creation using absolute paths.
