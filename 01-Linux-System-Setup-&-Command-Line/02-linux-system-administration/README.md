# Lab 02: Linux System Administration & User Management

**Difficulty:** Beginner to Intermediate  
**Environment:** Ubuntu Linux running in Oracle VirtualBox

## Overview

This lab focused on fundamental Linux system administration tasks, with an emphasis on managing user accounts, groups, file permissions and ownership.

The exercises provided practical experience with how Linux administrators control user access and manage permissions across the filesystem.

## Objectives

- Understand how Linux user accounts are managed.
- Create and manage user accounts and passwords.
- Create groups and assign users to them.
- Inspect and modify file and directory permissions.
- Manage file and directory ownership.
- Verify user and group membership.

## Environment

- Operating system: Ubuntu Linux
- Virtualisation software: Oracle VirtualBox
- Interface: Linux Terminal
- Shell: Bash

## Practical Exercises

### 1. User Account Management

Practised viewing existing Linux user accounts, creating new user accounts and managing passwords.

Commands:

| Command | Purpose |
|---|---|
| `sudo adduser` | Creates a new user account. |
| `passwd` | Sets or changes a user's password. |

### 2. Group Management

Practised creating Linux groups, adding users to groups and checking group membership.

Commands:

| Command | Purpose |
|---|---|
| `sudo groupadd` | Creates a new group. |
| `sudo usermod` | Modifies user account properties, including group membership. |
| `groups` | Displays the groups associated with a user. |
### 3. File Permissions

Practised inspecting and modifying file and directory permissions.

Commands:

| Command | Purpose |
|---|---|
| `ls -l` | Displays file permissions and ownership details. |
| `chmod` | Changes file and directory permissions. |

Linux permissions control three main types of access:

- **Read (r):** Allows users to view file contents.
- **Write (w):** Allows users to modify file contents.
- **Execute (x):** Allows users to execute files or access directories.

These permissions can be assigned to the file owner, group and other users.

### 4. File Ownership

Practised changing ownership of files and directories to manage access within the Linux filesystem.

Command:

| Command | Purpose |
|---|---|
| `chown` | Changes the owner and, where specified, group of a file or directory. |

## Testing and Verification

The exercises were performed in the Ubuntu terminal.

The following areas were practised:

- Viewing existing user accounts.
- Creating user accounts and managing passwords.
- Creating groups and assigning users.
- Inspecting and modifying file permissions.
- Changing file and directory ownership.
- Checking user and group membership.

## Skills Practised

- Linux user account administration.
- Password management.
- Group administration.
- File and directory permissions.
- Ownership management.
- Basic Linux access control.

## Conclusion

This lab provided practical experience with essential Linux administration tasks. It introduced the relationship between user accounts, groups, ownership and filesystem permissions.

These skills form an important foundation for supporting Linux systems and managing user access in an IT environment.
