# Authentication and Authorization in Linux

## Authentication
- Verifying identity of a user.
- Managed via `/etc/passwd`, `/etc/shadow`.

## Common Commands:
- `whoami` — Shows current user.
- `passwd` — Change current user's password.
- `sudo` — Execute as superuser.

## Authorization (Permissions)
- Who can read/write/execute files.

### File Permissions Example
- `ls -l` output:
  ```bash
  -rw-r--r-- 1 user group 1234 Apr 30 file.txt
  chmod 755 script.sh
  sudo chown user:group file.txt
  
---



