# Day 3: File Permissions

- ls -l shows permissions, e.g. -rw-------
- First character: - file, d folder
- Three groups: owner, group, everyone else
- r = read (4), w = write (2), x = execute (1)
- chmod 600 file : owner read/write only (safe)
- chmod 777 file : everyone can do everything (risky)
- Too-open permissions are a common security weakness
