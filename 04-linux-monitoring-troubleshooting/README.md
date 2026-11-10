# Lab 04: Linux System Monitoring & Troubleshooting

**Difficulty:** Basic to Intermediate  
**Environment:** Ubuntu Linux running in Oracle VirtualBox

## 1. Overview

This lab focused on monitoring a Linux system and investigating operational problems using built-in system administration tools.

The exercises involved inspecting system information, monitoring disk usage, reviewing system logs, identifying errors and investigating a stopped test service.

The objective was to develop a practical troubleshooting approach by identifying symptoms, examining available evidence, applying a fix and verifying the result.

## 2. Objectives

- Inspect basic Linux system information.
- Monitor available disk space and directory usage.
- Review system logs using journalctl and relevant log files.
- Identify errors and warnings in system logs.
- Investigate a stopped Linux test service.
- Determine the likely cause of a service failure.
- Apply a corrective action and verify that the system is functioning correctly.

## 3. Environment and Tools

- Operating system: Ubuntu Linux
- Virtualisation software: Oracle VirtualBox
- Interface: Linux Terminal
- Log management: systemd journal and Linux system logs
- Service management: systemd

## 4. System Information Inspection

Practised gathering basic information about the Linux machine to understand its current operating environment.

| Command | Purpose |
|---|---|
| `hostname` | Displays the system's hostname. |
| `uname -a` | Displays kernel and system information. |
| `uptime` | Displays how long the system has been running and its load averages. |

## 5. Disk Usage Monitoring

Practised checking available storage space and identifying how much disk space directories occupy.

| Command | Purpose |
|---|---|
| `df -h` | Displays filesystem disk usage in a human-readable format. |
| `du -sh` | Displays the total size of a specified directory in a human-readable format. |

These commands are useful when investigating storage-related problems, such as low disk space or directories consuming unexpected amounts of storage.

## 6. System Log Inspection

Practised inspecting Linux system logs to identify errors, warnings and information relevant to system operation.

| Command | Purpose |
|---|---|
| `journalctl` | Displays logs collected by the systemd journal. |
| `tail` | Displays the most recent lines of a file. |

System logs provide useful diagnostic information when investigating application failures, service problems and other operational issues.

## 7. Service Failure Investigation

A stopped test service was investigated as part of the practical exercise.

The investigation involved:

1. Identifying that the test service was not running.
2. Inspecting its status.
3. Reviewing relevant system logs for evidence of the failure.
4. Identifying the likely cause of the problem.
5. Applying a corrective action.
6. Checking the service again to verify that it was functioning correctly.

## 8. Troubleshooting Report

### Problem investigated

A test service was found to be stopped, requiring investigation to determine why it was not operating correctly.

### Symptoms

- The test service was not running as expected.
- Its service status indicated an operational problem.
- Relevant system logs were examined for additional information.

### Diagnostic commands

The investigation used Linux system administration tools, including:

| Command | Purpose |
|---|---|
| `systemctl status` | Checks the current state of the affected service. |
| `journalctl` | Reviews system logs for relevant errors and warnings. |

### Diagnosis

The service status and available log information were used to investigate the failure and determine its likely cause.

### Resolution

A corrective action was applied to address the identified service problem.

### Verification

The service was checked again after the corrective action to confirm that it was functioning correctly.

**Outcome:** The troubleshooting exercise demonstrated the process of identifying a service problem, investigating available diagnostic evidence, applying a fix and verifying the result.

## 9. Screenshots and Evidence

The following evidence supports the practical work completed:

- System information gathered using `hostname`, `uname -a` and `uptime`.
- Disk usage output from `df -h`.
- Directory size information from `du -sh`.
- Relevant system log entries showing errors or warnings.
- Evidence relating to the stopped test service.
- Service status after applying the corrective action.

Any sensitive information in log excerpts should be removed before publishing screenshots.

## 10. Skills Demonstrated

- Linux system information gathering.
- Disk space monitoring.
- Directory storage analysis.
- System log inspection.
- Error and warning identification.
- Service failure investigation.
- Evidence-based troubleshooting.
- Applying corrective actions and verifying results.

## 11. Conclusion

This lab provided practical experience with monitoring a Linux system and investigating operational problems.

It combined system information gathering, disk monitoring, log analysis and service troubleshooting to demonstrate a structured approach to identifying and resolving technical issues.

These skills are relevant to IT support, systems administration and cybersecurity environments, where monitoring systems, investigating errors and resolving technical problems are important responsibilities.
