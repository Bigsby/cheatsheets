# Loading Linux Kernel from GRUB shell

### Set paging for long outputs
```
set pager=1
```

## List partitions
```
ls
```

## Find the partition where Linux file system is ...
```
ls (hd0,1)/
```

## Set root to the found Linux file system
```
set root=(hd0,1)/
```

## Tell GRUB where is the linux kernel and set the kernel mounted root
```
linux /boot/vmlinuz... root=/dev/sda1
```

## Set initrd file
```
initrd /boot/initrd.img.....
```

## Boot
```
boot
```

[more](https://www.linux.com/training-tutorials/how-rescue-non-booting-grub-2-linux/)
