 Linux Fundamentals

## Introduction

Linux is a free and open-source operating system widely used in cybersecurity, ethical hacking, cloud computing, and server administration. Kali Linux is one of the most popular Linux distributions for penetration testing and security research.

---

## Linux File System

- `/` - Root directory
- `/home` - User home directories
- `/etc` - Configuration files
- `/bin` - Essential commands
- `/var` - Log and variable files
- `/tmp` - Temporary files

---

## Basic Linux Commands

| Command | Description |
|---------|-------------|
| pwd | Shows the current working directory |
| ls | Lists files and directories |
| cd | Changes directory |
| mkdir | Creates a new directory |
| touch | Creates a new file |
| cp | Copies files |
| mv | Moves or renames files |
| rm | Deletes files or directories |
| chmod | Changes file permissions |
| chown | Changes file ownership |

---

## Package Management

Update package list:

```bash
sudo apt update
```

Upgrade installed packages:

```bash
sudo apt upgrade
```

Install a package:

```bash
sudo apt install package_name
```

---

## Networking Commands

```bash
ip a
```

Displays network interface details.

```bash
ping google.com
```

Checks network connectivity.

```bash
netstat -tuln
```

Displays active network connections.

---

## Conclusion

Linux provides a powerful command-line environment that is essential for cybersecurity professionals. Learning Linux commands and file system navigation is the first step toward ethical hacking and penetration testing.
