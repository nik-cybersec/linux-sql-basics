# Managing File Contents in Bash

## Viewing File Contents
- `cat filename` — Displays the entire file.
- `less filename` — Scrollable file viewer.
- `more filename` — Page-by-page viewer.
- `head -n 5 filename` — Shows first 5 lines.
- `tail -n 5 filename` — Shows last 5 lines.

## Searching Within Files
- `grep "text" filename` — Searches for a string.
- `grep -i "text" filename` — Case-insensitive search.

## Redirection and Appending
- `>` — Overwrites file.
  ```bash
  echo "Hello" > file.txt

  echo "More text" >> file.txt
  cat file.txt | grep "error"
  
---


  




