# Command Path and Environment Practice

This file documents how Linux locates command binaries.

## Locating Commands
Command:
which vi

Example:
$ which vi
/usr/bin/vi

Description:
Shows the absolute path of the vi command.

---

## Checking Multiple Commands
Commands:
which vim
which gedit
which useradd

Example:
$ which vim
/usr/bin/vim

Description:
Verifies availability and location of commands.

---

## PATH Variable
Command:
echo $PATH

Example:
$ echo $PATH
/usr/bin:/usr/sbin:/root/bin

Description:
Displays directories searched for executable commands.

---

## Objective
This practice explains how Linux finds and executes commands.
