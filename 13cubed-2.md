`lsass.exe` is process that handles password and cred related functions(it should never occur more than once)
`_EPROCESS` block - memory structure associated with Windows processes and contains many attributes related to a process,a and points to other related data structures
`cmdscan and consoles` to get commmand line output. `modscan` for the drivers running
`malfind`-detects compromised processes
`PAGE_EXECUTE_READWRITE` means that a portion of memory is allocated to a process but no files (sus)
`hollowfind` similar to malfind but uses different processes
