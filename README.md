# Bash Scripting Assignment (30% OF FINAL MARKS)
IA616001 OPERATING SYSTEM
SUBMITTED BY:REETIKA SHRESTHA
SUBMITTED TO :WILLIAM LIU

## Author Details
- **Full Name**: REETIKA SHRESTHA
- **DUE DATE**:26/05/2024

## Project Description
This repository contains two  Bash scripts that helps to automate the creation of user and configuration of the user environment,backup directories.

### Task 1: Creating a User Environment
The first script helps to automate the creation of user and configures them based on data provided on a CSV file.

#### INSTRUCTIONS :
1. OPEN TERMINAL:
2. CREATE A FILE AND WRITE THE SCRIPT.
3. MAKE SURE YOU HAVE THE CSV FILE TO INGEST USER-RELATED INFORMATION.
4. AFTER FOLLOWING ALL THE COMMANDS LIKE CHMOD +X AND./USERS.SH,
5. YOU CAN NOW VIEW ALL THE INFORMATION INSIDE THE USER_CREATION LOG .

### Task 2: Backup Script
The second script compresses a given folder and uploads it to a remote location and creates a backup.

#### INSTRUCTIONS :
1. OPEN TERMINAL.
2. CREATE A FILE AND WRITE THE SCRIPT. (NANO COMMAND AFTER WRITING THE SCRIPT PRESS CTRL+X THEN ENTER)
3. THE PATH IS NOT HARDCODED YOU CAN DO PUT YOUR LOCATION AS WELL BUT THERE IS A STRUCTURE YOU NEED TO FOLLOW <directory_to_backup> <remote_user> <remote_host> <remote_port> <remote_path> <output_directory>"
  ~/Documents/bash_script/backup.sh /home/Documents/shrer5/testdir shrer5 backupserver.com 22 /home/shrer5/backups /tmp
Directory to backup: /home/Documents/shrer5/testdir
Remote user: shrer5
Remote host: backupserver.com
Remote port: 22
Remote path: /home/shrer5/backup
Output directory: /tmp


## Prerequisites
- Ubuntu Linux system
- Bash shell
- Git (for version controlling)
- CSV file containing user information

## Project Structure

├── README.md
├── BSA_Self_Assessment.txt
├── task1
│ ├── users.sh
│ ├── users.csv
│ └── logs
└── task2
├── backup.sh
└── testdir
