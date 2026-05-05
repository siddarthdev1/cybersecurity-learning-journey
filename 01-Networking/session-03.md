# Session 03 – TCP/IP Model

## 🎯 Objective
Understand the TCP/IP model, compare it with the OSI model, and connect theory to practical networking commands.

---

## 📚 Concepts Learned

### TCP/IP Model (4 Layers)

1. **Application Layer**
   - Handles user-facing communication
   - Examples: HTTP, HTTPS, DNS

2. **Transport Layer**
   - End-to-end communication between devices
   - Protocols: TCP (reliable), UDP (fast)

3. **Internet Layer**
   - Logical addressing and routing
   - Protocols: IP, ICMP

4. **Network Access Layer**
   - Local network + physical transmission
   - Includes Wi-Fi, Ethernet, MAC

---

## 🔄 OSI vs TCP/IP Comparison

- OSI has 7 layers → conceptual framework
- TCP/IP has 4 layers → real-world implementation
- OSI improves structured understanding
- TCP/IP powers actual internet communication

---

## 💻 Practical Work

### Command 1 — Test Connectivity
```bash
ping google.com
```

**Output:**
```
Pinging google.com [2404:6800:4009:810::200e] with 32 bytes of data:
Reply from 2404:6800:4009:810::200e: time=92ms
Reply from 2404:6800:4009:810::200e: time=91ms
Reply from 2404:6800:4009:810::200e: time=96ms
Reply from 2404:6800:4009:810::200e: time=91ms

Ping statistics for 2404:6800:4009:810::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss)

Approximate round trip times in milli-seconds:
    Minimum = 91ms, Maximum = 96ms, Average = 92ms
```

### Command 2 — View Network Configuration
```bash
ipconfig
```

**Output:**
```
Wireless LAN adapter Wi-Fi:

Connection-specific DNS Suffix  . : lan
IPv6 Address. . . . . . . . . . . : 2409:40f2:2080:7e9:c9a5:6bf2:7f5:4284
Temporary IPv6 Address. . . . . . : 2409:40f2:2080:7e9:c4ab:4a0a:8e99:d477
Link-local IPv6 Address . . . . . : fe80::bac4:7aa4:8f70:4a2%19
IPv4 Address. . . . . . . . . . . : 192.168.31.206
Subnet Mask . . . . . . . . . . . : 255.255.255.0
Default Gateway . . . . . . . . . : 192.168.31.1
```