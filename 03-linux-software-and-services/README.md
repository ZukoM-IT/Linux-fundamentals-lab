# Lab 03: Linux Software Installation & Service Management

**Difficulty:** Beginner to Intermediate  
**Environment:** Ubuntu Linux running in Oracle VirtualBox

## Overview

This lab focused on software package management, process monitoring and basic Linux service management.

The exercises provided practical experience with updating Ubuntu packages, installing software through the terminal, inspecting running processes and checking the status of system services.

## Objectives

- Understand basic Linux package management.
- Update Ubuntu package lists and installed software.
- Install software using the APT package manager.
- Inspect running processes.
- Search for specific processes.
- Check the status of Linux services.

## Environment

- Operating system: Ubuntu Linux
- Virtualisation software: Oracle VirtualBox
- Interface: Linux Terminal
- Package manager: APT
- Service management: systemd

## Practical Exercises

### 1. Package Management

Practised updating Ubuntu package lists, upgrading installed packages and installing software through the terminal.

| Command | Purpose |
|---|---|
| `sudo apt update` | Refreshes the local package lists. |
| `sudo apt upgrade` | Upgrades installed packages where updates are available. |
| `sudo apt install` | Installs software packages from configured repositories. |

### 2. Process Management

Practised viewing running processes and searching for specific processes.

| Command | Purpose |
|---|---|
| `ps` | Displays information about running processes. |
| `top` | Provides a live view of running processes and system resource usage. |
| `pgrep` | Searches for processes by name or other matching criteria. |
| `ps aux` | Displays a detailed list of running processes. |

### 3. Linux Service Management

Practised checking the status of Linux services using systemd.

| Command | Purpose |
|---|---|
| `systemctl status` | Displays the current status of a specified service. |

## Testing and Verification

The exercises were performed in the Ubuntu terminal.

The following activities were completed:

- Updated Ubuntu package lists.
- Upgraded installed software packages.
- Installed software using APT.
- Viewed running processes.
- Searched for specific running processes.
- Checked the status of Linux services.

## Skills Practised

- Ubuntu package management.
- Software installation and system updates.
- Linux process inspection.
- Process identification.
- Basic systemd service monitoring.
- Linux command-line administration.

## Conclusion

This lab provided practical experience with managing software packages, inspecting running processes and checking Linux service status.

These skills are relevant to IT support and junior system administration, particularly when maintaining software, monitoring system activity and investigating service availability.
