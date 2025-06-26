
# 📶 Monitor Network Traffic using Wireshark

A practical network traffic monitoring project leveraging **Wireshark**, one of the most powerful open-source network protocol analyzers. This project demonstrates capturing, analyzing, and interpreting network packets in a controlled environment for cybersecurity monitoring and troubleshooting.

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

In this project, I utilized **Wireshark** to capture and analyze real-time network traffic. The primary focus was on identifying different protocols, examining packet structures, filtering specific traffic types, and detecting potential anomalies or suspicious behavior in a network environment.

---

## 🎯 Objectives

- Set up **Wireshark** for packet capturing.
- Monitor and capture real-time network traffic.
- Apply filters to isolate specific protocols (HTTP, DNS, ARP, TCP, etc.).
- Analyze captured packet data for insights and anomalies.
- Understand packet structures, headers, and payloads.
- Document findings and observations.

---

## 🛠️ Tools Used

| Tool       | Purpose                            |
|------------|-------------------------------------|
| **Wireshark** | Network packet capture and analysis |
| **Kali Linux / Windows 11** | Test environment |
| **Chrome/Firefox** | Generate HTTP/DNS traffic |
| **Command Prompt / Terminal** | Test with `ping`, `tracert`, etc. |

---

## 📑 Project Workflow

1. **Install Wireshark**  
   Download and install Wireshark from the official website.

2. **Select Network Interface**  
   Choose the active network interface to capture traffic.

3. **Start Packet Capture**  
   Begin capturing live traffic on the selected interface.

4. **Generate Traffic**  
   - Open websites.
   - Perform DNS lookups.
   - Use `ping` and `tracert` commands.
   - Download files to generate HTTP and TCP traffic.

5. **Apply Filters**  
   Example filters:
   - `http`
   - `dns`
   - `icmp`
   - `tcp.port == 80`
   - `ip.addr == <target IP>`

6. **Analyze Packets**  
   Examine packet details:
   - Source and destination addresses
   - Protocol information
   - Header values and payload data

7. **Save and Export Captures**  
   Save `.pcapng` files for documentation and future analysis.

8. **Document Observations**  
   Note protocol behaviors, response times, anomalies, and unusual traffic patterns.

---

## 📸 Screenshots

| Description                     | Screenshot |
|:---------------------------------|:------------|
| Applied DNS Filter               | ![DNS Filter](https://github.com/user-attachments/assets/20b6d463-db8a-42cf-b3df-750d7b01bf32) |
| Applied HTTP Filter              | ![HTTP Filter](https://github.com/user-attachments/assets/809a2b0b-9664-479c-ac93-28152f9dbb26) |
| Packet Detail Pane View          | ![Packet Details pane view](https://github.com/user-attachments/assets/b86fc46f-3615-4ef6-99a4-1a8114dacc88) |
| SYN flag set, indicating thestart of a new TCP connection    | ![SYN FLAG SET](https://github.com/user-attachments/assets/fa7f535d-8563-4c42-b26c-30a2c1985f80) |    
| Applied Tcp Filter               | ![Tcp Filter](https://github.com/user-attachments/assets/e7b1eae9-a0d4-4231-ac9e-cc78eadc5b68) |
| TCP Analysis Flags               | ![TCP Analysis Flags](https://github.com/user-attachments/assets/01a78dd4-31d3-46be-9556-2f4cf863cf07) | 
 
*(Replace placeholders with actual images in your project repo)*

---

## 📊 Sample Captures

- **HTTP Request and Response**
- **DNS Query for Domain Name Resolution**
- **ICMP Echo Request (Ping)**
- **TCP 3-Way Handshake**

*Captured `.pcapng` files are available in the `captures/` folder.*

---

## 📚 Learnings

- Familiarity with **Wireshark’s interface** and key functionalities.
- Practical understanding of **common network protocols** (TCP, UDP, HTTP, DNS, ARP).
- Techniques to **apply filters and isolate specific traffic**.
- Ability to **interpret packet structures** and headers.
- Recognition of **potential network anomalies and irregular traffic patterns**.

