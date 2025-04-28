# Basic Linux Commands

- `pwd` — Show current directory
- `ls` — List files
- `cd` — Change directory
- `mkdir` — Make a new directory
- `touch` — Create a new empty file
- `cat` — View file content
- `rm` — Remove a file
- `rmdir` — Remove a directory
- # Linux Basics - Commands and Concepts

## File Permissions
- `chmod` — Change file permissions.
  - Example: `chmod 755 filename`
- `ls -l` — View detailed file permissions.

## Important Commands
- `grep` — Search for text patterns in files.
  - Example: `grep "error" logfile.txt`
- `head` — Display the first 10 lines of a file.
  - Example: `head logfile.txt`
- `tail` — Display the last 10 lines of a file.
  - Example: `tail logfile.txt`
- `| (pipe)` — Send the output of one command as input to another.
  - Example: `cat logfile.txt | grep "error"`

## Managing Users
- `sudo adduser username` — Add a new user.
- `sudo userdel username` — Delete a user.
- `passwd username` — Change user password.

