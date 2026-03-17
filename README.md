# LimanMYS2.0 — Server Setup & Management Script

> Parameter-based shell script for Liman MYS 2.0 server installation, removal, and reset operations.

[![Language](https://img.shields.io/badge/language-Bash-4EAA25)](https://www.gnu.org/software/bash/)
[![Platform](https://img.shields.io/badge/platform-Linux-FCC624)](https://www.linux.org/)
[![License](https://img.shields.io/badge/license-open%20source-green)](#)

---

## Overview

LimanMYS2.0 is a parameter-driven shell script that automates the installation, removal, and password reset operations for a Liman MYS 2.0 server environment. Each operation is handled as a named parameter, making the script simple to use and extend.

---

## Parameters

| Parameter | Description |
|-----------|-------------|
| `build`   | Initiates the Liman MYS 2.0 installation |
| `remove`  | Removes the existing Liman installation |
| `admin`   | Resets the admin password |
| `reset`   | Resets a user password |
| `help`    | Lists all available parameters and usage instructions |

If no parameter is provided, the script displays an error message and recommends running the `help` command.

---

## Requirements

- Bash shell environment
- A Linux distribution compatible with Liman MYS 2.0

---

## Usage

Grant execution permission and run:

```bash
chmod +x liman.sh
./liman.sh [parameter]
```

**Examples:**

```bash
./liman.sh build    # Start installation
./liman.sh admin    # Reset admin password
./liman.sh help     # Show usage information
```

After each operation, the script reports success or failure (e.g., `"PostgreSQL installed"` / `"installation failed"`).

---

## Project Info

- **Course:** Atatürk University — Open Source Software Development (Term Project)
- **Author:** [@mustafaceliker](https://github.com/mustafaceliker)
