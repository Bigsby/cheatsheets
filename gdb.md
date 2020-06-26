# Daskboard script
[link](https://github.com/Bigsby/gdb-dashboard)

# Cheatsheet
[link](https://darkdust.net/files/GDB%20Cheat%20Sheet.pdf)

# Commands Within GDB console
### Connect to remote (localhost) session
```
target remote localhost:<port>
```

### Set breakpoint at instruction memory address
```
break *<address>
```
Example for boot sector start:
```
break *0x7c00
```
