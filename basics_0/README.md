# Networking Basics

This project is a deep dive into the fundamental concepts of computer networking, including the OSI model, types of networks, IP addressing, and basic network protocols such as TCP and UDP. The project also includes practical tasks to solidify your understanding of these concepts.

## Learning Objectives

By the end of this project, you should be able to explain the following concepts without the need for external resources:

- **OSI Model**
  - What it is and why it is important
  - The seven layers of the OSI model
  - How the OSI model is organized, from the physical layer (Layer 1) to the application layer (Layer 7)

- **Types of Networks**
  - **LAN (Local Area Network)**
    - Typical usage and geographical size
  - **WAN (Wide Area Network)**
    - Typical usage and geographical size
  - **Internet**
    - What it is and how it relates to LAN and WAN

- **IP Addressing**
  - What an IP address is and its function
  - The two types of IP addresses: **Private** and **Public**
  - The concept of **localhost**
  - What a **subnet** is and why it is important
  - The need for **IPv6** due to the limitations of IPv4

- **Network Protocols: TCP and UDP**
  - The two main data transfer protocols for IP
  - The key differences between **TCP** (Transmission Control Protocol) and **UDP** (User Datagram Protocol)
  - What a **port** is and common port numbers for services like SSH (22), HTTP (80), and HTTPS (443)

- **Network Tools and Protocols**
  - **Ping/ICMP**: How to use ping to check if a device is connected to a network
  - Use of commands like `netstat` and `ping` for network troubleshooting

## Project Tasks

### 0. OSI Model
Understand the OSI model, its layers, and how it is organized.

### 1. Types of Network
Identify different types of networks and their typical usage scenarios.

### 2. MAC and IP Address
Learn about MAC addresses and IP addresses, and understand their significance in networking.

### 3. TCP and UDP
Understand the differences between TCP and UDP, including their advantages and disadvantages.

### 4. TCP and UDP Ports
Create a Bash script to display listening TCP and UDP ports along with the associated process names.

### 5. Is the Host on the Network
Create a Bash script that pings a specified IP address to check if a device is online, and handle cases where no IP is provided.

## Requirements

- **General Requirements:**
  - Use allowed editors: `vi`, `vim`, `emacs`
  - All Bash scripts should be executable and pass shellcheck without errors
  - Bash scripts should start with `#!/usr/bin/env bash` and include a comment on the second line explaining the script’s function

- **Specific Requirements:**
  - Task-specific scripts to be stored in the `basics_0` directory
  - Use GitHub repository: `holbertonschool-network`

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/holbertonschool-network.git
