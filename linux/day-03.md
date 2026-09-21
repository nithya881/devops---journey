# Day 3: Linux Distributions

## What I Learned

Today I learned what Linux distributions are, why different distributions exist, and the difference between the Linux kernel and a Linux distribution.

## Linux

Linux is a kernel and the core component of an operating system.

The Linux kernel manages resources such as:

- CPU
- Memory
- Hardware
- Processes
- Filesystems
- Devices

A usable operating system needs more than the kernel.

## Linux Distribution

A Linux distribution combines the Linux kernel with system tools, libraries, software, configuration, and package management to provide a complete usable operating system.

Examples:

- Ubuntu
- Debian
- Fedora
- RHEL
- Rocky Linux
- AlmaLinux

## Common Linux Distributions

### Ubuntu

Ubuntu is a Linux distribution based on Debian.

It is commonly used for:

- Development
- Cloud servers
- DevOps
- Docker
- Kubernetes

### Debian

Debian is a Linux distribution known for stability and community development.

Ubuntu is based on Debian.

### Fedora

Fedora is a Linux distribution sponsored by Red Hat and is known for adopting newer technologies.

### RHEL

RHEL stands for Red Hat Enterprise Linux.

It is an enterprise-focused Linux distribution.

### Rocky Linux and AlmaLinux

Rocky Linux and AlmaLinux are enterprise-oriented Linux distributions designed to be compatible with RHEL.

## Linux Distribution Families

### Debian Family

- Debian
- Ubuntu

### Red Hat Ecosystem

- RHEL
- Fedora
- Rocky Linux
- AlmaLinux

## Ubuntu LTS

LTS stands for Long Term Support.

LTS releases provide longer-term support and stability.

My system is running:

- Ubuntu 22.04.5 LTS
- Codename: Jammy

## Checking Linux Distribution Information

I practiced:

`cat /etc/os-release`

This shows information about the Linux distribution.

I also practiced:

`lsb_release -a`

This displays Linux distribution information such as the distributor, version, and codename.

## Checking Kernel Information

I practiced:

`uname -r`

This shows the Linux kernel version.

My kernel version is:

`6.18.33.2-microsoft-standard-WSL2`

## Ubuntu vs Linux Kernel

The Linux kernel is the core component that manages system resources.

Ubuntu is a complete Linux distribution built around the Linux kernel.

## WSL2

WSL2 stands for Windows Subsystem for Linux 2.

It allows me to run a Linux environment inside Windows without setting up a traditional separate virtual machine.

My setup is:

Windows
↓
WSL2
↓
Ubuntu 22.04.5 LTS
↓
Linux kernel

## Practice

I identified my Linux distribution, Ubuntu version, LTS status, codename, and kernel version using terminal commands.

## Day 3 Completed

I completed Linux distributions and practiced identifying my Ubuntu and Linux kernel information.
