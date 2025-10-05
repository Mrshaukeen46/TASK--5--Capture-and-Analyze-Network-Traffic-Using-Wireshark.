# TASK--5--Capture-and-Analyze-Network-Traffic-Using-Wireshark.
# 🧩 Task 5: Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective
To understand how network data is transmitted, identify various communication protocols, and analyze live network packets using Wireshark to detect patterns, troubleshoot issues, and enhance cybersecurity awareness.

---

## 🧠 Overview
Wireshark is a powerful open-source packet analyzer used for monitoring network traffic in real time. In this task, Wireshark was utilized to capture and analyze live network packets to observe how devices communicate within a network. The activity helped identify different protocols (such as TCP, UDP, ARP, and HTTP), recognize communication patterns, and understand how attackers might exploit insecure traffic.

---

## 🪜 Steps Performed
1. **Installed Wireshark**  
   Downloaded and installed Wireshark on the system from the official website.

2. **Selected Network Interface**  
   Chose the active network interface (e.g., Wi-Fi or Ethernet) to begin live packet capture.

3. **Captured Live Network Traffic**  
   Started capturing packets to monitor communication between devices in real time.

4. **Applied Display Filters**  
   Used filters such as `ip.addr == 192.168.1.102` or `tcp` to isolate relevant traffic for analysis.

5. **Analyzed Packet Details**  
   Examined each packet’s source and destination IPs, port numbers, and protocol layers to understand data flow.

6. **Identified Broadcast Traffic**  
   Observed communication between the source IP **192.168.1.102** and broadcast address **192.168.1.255**, identifying ARP and DHCP broadcasts.

7. **Saved and Exported Capture**  
   Exported the captured data as a `.pcap` file for documentation and further study.

---

## 🧰 Tools Used
- **Wireshark**  
- **Network Interface (Wi-Fi/Ethernet)**  
- **Local System / Virtual Machine**

---

## 📊 Key Learnings
- Gained hands-on experience in network traffic monitoring.  
- Learned to identify and interpret different protocols and packet structures.  
- Understood how Wireshark helps detect anomalies and potential threats in network communication.  
- Enhanced knowledge of packet flow, IP addressing, and protocol hierarchy.

---

## 🧠 Conclusion
This task provided a practical understanding of network analysis using Wireshark. By capturing and studying live packets, the importance of encryption, secure protocols, and traffic monitoring in cybersecurity was clearly demonstrated.

---

📅 **Task Completed:** Capture and Analyze Network Traffic Using Wireshark  
👤 **Internship:** Cybersecurity Fundamentals – Elevate Labs  
🏫 **Institution:** Albedo School of Business Education
