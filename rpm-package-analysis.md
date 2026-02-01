# RPM Package Analysis Practice

This file documents my practice with RPM package commands.

## List Installed Packages
Command:
rpm -qa

Description:
Lists all installed RPM packages.

---

## Identify Package for Command
Command:
rpm -qf /usr/bin/vi

Example:
vim-minimal-9.1.083-5.el10.x86_64

Description:
Identifies which package provides a command.

---

## List Config Files of Package
Command:
rpm -qc shadow-utils

Example:
/etc/default/useradd

Description:
Shows configuration files of a package.

---

## Objective
This practice demonstrates RPM package management skills.
