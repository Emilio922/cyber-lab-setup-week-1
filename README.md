# 🛡️ Cyber Lab Setup — Week 1

## 📌 Project Overview

This project focuses on setting up a **virtual cybersecurity and penetration-testing laboratory** using VMware Workstation, Kali Linux, and Metasploitable.

The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly.

The lab is designed to use isolated virtual machines so that Kali Linux can be used as the security-testing machine and Metasploitable can be used as an intentionally vulnerable target for authorized practice.

---

## 🎯 Objectives

The main objectives of this project are to:

- Install and configure VMware Workstation.
- Install and configure Kali Linux as a virtual machine.
- Install/import Metasploitable as a vulnerable target VM.
- Configure networking between the lab virtual machines.
- Verify connectivity between Kali Linux and Metasploitable.
- Document the laboratory setup.
- Prepare the environment for future cybersecurity projects.

---

## 🧪 Lab Environment

| Component | Role |
|---|---|
| **Kali Linux** | Security-testing / attacker VM |
| **Metasploitable** | Intentionally vulnerable target VM |
| **VMware Workstation** | Virtualization platform |

### Current Setup

- **Virtualization:** VMware Workstation
- **Security VM:** Kali Linux
- **Target VM:** Metasploitable
- **Lab type:** Controlled virtual cybersecurity laboratory

---

## 🖥️ Kali Linux Running

The following screenshot documents Kali Linux running successfully inside VMware:

![Kali Linux running](images/kali-linux-running.png)

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

⚠️ **Important:** This laboratory must only be used for systems that you own or have explicit permission to test. Metasploitable is intentionally vulnerable and should be kept inside the isolated lab environment.

---

## 📁 Repository Structure

```text
cyber-lab-setup-week-1/
├── README.md
├── images/
│   └── kali-linux-running.png
└── screenshots/
```

---

## 🚀 Next Steps

Future weeks can build on this environment by documenting:

1. VMware network configuration
2. Kali Linux IP configuration
3. Metasploitable IP configuration
4. Connectivity testing
5. Nmap reconnaissance
6. Service and port enumeration
7. Vulnerability identification
8. Controlled exploitation exercises
9. Findings and remediation notes

---

## 📚 Week 1 Status

**Status:** ✅ Initial lab setup documented

**Completed:**
- [x] Kali Linux downloaded
- [x] Kali Linux running in VMware
- [x] Metasploitable downloaded
- [x] Initial lab repository documentation created
- [ ] Virtual network configuration documented
- [ ] Kali ↔ Metasploitable connectivity documented
