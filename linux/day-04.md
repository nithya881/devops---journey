# Day 4: Linux Filesystem Structure

## What I Learned

Today I learned about the Linux filesystem hierarchy and the purpose of important directories.

Linux uses one filesystem hierarchy that starts from `/`.

## Important Directories

- `/` = Root of the entire filesystem
- `/home` = Home directories of normal users
- `/root` = Home directory of the root user
- `/etc` = System configuration files
- `/var` = Frequently changing data and logs
- `/tmp` = Temporary files
- `/usr` = Programs, libraries and shared resources
- `/bin` = Essential commands
- `/sbin` = System administration commands
- `/dev` = Device files
- `/proc` = Virtual filesystem with system and process information
- `/sys` = Virtual filesystem with kernel and device information
- `/boot` = Boot-related files
- `/opt` = Optional or additional software
- `/mnt` = Temporary filesystem mount point
- `/media` = Removable media
- `/srv` = Data provided by services
- `/run` = Runtime system information

## Important Concepts

- `/` and `/root` are different.
- `/` is the root of the entire filesystem.
- `/root` is the root user's home directory.
- `/home` contains normal users' home directories.
- `/proc` and `/sys` are virtual filesystems.
- Linux uses one filesystem hierarchy starting from `/`.
- In WSL2, the Windows C: drive is accessible through `/mnt/c`.
- `/bin` and `/sbin` may point to locations under `/usr` on modern Ubuntu systems.

## Commands Practiced

- `ls /`
- `ls /home`
- `ls /root`
- `ls /etc`
- `ls /var`
- `ls /tmp`
- `ls /usr`
- `ls /dev`
- `ls /proc`
- `ls /sys`
- `ls /boot`
- `ls /opt`
- `ls /mnt`
- `ls /media`
- `ls /srv`
- `ls /run`
- `find / -maxdepth 1 -type d 2>/dev/null`
- `df -h`

## Practical Work

- Explored the main Linux filesystem hierarchy.
- Inspected important system directories.
- Used `find` to view directories directly under `/`.
- Used `df -h` to check filesystem usage.
- Observed the Linux root filesystem mounted at `/`.
- Observed the Windows C: drive mounted at `/mnt/c` in WSL2.
- Observed Snap filesystem mounts.

## Remember

- `/` → Entire Linux filesystem
- `/home` → Normal users
- `/root` → Root user's home
- `/etc` → Configuration
- `/var` → Changing data and logs
- `/tmp` → Temporary files
- `/usr` → Programs and libraries
- `/dev` → Devices
- `/proc` → System and process information
- `/sys` → Kernel and device information
- `/boot` → Boot files
- `/mnt` → Mount point
- `/media` → Removable media
- `/run` → Runtime information

## Day 4 Completed

Linux filesystem structure and practical exploration completed. 
 
 
