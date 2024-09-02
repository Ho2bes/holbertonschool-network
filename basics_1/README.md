# Networking Basics Project

This project covers fundamental networking concepts and practical tasks using Bash scripts. The focus is on understanding network configuration, IP addresses, and basic networking tools.

## Learning Objectives

By the end of this project, you should be able to explain the following concepts:

### General Concepts
- **localhost/127.0.0.1**: What it is and its significance in networking.
- **0.0.0.0**: What it represents and how it differs from 127.0.0.1.
- **/etc/hosts**: The purpose of the hosts file and how to modify it.
- **Displaying active network interfaces**: How to use network tools to show your machine’s network interfaces.

### Specific Tools and Commands
- **ifconfig**: Displaying and configuring network interfaces.
- **telnet**: Connecting to remote hosts over TCP/IP networks.
- **nc (Netcat)**: A versatile networking tool for debugging and testing.
- **cut**: A command to extract sections from each line of files.

## Project Tasks

### 0. Change your home IP
**Objective**: Write a Bash script that configures an Ubuntu server with the following settings:
- `localhost` resolves to `127.0.0.2`.
- `facebook.com` resolves to `8.8.8.8`.

**File**: `0-change_your_home_IP`

**Example**:
```bash
ping localhost
ping facebook.com
