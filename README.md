# Linux-User-Permission-Management-System
Project Description : 
This project demonstrates implementation of role-based user and permission management on a Linux server.
It simulates how enterprises control access to files and directories based on job roles.

The project focuses on:
- Creating users and groups

- Assigning users to appropriate groups

- Configuring file and directory permissions

- Testing access control using multiple user 
Environment :
Ubuntu Server 22.04 (AWS EC2 VM)

Linux CLI
Project Implementation :
1. Created Role-Based Groups

Created three groups to simulate organizational roles:

- admin

- developer

- support
Command used:
groupadd administrator
groupadd developer
groupadd support
