
# 🖥️ Windows 11 Wi-Fi Connectivity Troubleshooting

![Windows](https://img.shields.io/badge/Windows-11-0078D4?style=for-the-badge&logo=windows11&logoColor=white)
![Category](https://img.shields.io/badge/IT-Troubleshooting-00C896?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Resolved-brightgreen?style=for-the-badge)

---

## 📋 Project Overview

This case study documents my experience diagnosing and
resolving a Windows 11 wireless connectivity issue on
my personal laptop.

After a Windows update, the Wi-Fi option disappeared
from my computer, preventing me from connecting
to wireless networks.

I investigated the issue through Windows diagnostic
tools, driver troubleshooting, technical research,
and additional system configuration checks.

The problem was ultimately resolved by identifying
and re-enabling a disabled wireless network adapter.

---

## 💻 System Environment

| Component | Details |
|-----------|---------|
| Device | HP Pavilion Laptop |
| Operating System | Windows 11 |
| Wireless Adapter | Intel(R) Wi-Fi 6 AX201 |
| Issue | Missing Wi-Fi option |
| Resolution | Re-enabled disabled Wi-Fi adapter |

---

## 🔍 Problem Description

Following a Windows update, the Wi-Fi option
disappeared from my laptop's network settings.

### Symptoms

- Wi-Fi toggle was missing from Windows.
- Wireless network connections were unavailable.
- The wireless adapter was still visible in
  Device Manager.
- Restarting and reinstalling drivers did not
  restore wireless connectivity.

Although Windows detected the wireless hardware,
the Wi-Fi functionality remained unavailable.

---

## 🛠️ Troubleshooting Process

### Step 1: Investigating Device Manager

Opened Windows Device Manager to inspect the
installed network adapters.

Located the Intel(R) Wi-Fi 6 AX201 adapter.

**Finding:**

Windows detected the wireless adapter, indicating
that the device was recognized by the operating system.

However, Wi-Fi remained unavailable.

**Result:** Issue unresolved.

---

### Step 2: Wireless Driver Installation

Investigated whether the problem was related
to an outdated or malfunctioning wireless driver.

Installed an Intel wireless driver and
restarted the laptop.

**Result:**

The Wi-Fi option remained missing.

**Status:** Unsuccessful.

---

### Step 3: Driver Removal and Reinstallation

Attempted to resolve the issue by removing
the wireless adapter through Device Manager.

Actions performed:

1. Opened Device Manager.
2. Located the wireless network adapter.
3. Selected the option to uninstall the device.
4. Selected the driver removal option.
5. Restarted the laptop.
6. Checked Device Manager again.

**Result:**

The adapter reappeared in Device Manager,
but the Wi-Fi option was still unavailable.

**Status:** Unsuccessful.

---

### Step 4: Windows Network Reset

Attempted to restore network functionality
using Windows Network Reset.

After performing the reset, I restarted
the computer and checked whether Wi-Fi
was available.

**Result:**

The missing Wi-Fi option was not restored.

**Status:** Unsuccessful.

---

### Step 5: Technical Research

Continued investigating the issue using:

- Microsoft technical forums
- Online troubleshooting resources
- AI-assisted technical research
- Windows networking information

Explored additional possible causes and
troubleshooting methods.

I also considered Safe Mode troubleshooting
but avoided proceeding after encountering
a BitLocker-related warning.

This was an important consideration because
I wanted to avoid unnecessary risks to
my personal files and system configuration.

---

## ✅ Root Cause & Resolution

### Root Cause

The wireless network adapter was disabled
in Windows Network Connections.

Although the adapter was detected in
Device Manager, its disabled state prevented
Wi-Fi connectivity from being available.

### Resolution

The issue was resolved by accessing
Windows Network Connections and
re-enabling the wireless adapter.

**Steps performed:**

1. Pressed `Windows + R` to open Run.
2. Entered the following command:

   `ncpa.cpl`

3. Pressed Enter to open Network Connections.
4. Located the disabled Wi-Fi adapter.
5. Right-clicked the adapter.
6. Selected **Enable**.
7. Confirmed that the Wi-Fi option returned.

### Final Result

**Status: RESOLVED ✅**

Wireless connectivity was restored
after re-enabling the network adapter.

The resolution did not require additional
driver installation or hardware replacement.

---

## 🧠 Technical Explanation

Windows Device Manager and Network Connections
provide different ways to inspect and manage
networking components.

**Device Manager**

Displays installed hardware and associated
device drivers.

**Network Connections**

Displays network interfaces and allows
users to manage their connection status.

In this case, the wireless adapter was
detected by Windows but was disabled
in Network Connections.

Re-enabling the adapter restored
its functionality.

This demonstrated why checking both
hardware detection and network adapter
configuration is important during
connectivity troubleshooting.

---

## 📚 Skills Demonstrated

| Skill | Application |
|-------|-------------|
| Windows Troubleshooting | Investigated missing Wi-Fi functionality |
| Device Manager | Inspected wireless hardware and drivers |
| Driver Troubleshooting | Tested driver installation and removal |
| Network Configuration | Identified and enabled a disabled adapter |
| Technical Research | Investigated solutions using online resources |
| Problem-Solving | Evaluated multiple potential causes |
| Risk Awareness | Considered system security before advanced changes |

---

## 💡 Lessons Learned

### 1. Check Simple Solutions First

A disabled network adapter can cause
connectivity problems even when
Windows recognizes the hardware.

Checking adapter status early may help
avoid unnecessary troubleshooting.

### 2. Hardware Detection Does Not Guarantee Connectivity

An adapter appearing in Device Manager
does not necessarily mean that the
network connection is enabled.

### 3. Document Troubleshooting Results

Recording each attempted solution
helps identify which actions were
successful and which were not.

### 4. Research Is Part of Troubleshooting

Technical troubleshooting frequently
requires consulting documentation,
exploring potential causes,
and learning unfamiliar system components.

### 5. Consider System Risks

Advanced troubleshooting steps should
be evaluated carefully, especially when
they involve encryption, recovery settings,
or personal data.

---

## 🎯 Conclusion

This experience provided practical exposure
to Windows networking, driver management,
and troubleshooting techniques.

The issue initially appeared to involve
wireless drivers or a Windows update,
but the solution was ultimately found
within Windows Network Connections.

By using `ncpa.cpl` to locate and enable
the disabled wireless adapter, I was
able to restore Wi-Fi connectivity.

The experience reinforced the importance
of systematic investigation, technical
research, and understanding how different
Windows components interact.

---

<div align="center">

### 🔗 Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pramirez-tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pamela-ramirez12)

**Pamela Ramirez | Computer Science Undergraduate**

</div>
