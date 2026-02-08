---
title: "PyOS — Command-Line Operating System"
date: 2024-04-01
draft: false
description: "A modular command-line OS simulator with secure authentication and extensible commands"
tags: ["Python", "CLI", "Systems Programming"]
weight: 3
---

## Overview

PyOS is a fully-featured command-line operating system simulator built in Python. It provides a realistic shell experience with user authentication, colorful interface, and an extensible command system.

## 🔧 Tech Stack

- **Python** - Core language
- **Argparse** - Argument parsing
- **Custom Authentication** - Secure user management

## ✨ Key Features

### Secure Authentication
- **User registration and login** system
- **Password hashing** for security
- **Session management**

### Rich Shell Experience
- **Color-coded interface** for better readability
- **Command history** and navigation
- **Tab completion** support

### Extensible Architecture
- **Modular command system** - easily add new commands
- **Plugin architecture** for extensions
- **Minimal dependencies** for portability

## 🖥️ Available Commands

```bash
$ help          # Show available commands
$ ls            # List directory contents
$ cd            # Change directory
$ cat           # Display file contents
$ mkdir         # Create directory
$ touch         # Create file
$ rm            # Remove file/directory
$ clear         # Clear screen
$ exit          # Exit PyOS
```

## 🎨 Features Demo

```
╔══════════════════════════════════════╗
║           Welcome to PyOS            ║
║      A Python-based CLI OS           ║
╚══════════════════════════════════════╝

[kushagra@pyos ~]$ ls
Documents/  Downloads/  Projects/

[kushagra@pyos ~]$ cd Projects

[kushagra@pyos ~/Projects]$ _
```

## 🔗 Links

- [GitHub Repository](https://github.com/kushagra8881)
