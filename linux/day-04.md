# Day 4: Linux Filesystem Structure

## What I Learned

Today I learned more about the Linux filesystem hierarchy and the purpose of important directories.

Linux uses one main filesystem hierarchy that starts from the root directory `/`.

## Important Directories

### `/`

The root directory is the top of the Linux filesystem hierarchy.

All other directories exist under `/`.

### `/home`

Contains the home directories of normal users.

### `/etc`

Contains system configuration files.

### `/var`

Contains data that changes while the system operates, such as logs and application data.

### `/tmp`

Contains temporary files used by applications and processes.

### `/usr`

Contains many programs, libraries, and shared resources.

### `/dev`

Contains device files used to represent devices and system resources.

### `/boot`

Contains files needed during the boot process.

### `/root`

The home directory of the root user.

It is different from `/`.

- `/` = root of the filesystem
- `/root` = root user's home directory

## Linux Filesystem Structure

The basic structure is:

/
├── home
├── etc
├── var
├── tmp
├── usr
├── dev
├── boot
└── root

## Important Concepts

Linux uses one filesystem hierarchy starting from `/`.

Unlike Windows, Linux does not normally organize the filesystem using drive letters such as `C:\` or `D:\`.

The Linux filesystem is organized as a tree structure.

## Commands Practiced

I will practice exploring the important directories using:

`ls /`

`ls /home`

`ls /etc`

`ls /var`

`ls /tmp`

`ls /usr`

`ls /dev`

`ls /boot`

`ls /root`

I will also use:

`du -sh /home`

`df -h`

to understand disk usage and filesystem space.

## Practice

I learned the purpose of important Linux directories and will explore them using the terminal without modifying system files.

## Day 4 Progress

I learned the Linux filesystem hierarchy and the purpose of important system directories.
