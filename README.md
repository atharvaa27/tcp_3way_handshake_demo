# TCP 3-Way Handshake Demo 🔗

This project demonstrates how the **TCP 3-way handshake** works by capturing and analyzing packets on an Ubuntu system using tools like `tcpdump` and/or `Wireshark`.

---

## 🔍 What is the TCP 3-Way Handshake?

The TCP 3-way handshake is the foundation of reliable connection establishment in the Transmission Control Protocol. It involves:

1. **SYN** – Client initiates a connection
2. **SYN-ACK** – Server acknowledges and replies
3. **ACK** – Client confirms the connection is open

---

## 🖥️ Tools Used

- Ubuntu Linux (22.04)
- `tcpdump`
- Basic terminal commands (`curl`, `netcat`, etc.)

---

## 🎯 Objective

To visually observe and understand the TCP handshake process:
- Capture raw packet data
- Analyze the SYN, SYN-ACK, ACK flow
- Optionally write automation or use filters

---

## 📸 Screenshots

_Screenshots_

- Example `tcpdump`:
  ```bash
  sudo tcpdump -i any tcp port 80 -n
