# Users and Permissions in Linux

## Normal User
A normal user has limited permissions. This user can access personal files and run allowed programs but cannot modify critical system files.

## Root User
The root user is the administrator of the system and has full control over all files, users, and system settings. Misuse of root privileges can damage the system or cause security breaches.

---

## File Permissions

Linux permissions are divided into:
- r (read)
- w (write)
- x (execute)

Permissions are applied to:
- Owner
- Group
- Others

---

## Owner, Group, and Others

- Owner: The user who owns the file
- Group: A set of users who share the same access permissions
- Others: All users who are neither the owner nor part of the group

---

## chmod Command
The chmod command is used to change file and directory permissions. It controls who can read, write, or execute files.

---

## 777 Permission and Risk
777 permission allows everyone to read, write, and execute a file. This is dangerous because unauthorized users can modify files or execute malicious code.

---

## Least Privilege Principle
Users should only be given the minimum permissions required to perform their tasks. This reduces security risks and limits damage.
