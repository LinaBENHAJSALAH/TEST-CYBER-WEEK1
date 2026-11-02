# 🔐 Week 1: Kali Linux Installation and Configuration

**Project:** Cybersecurity Internship – Practical Tasks  
**Task:** Week 1 – Kali Linux Installation and Configuration  
**Environment:** Ubuntu Linux + Oracle VirtualBox + Kali Linux  
**Category:** Cybersecurity / Virtualization / Linux

---

## 📌 1. Project Overview

This task focuses on setting up a Kali Linux virtual machine using Oracle VirtualBox on an Ubuntu host system.

Kali Linux is a Debian-based Linux distribution designed for cybersecurity professionals, penetration testers, and security researchers.

The purpose of this task is to prepare a working cybersecurity environment that will be used for future practical exercises, including networking, reconnaissance, vulnerability assessment, and penetration testing.

---

## 🎯 2. Objectives

The main objectives of this task are:

- Install and configure Oracle VirtualBox.
- Download the official Kali Linux virtual machine.
- Import Kali Linux into Oracle VirtualBox.
- Configure the virtual machine's hardware resources.
- Start Kali Linux successfully.
- Verify the operating system and basic system information.
- Prepare the environment for future cybersecurity exercises.
- Document the installation process with screenshots.

---

## 💻 3. System Specifications

| Component | Configuration |
|---|---|
| Host Operating System | Ubuntu Linux |
| Virtualization Software | Oracle VirtualBox |
| Virtualization Version | 7.2 |
| Guest Operating System | Kali Linux |
| Architecture | 64-bit |
| Host RAM | 8 GB |
| Virtual Machine | Kali Linux |
| Network Adapter | [Your actual configuration] |

*Note: The virtual machine's allocated RAM, CPU, and network configuration should reflect the actual VirtualBox settings.*

---

## ⚙️ 4. Implementation Procedure

### Step 1: Install Oracle VirtualBox

Oracle VirtualBox was installed on the Ubuntu host system to provide a virtualization environment.

Official download:
https://www.virtualbox.org/wiki/Downloads

### Step 2: Download Kali Linux

The official Kali Linux virtual machine image was downloaded from the Kali Linux website.

Official download:
https://www.kali.org/get-kali/

The prebuilt VirtualBox image was selected to simplify the installation process.

### Step 3: Import Kali Linux into VirtualBox

The downloaded Kali Linux virtual machine was imported into Oracle VirtualBox.

The virtual machine configuration was reviewed, including:

- RAM allocation.
- CPU allocation.
- Virtual disk configuration.
- Network adapter settings.

### Step 4: Start and Configure Kali Linux

The Kali Linux virtual machine was started through Oracle VirtualBox.

After startup, the operating system environment was checked to ensure that the virtual machine was ready for use.

### Step 5: Verify the Installation

The following commands can be used to verify the Kali Linux environment:

**Check the operating system:**

```bash
cat /etc/os-release
```

**Check the kernel version:**

```bash
uname -r
```

**Check system architecture:**

```bash
uname -m
```

**Check IP address and network interfaces:**

```bash
ip -br addr
```

**Check available disk space:**

```bash
df -h
```

These commands help confirm the operating system installation and inspect the basic system configuration.

---

## 📸 5. Installation Evidence

The following screenshots document the Kali Linux installation and configuration process.

### Screenshot 1: Kali Linux Virtual Machine in VirtualBox

![VirtualBox Kali VM](screenshots/01-virtualbox-kali-vm.png)

**Description:** Shows the Kali Linux virtual machine registered in Oracle VirtualBox and its configuration.

### Screenshot 2: Kali Linux Desktop Environment

![Kali Linux Desktop](screenshots/02-kali-desktop.png)

**Description:** Shows the Kali Linux desktop after successfully starting the virtual machine.

### Screenshot 3: Kali Linux Terminal Verification

![Kali Linux Terminal](screenshots/03-kali-terminal-verification.png)

**Description:** Shows terminal commands used to verify the operating system, kernel version, architecture, and network configuration.

---

## 🧠 6. What I Learned

During this task, I gained practical experience with:

1. **Virtualization:** Understanding how virtual machines operate independently from the host operating system.
2. **Oracle VirtualBox:** Creating, importing, and managing virtual machines.
3. **Kali Linux:** Understanding the Linux environment used for cybersecurity activities.
4. **System Configuration:** Managing virtual machine resources such as RAM, CPU, and storage.
5. **Linux Commands:** Using terminal commands to inspect system information and network interfaces.
6. **Cybersecurity Environment:** Preparing a dedicated environment for future security testing and practical exercises.

---

## 🔐 7. Security and Ethical Considerations

Kali Linux will be used strictly for educational purposes and authorized cybersecurity testing.

- Perform security testing only on systems that I own or have explicit permission to assess.
- Use controlled laboratory environments for penetration testing exercises.
- Keep the operating system and security tools updated.
- Avoid testing against unauthorized networks or systems.

---

## 🚀 8. Future Improvements

The following activities may be performed in future tasks:

- Explore Kali Linux security tools.
- Practice Linux commands and system administration.
- Learn network reconnaissance using Nmap.
- Analyze network traffic using Wireshark.
- Practice vulnerability assessment in controlled environments.
- Build a dedicated penetration testing laboratory.

---

## 📚 9. References

- [Kali Linux Official Website](https://www.kali.org/)
- [Kali Linux Documentation](https://www.kali.org/docs/)
- [Oracle VirtualBox](https://www.virtualbox.org/)
- [VirtualBox User Manual](https://www.virtualbox.org/manual/)

---

## 👤 10. Task Information

| Field | Details |
|---|---|
| Internship Task | Week 1 |
| Task Name | Kali Linux Installation and Configuration |
| Host OS | Ubuntu Linux |
| Virtualization | Oracle VirtualBox |
| Guest OS | Kali Linux |
| Evidence | 3 Screenshots |
| Repository | GitHub |

**Status:** [Completed / In Progress]

---

*This repository documents the installation and initial configuration of Kali Linux as part of the cybersecurity internship.*
