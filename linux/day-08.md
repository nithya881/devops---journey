
# Day 8: User and Group Management in Linux

## What I Learned

Today I started Week 2 of my 32-week DevOps roadmap. I learned about Linux users, groups, and commands used to inspect user accounts and group memberships.

## Key Concepts

### 1. Users

A user represents an account on a Linux system. Each user has a username and a unique User ID (UID).

### 2. Groups

A group is a collection of users used to manage access and permissions. A user can belong to multiple groups.

### 3. Root User

The root user is the superuser account with extensive administrative privileges. Administrative commands should be used carefully.

## Commands Practiced

### 1. whoami

Displays the username of the current user.

```bash
whoami
```

### 2. id

Displays the current user's UID, primary GID, and group memberships.

```bash
id
```

### 3. groups

Displays the groups the current user belongs to.

```bash
groups
```

### 4. who

Displays users currently logged in to the system.

```bash
who
```

### 5. getent passwd

Retrieves user account entries from the system's configured account database.

```bash
getent passwd
getent passwd | head
```

### 6. getent group

Retrieves group entries from the system's configured group database.

```bash
getent group
getent group sudo
```

## Practical Work

- Checked my current username using `whoami`.
- Inspected my UID, GID, and group memberships using `id`.
- Listed my group memberships using `groups`.
- Checked logged-in sessions using `who`.
- Inspected user accounts using `getent passwd`.
- Inspected group information using `getent group`.

## Important Takeaways

- UID means User ID.
- GID means Group ID.
- A user can belong to multiple groups.
- The root account has extensive administrative privileges.
- The `groups` command displays the current user's group memberships.
- Linux includes both regular user accounts and system accounts.

## Safety Note

User and group management commands can change system access. Practice administrative changes only on a Linux machine where you have permission.

## Day 8 Completed

Completed introductory user and group inspection exercises as part of my DevOps learning journey.

Next: Continue Week 2 according to the roadmap.
