# Module 02 – Linux, Networking & Cloud Infrastructure

## Overview
This module covers Linux administration, networking fundamentals, SSH configuration, and Linux server deployment using Ubuntu.

## 1. Linux CLI

| Command | Description |
|---|---|
| whoami | Displays current user |
| pwd | Shows current directory |
| ls -la | Lists all files and directories |
| cd | Changes directory |
| mkdir | Creates a directory |
| touch | Creates an empty file |
| cp | Copies files |
| mv | Moves or renames files |
| rm | Removes files |
| cat | Displays file content |

## 2. Files & Permissions

| Command | Description |
|---|---|
| chmod | Changes file permissions |
| chown | Changes file ownership |
| ls -l | Displays file permissions |
| stat | Shows file information |

## 3. Users & Groups

| Command | Description |
|---|---|
| whoami | Displays current user |
| id | Shows user and group IDs |
| groups | Lists user groups |
| adduser | Creates a user |
| groupadd | Creates a group |
| usermod | Modifies user accounts |

## 4. Processes & Services

| Command | Description |
|---|---|
| ps aux | Lists running processes |
| top | Monitors processes |
| kill | Sends a signal to a process |
| systemctl status | Checks service status |
| systemctl start | Starts a service |
| systemctl stop | Stops a service |
| systemctl enable | Enables automatic startup |

## 5. SSH Configuration

| Command | Description |
|---|---|
| ssh | Connects to a remote server |
| ssh-keygen | Generates SSH keys |
| ssh-keygen -l | Displays key fingerprint |
| ssh-keygen -t ed25519 | Generates an Ed25519 key pair |

## 6. Networking

| Command | Description |
|---|---|
| ip addr | Displays IP addresses |
| ip route | Displays routing information |
| ping | Tests network connectivity |
| ss -tuln | Lists listening ports |
| nslookup | Checks DNS information |
| hostname | Displays system hostname |
| ufw status | Checks firewall status |

## 7. Linux Server Deployment

A local Linux web server was deployed using Ubuntu 24.04 LTS and Nginx.

### Steps Performed

1. Create a Virtual Machine using VMware.
2. Configure Ubuntu 24.04 LTS and update the system.
3. Enable SSH access and generate an Ed25519 SSH key pair.
4. Check network configuration, DNS resolution, listening ports, and firewall status.
5. Install and start the Nginx web server.
6. Create a custom HTML page at `/var/www/html/index.html`.
7. Test the web server using `curl http://localhost`.

### Deployment Result

Successfully deployed a local Nginx web server on Ubuntu and verified its functionality using a custom HTML page.

## Practical Environment

- Operating System: Ubuntu 24.04 LTS
- Virtualization: VMware
- Web Server: Nginx
- Access Protocol: SSH
- Platform: Linux Terminal

## Screenshots

Practical screenshots are stored in the Screenshots directory.

## Progress

Status: Completed
