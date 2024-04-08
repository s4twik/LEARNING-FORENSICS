have seen volatility being used before but i don't have a very clear idea
first we learn about how to identify the profile of the mem dump.
tried using it on the memdump file from bitsCTF, (Damian one)
then did pslist and psscan, 
psscan is more indepth than pslist, it can find more details
```malware generally uses svchost.exe or spelling mistakes scvhost.exe```
```svchost.exe should always have the parent proces as services.exe```

set of process can be acquired by `pstree`
the PID of services.exe and PPID svchost.exe should be same

cmdscan and consoles are used to get the commands entered by the user and get the output they got

`procdump`,`netscan`, `filedump`, `memdump` is covered
`imagecopy` is used to make a raw data copy of a hibernation, crash or VM core file and can be used to analyze it.
`timeliner` is used to collect timelines 
