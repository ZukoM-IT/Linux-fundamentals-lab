# Lab 03: Linux Software Installation & Service Management

**Difficulty:** Beginner to Intermediate  
**Environment:** Ubuntu Linux running in Oracle VirtualBox

## 1. Overview

This lab focused on Linux software installation, package management, process monitoring and service administration.

The practical exercises involved installing software through the APT package manager, identifying running processes, managing system services and investigating a service failure using system diagnostic tools.

The purpose was to develop practical skills relevant to maintaining and troubleshooting Linux-based systems.

## 2. Objectives

- Update and manage software packages using APT.
- Install software through the Linux terminal.
- Identify and inspect running processes.
- Understand the difference between processes and services.
- Check and manage Linux services using systemd.
- Configure services to start automatically at boot where appropriate.
- Investigate service failures using status information and system logs.

## 3. Environment and Tools

- Operating system: Ubuntu Linux
- Virtualisation software: Oracle VirtualBox
- Interface: Linux Terminal
- Package manager: APT
- Service management: nginx

## 4. Software Installation and Package Management

Practised updating Ubuntu package lists, upgrading installed packages and installing software through the terminal.

| Command | Purpose |
|---|---|
| `sudo apt update` | Refreshes the local package lists. |
| `sudo apt install` | Installs software packages. |

Software installation was verified through the terminal.

## 5. Process Management

Practised inspecting running processes and searching for specific processes.

| Command | Purpose |
|---|---|
| `ps` | Displays information about running processes. |
| `top` | Provides a live view of processes and system resource usage. |

## 6. Linux Service Management

Practised inspecting and managing Linux services using systemctl.

| Command | Purpose |
|---|---|
| `systemctl status` | Displays the current status of a service. |
| `systemctl restart` | Restarts a service. |
| `systemctl start` | Starts a service. |

Service management exercises included checking service status, stopping and restarting a service, and verifying its operational state.

## 7. Testing and Verification

The following testing activities formed part of the lab:

- Demonstrated successful software installation.
- Identified running processes using Linux process inspection commands.
- Checked service status before and after stopping a service.
- Restarted a service and verified that it was running.
- Investigated a service failure using service status information and system logs.

## 8. Troubleshooting Report

A service failure was investigated as part of this exercise.

The troubleshooting process involved:

1. Checking the affected service's status using `systemctl status`.
2. Examining available system logs to investigate the failure.
3. Reviewing the information provided by the service status and logs to understand the reported problem.

This exercise demonstrated how Linux administrators can use service information and system logs to investigate problems rather than relying on guesswork.

**Troubleshooting outcome:** The service failure was investigated using status information and system logs.

## 9. Screenshots and Evidence

Practical evidence for this lab includes:

- Software installation commands and terminal output.
- Screenshots showing running process inspection.
- Service status before and after testing.
- Evidence of restarting the service.
- Service failure investigation using status information and logs.

## 10. Skills Demonstrated

- Linux package management using APT.
- Software installation and system updates.
- Process identification and monitoring.
- Understanding Linux processes and services.
- Service management using systemd.
- Service status verification.
- Basic Linux troubleshooting and log investigation.

## 11. Conclusion

This lab provided practical experience with software management, process inspection and Linux service administration.

It also introduced service troubleshooting through status checks and system log analysis.

These skills are relevant to IT support, technical operations and junior system administration roles, where maintaining software, monitoring processes and investigating service failures are important responsibilities.
