<div align="center">

## 🔐 Cybersecurity Home Lab — Kali Linux & VirtualBox

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>
<p align="center">

---

![Kali Linux](https://img.shields.io/badge/Kali%20Linux-Cybersecurity-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-Virtualization-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Learning-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Lab-red?style=for-the-badge)

---

<div align="center">
<img src="https://img.shields.io/badge/%20BY-C00000?style=flat-square" /> <br>
  <img src="https://img.shields.io/badge/Usman%20Umar Idris%20Ethical Hacker-C00000?style=flat-square" />
</p>
</div>
---
## 📌 Project Overview

This project focuses on setting up a **virtual cybersecurity and penetration-testing laboratory** using VirtualBox and Kali Linux.

The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly.

The lab is configured on a private virtual network so that additional machines can be added later and used as targets for authorized security testing.

---


## 🎯 Objectives

The main objectives of this project are to:

- Install and configure VirtualBox.
- Install/import Kali Linux as a virtual machine.
- Create a private **NAT Network** for the cybersecurity lab.
- Configure network connectivity for Kali Linux.
- Assign a consistent IP address to the Kali VM.
- Verify network connectivity and DNS resolution.
- Take a clean VM snapshot for recovery.
- Document the complete setup process.
- Prepare the environment for future cybersecurity projects.

---

## 🛡️ Purpose of the Lab

The lab provides an isolated and controlled environment for cybersecurity learning and authorized security testing.

It can be used for activities such as:

- Network reconnaissance
- Port scanning
- Vulnerability assessment
- Packet analysis
- Web security testing
- Exploitation practice
- Security-tool experimentation

>⚠️ **Important:** This laboratory must only be used for systems that you own or have explicit permission to test. Do not use the lab or its tools to attack unauthorized systems.

---
## 🏗️ Lab Architecture

![](1-screenshot-title-image.png)


Additional target machines can be added to the same virtual network in future projects.

---

## ⚙️ Lab Configuration

| 🧩 Component       | ⚙️ Configuration   |
| ------------------ | ------------------  |
| 🖥️ Host OS         | Windows 10         |
| 🧠 Host RAM        | 8 GB               |
| ⚡ Processor       | Intel Core i7      |
| 🧰 Hypervisor      | VirtualBox 7.2  |
| 🐉 Security OS     | Kali Linux 2026.2  |
| 🧠 Kali RAM        | 2048 MB            |
| 🌐 Virtual Network | NAT Network        |
| 📡 Network Address | 10.0.0.0/24        |
| 🐧 Kali IP Address | 10.0.0.2/24        |
| 🚪 Default Gateway | 10.0.0.1           |
| 🌍 DNS Server      | 8.8.8.8            |
| 🔮 Future VM Range | 10.0.0.3–10.0.0.99 |

---

# 🪜 Lab Setup Procedure

## Step 1. Install 7-Zip

7-Zip was installed to extract the Kali Linux virtual-machine package, which may be distributed as a `.7z` archive.






# 🔐 Cybersecurity Home Lab — Kali Linux & VirtualBox

> A personal, isolated cybersecurity laboratory built with **Kali Linux** and **Oracle VirtualBox** for learning Linux, networking, system administration, and authorized security testing.


---

## 📌 Project Overview

This project documents the setup of a personal cybersecurity laboratory using **Kali Linux** running inside **Oracle VirtualBox**.

The purpose of the lab is to provide a controlled environment where I can safely learn and practice cybersecurity concepts without affecting real-world systems.

The laboratory will serve as a foundation for future practical work involving:

- 🐧 Linux administration
- 🌐 Networking
- 🔎 Network reconnaissance
- 🛡️ Security testing
- 🔐 Cybersecurity tools
- 📡 Network analysis
- 🧪 Security experimentation
- 💻 Virtualization
- 📚 Hands-on cybersecurity learning

> **Important:** All security testing performed in this laboratory is intended for systems that I own or have explicit permission to test.

---

# 🎯 Objectives

The main objectives of this project are to:

- Set up Oracle VirtualBox as the virtualization platform.
- Install and configure Kali Linux as a virtual machine.
- Understand the relationship between the host OS and guest OS.
- Configure the Kali Linux virtual machine.
- Understand virtual networking.
- Test network connectivity from Kali Linux.
- Learn basic Linux commands and administration.
- Create snapshots for safe experimentation and recovery.
- Build a foundation for future cybersecurity labs.
- Document the setup and troubleshooting process.

---

# 🏗️ Lab Architecture

The current laboratory consists of:

```text
┌─────────────────────────────────────────────┐
│              HOST COMPUTER                  │
│                                             │
│                Windows OS                   │
│                     │                       │
│              Oracle VirtualBox              │
│                     │                       │
│              ┌──────▼──────┐                │
│              │ Kali Linux  │                │
│              │     VM      │                │
│              └──────┬──────┘                │
│                     │                       │
│              Virtual Network                │
│                     │                       │
│          Future Lab Machines                │
│          (Targets / Servers)                │
│                                             │
└─────────────────────────────────────────────┘
