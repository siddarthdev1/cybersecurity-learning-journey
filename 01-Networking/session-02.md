# Session 02 – OSI Model

## 🎯 Objective
Understand OSI Model layers and map them to real-world networking

---

## 📚 Concepts Learned

### OSI Model (7 Layers – With Real Meaning)

1. Application  
   - User-facing services  
   - Protocols: HTTP, HTTPS, FTP, DNS  

2. Presentation  
   - Data formatting, encryption, compression  
   - Example: SSL/TLS (used in HTTPS)  

3. Session  
   - Maintains sessions between devices  
   - Example: Session handling in web apps  

4. Transport  
   - End-to-end delivery  
   - Protocols: TCP (reliable), UDP (fast)  
   - Handles ports (e.g., 80, 443)  

5. Network  
   - Logical addressing and routing  
   - Protocol: IP  
   - Devices: Routers  

6. Data Link  
   - Physical addressing (MAC)  
   - Error detection  
   - Devices: Switches  

7. Physical  
   - Actual transmission of bits  
   - Hardware: cables, NIC  

---

## 🧠 Real-World Mapping (How data actually moves)

Example: Opening a website (https://google.com)

1. Application → Browser sends HTTP request  
2. Presentation → Data encrypted using TLS  
3. Session → Session established between client and server  
4. Transport → TCP handshake (SYN, SYN-ACK, ACK)  
5. Network → IP routing to destination server  
6. Data Link → MAC address used in local network  
7. Physical → Bits sent through cable/WiFi  

---


### 1. Check IP Address

```
ipconfig

## 🧠 Key Observations (OSI + Commands)

- `ipconfig` shows IP configuration → relates to Network Layer (Layer 3)
- IPv4/IPv6 addresses are used for identifying devices across networks
- Default gateway represents routing path → also part of Network Layer
- `ping` uses ICMP protocol → operates at Network Layer
- OSI model helps map real commands to conceptual layers

---

## 📄 Raw Command Output

```
Windows IP Configuration

IPv4 Address. . . . . . . . . . . : 192.168.29.45
IPv6 Address. . . . . . . . . . . : 2404:6800:4009:825::200e
Default Gateway . . . . . . . . . : 192.168.29.1