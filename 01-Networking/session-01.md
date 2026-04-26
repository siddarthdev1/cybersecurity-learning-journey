# Session 01 – Networking Basics

## 📅 Date
26 April 2026

## ⏱️ Duration
1 Hour

## 🎯 Objective
Understand basic networking concepts and test connectivity

---

## 📚 Concepts Learned
- What is a computer network
- Basic idea of communication between devices
- Introduction to TCP/IP

---

## 💻 Practical Work
- Tested internet connectivity using ping
- Observed response time from server

---

## ⚙️ Commands Used
```bash
ping google.com
ipconfig


## 💻 Practical Work

## 🧠 Key Observations from Ping Test

- System successfully communicated with Google's server using IPv6 address (2404:6800:4009:825::200e)
- No packet loss observed → stable network connection
- Average latency ~97ms (min: 92ms, max: 110ms)
- ICMP protocol used for communication (ping)

---

## 📄 Raw Output

```bash
Pinging google.com [2404:6800:4009:825::200e] with 32 bytes of data:
Reply from 2404:6800:4009:825::200e: time=92ms 
Reply from 2404:6800:4009:825::200e: time=94ms 
Reply from 2404:6800:4009:825::200e: time=94ms 
Reply from 2404:6800:4009:825::200e: time=110ms 

Packets: Sent = 4, Received = 4, Lost = 0 (0% loss)
Minimum = 92ms, Maximum = 110ms, Average = 97ms

## 📌 What I Learned

- My system is using IPv6 instead of IPv4 for this request
- Latency varies between packets depending on network conditions
- Packet loss is critical for determining network reliability (0% = good)