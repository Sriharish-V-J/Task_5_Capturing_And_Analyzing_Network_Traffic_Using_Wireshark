# Task_5_Capturing_And_Analyzing_Network_Traffic_Using_Wireshark

## 🎯 Objective
To capture real-time network traffic and analyse common network protocols such as DNS, HTTP, and ICMP using Wireshark.

---

## 🛠 Tools Used
- Wireshark

---

## 📌 Steps To Be Followed (on Linux)

1. Install Wireshark.

   ```bash
   sudo apt install wireshark
   ```
   
2. Start Wireshark and select the active network interface.
   
3. Browse a website or ping a server to generate traffic.
  
4. Stop the capture after 1 minute.
   
5. Apply protocol filters like `dns`, `http`, and `icmp`.
   
7. Identifiable protocols:
   - **DNS**: Queries to resolve domain names.
   - **HTTP**: GET requests and server responses (unencrypted).
   - **ICMP**: Echo requests/replies via ping.

---

## 📂 Samples
- Packet Capture File: `Packet_Capture.pcapng`
  
---

## ✅ Outcome
The above task will help to observe how protocols work at a packet level. It gives insights into how data moves through the network and how different layers (transport, application) interact.

---
