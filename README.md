# 📡 Monitor Network Traffic using Wireshark

A hands-on project to capture, analyze, and monitor network traffic using **Wireshark**, one of the most popular network protocol analyzers. This project demonstrates traffic monitoring, protocol filtering, and identifying potentially suspicious network activity.

---

## 📖 Table of Contents

- [📡 Overview](#-overview)
- [🎯 Objectives](#-objectives)
- [🛠️ Tools Used](#️-tools-used)
- [📑 Project Workflow](#-project-workflow)
- [📸 Screenshots](#-screenshots)
- [📊 Sample Captures](#-sample-captures)
- [📚 Learnings](#-learnings)
- [🔒 Disclaimer](#-disclaimer)

---

## 📡 Overview

Network traffic analysis is crucial for identifying performance bottlenecks, malicious activities, and misconfigurations. In this project, Wireshark is used to capture live network traffic and analyze packet details for HTTP, DNS, ARP, and ICMP protocols.

---

## 🎯 Objectives

- Install and configure Wireshark.
- Capture live network traffic.
- Apply display filters for specific protocols.
- Analyze captured packets in detail.
- Identify suspicious or abnormal network activities.
- Document findings and learnings.

---

## 🛠️ Tools Used

| Tool       | Purpose                       |
|------------|--------------------------------|
| **Wireshark** | Network traffic capture and analysis |
| **Windows 11 / Kali Linux** | Host OS for testing |
| **Chrome Browser** | For generating HTTP/HTTPS traffic |
| **Ping / Traceroute** | ICMP packet generation |

---

## 📑 Project Workflow

### 1️⃣ Install Wireshark
Download and install the latest Wireshark version from [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)

### 2️⃣ Capture Live Traffic
- Launch Wireshark.
- Select the active network interface (e.g., Ethernet, Wi-Fi).
- Click **Start Capturing Packets**.

### 3️⃣ Apply Display Filters
To focus on specific traffic:
- HTTP Traffic: `http`
- DNS Queries: `dns`
- ICMP (Ping): `icmp`
- ARP Packets: `arp`
- Traffic from specific IP: `ip.addr == 192.168.1.1`

### 4️⃣ Generate Sample Traffic
- Open browser and visit several websites.
- Use terminal:
  ```bash
  ping 8.8.8.8
  nslookup www.google.com
