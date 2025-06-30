# 🛰️Wireshark Packet Capture & Analysis

## 🎯 Objective

To use **Wireshark** to capture live network traffic, apply protocol-based filters, analyze packet-level data, and identify any network protocols in use.

---

## 🛠 Tools & Environment

- **Tool Used**: Wireshark (GUI)
- **Operating System**: Windows 11
- **Network Interface**: Wi-Fi (Local connection)
- **Capture File Format**: `.pcapng`
- **Total Packets Captured**: ~6000+
- **Capture Duration**: 1–2 minutes

---

## 📸 Task Steps Performed

### ✅ Step 1: Installed Wireshark
Downloaded and installed the latest version of Wireshark along with **Npcap** for packet capture.

### ✅ Step 2: Started Packet Capture
- Opened Wireshark
- Selected the **Wi-Fi interface**
- Clicked the **Start Capture** button

### ✅ Step 3: Generated Network Traffic
- Opened a web browser
- Visited multiple sites (e.g., Google, YouTube)
- Used `ping google.com` from CMD to create ICMP traffic

### ✅ Step 4: Stopped and Saved the Capture
- Stopped capture after ~1.5 minutes
- Saved the file as `task5_capture.pcapng`

### ✅ Step 5: Applied Filters to Analyze Protocols
Used the following filters to inspect specific protocol traffic:

| Protocol     | Display Filter |
|--------------|----------------|
| TCP          | `tcp`          |
| DNS          | `dns`          |
| TLS (HTTPS)  | `tls`          |
| ICMP (Ping)  | `icmp`         |
| HTTP         | `http`         |

For each filter, relevant packets were observed (if present), and screenshots were taken.

### ✅ Step 6: Took Screenshots
Captured screenshots while filters were applied to show:
- Filtered packet list
- Packet details and hex output

Example files:
- `filter_tcp.png`
- `filter_dns.png`
- `filter_tls.png`

---

## 🔍 Protocols Identified

- **DNS**: Domain name lookups
- **TCP**: Core transport protocol for websites and services
- **TLS**: Encrypted HTTPS communication
- **UDP**: Protocol for DNS queries/response

---

## 📄 Files Included

| File Name                     | Description                                   |
|------------------------------|-----------------------------------------------|
| `task5_capture.pcapng`       | Complete packet capture file                  |
| `filter_tcp.png`             | Screenshot with TCP filter applied            |
| `filter_dns.png`             | Screenshot with DNS filter applied            |
| `filter_tls.png`             | Screenshot with TLS filter applied            |
| `filter_tls.png`             | Screenshot with TLS filter applied            |
| `README.md`                  | This documentation file                       |

---

## ✅ Outcome

This task demonstrates how to:
- Use Wireshark to capture and inspect real-time network packets
- Analyze traffic using filters for TCP, UDP, DNS, and TLS
- Save `.pcapng` files and report findings
- Understand how common protocols behave on the wire

---

