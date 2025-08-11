# Task 5 – Network Traffic Capture and Protocol Analysis using Wireshark

## 📌 Objective
Capture live network traffic, identify common protocols, and document findings using Wireshark.

## 🛠 Tool Used
- **Wireshark** – Network protocol analyzer

## 📂 Steps Performed

### 1️⃣ Install Wireshark
- Download from [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)
- Install with default settings
- For Windows, install **Npcap** when prompted

### 2️⃣ Start Wireshark
- Open Wireshark
- Select your active network interface (Wi-Fi/Ethernet)

### 3️⃣ Capture Packets
- Double-click the interface to start capture
- Generate traffic (visit websites or run `ping google.com`)

### 4️⃣ Stop and Filter
- Stop capture after 1–2 minutes
- Apply filters such as:

### 5️⃣ Save Capture
- Go to **File → Save As**
- Save file as `task5_capture.pcap`

## 📊 Findings
- **HTTP** – Web requests and responses
- **DNS** – Domain name to IP resolution
- **TCP** – Reliable connection management

## 📄 Report
A detailed report (`Prepare Short Report.docx`) is included in this repository with:
- Step-by-step process
- Protocol screenshots
- Observations and conclusion
