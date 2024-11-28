# 🌐 MITM Attack Practice

This repository demonstrates a **Man-in-the-Middle (MITM) attack** using **ARP poisoning** and **Wireshark** to capture HTTP credentials in a **controlled environment**. It's a great way to learn how attackers can intercept network traffic and potentially steal sensitive information. 🚨

## 🔧 Tools Used:
- **Kali Linux** 🐧
- **Wireshark** 🔍
- **Ettercap** 💻

## 📖 Setup Instructions:

### 1️⃣ **VM Setup**:
- **Kali Linux** as the **attacker**.
- **Windows VM** as the **victim**.

### 2️⃣ **Install Tools on Kali Linux**:
- Install **Ettercap**: For performing ARP poisoning and intercepting network traffic.
- Install **Wireshark**: For capturing and analyzing packets.

### 3️⃣ **Running ARP Poisoning with Ettercap**:
- Start **Ettercap** and run **ARP poisoning** on the victim (Windows VM).
- Ensure that the attacker (Kali) is in between the victim and the target (router) for successful interception.

### 4️⃣ **Capturing Packets with Wireshark**:
- Launch **Wireshark** and start capturing network packets.
- Filter for HTTP requests using `http.request.method == "POST"` or filter by IP to analyze the traffic.

## 📂 Files Included:
- **`Ettercap.conf`**: Configuration file for ARP poisoning.
- **`Wireshark.pcap`**: Captured network packets during the MITM attack.

## 🔑 License:
This project is licensed under the **MIT License**. Feel free to use and modify it!

---

### ✨ What you will learn:
- How ARP poisoning works in a local network.
- How attackers can sniff sensitive information like **login credentials**.
- How to use tools like **Ettercap** and **Wireshark** to perform **MITM attacks**.

### ⚠️ Disclaimer:
This project is for **ethical hacking practice** only. Always use it in a **controlled environment** and with permission. Misuse of this technique can lead to serious consequences. **Use responsibly.**

---

### 📲 Contact:
- Feel free to raise issues or questions related to this repo. I am happy to help!
