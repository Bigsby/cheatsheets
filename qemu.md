Run raw binary bootloader
```
qemu-system-x86_64 -drive file=first.bin,format=raw
```

Run in nographic
```
qemu-system-x86_64 -nographic -drive file=first.bin,format=raw
```

In Qemu, go to monitor in graphic mode:
- `Ctrl`+`Alt`+2

In Qemu with -nographic:
- `Ctrl`+ A, X to exit
- `Ctrl`+ A, C to go to monitor

In Qemu with -curses:
- `Alt + 2` - Go To Monitor
- `Alt + 1` - Go To Emulartor

In Qemu monitor:
- xp /`n`i `address` to disassemble `n` bytes start from `address`

[Qemu Monitor docs](https://en.wikibooks.org/wiki/QEMU/Monitor)

