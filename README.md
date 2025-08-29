# 🏠 SmartHome-Networking

#### 📌 Project Overview
This project simulates a **smart home network** using **Cisco Packet Tracer**.  
It demonstrates how IoT devices like **smart lights, thermostats, IP cameras, and PCs** communicate in a home network with proper **IP addressing** and **routing**.

#### ⚡ Features
- 💡 Smart devices connected to a central router
- 🌐 IP addresses configured for all devices
- 🛡️ VLANs (optional) to separate device types for security
- 📶 Internet access simulation for IoT devices
- 🧰 Network troubleshooting and simulation testing
- 🔗 Demonstrates device-to-device communication

#### 🖼️ Network Topology Diagram (ASCII Version)

          [Internet]
              |
          [Router]
              |
      -----------------
      |               |
   [Switch 1]      [Switch 2]
      |               |



> For a **visual diagram**, export your Packet Tracer file as an image (`File → Export → Image`) and include it in the `images/` folder.  
> Example: `images/smarthome-diagram.png`.

#### 🖥️ Device List

| Device Type       | Quantity | IP Address Range          | Description                       |
|------------------|----------|--------------------------|-----------------------------------|
| Router            | 1        | 192.168.1.1              | Central router connecting all devices |
| Switch            | 1-2      | N/A                      | Connects wired devices            |
| PC                | 3        | 192.168.1.2-192.168.1.4 | Computers for home users          |
| Smart Lights      | 2-3      | DHCP assigned            | Automated lighting devices        |
| IP Cameras        | 1-2      | DHCP assigned            | Home security cameras             |
| Thermostat        | 1        | DHCP assigned            | Smart temperature control device  |

#### 🗺️ IP Addressing Scheme
- **Router Gateway:** 192.168.1.1  
- **Subnet Mask:** 255.255.255.0  
- **DHCP Range:** 192.168.1.2 - 192.168.1.50  
- **VLANs (optional):**
  - VLAN 10: PCs
  - VLAN 20: Smart devices
  - VLAN 30: Security devices

#### 🚀 How to Use
1. Open **Cisco Packet Tracer**
2. Load the `.pkt` file in this repository
3. Observe network connectivity
4. Test communication between devices (ping, HTTP requests, etc.)
5. Modify IP addresses or devices to experiment with networking concepts

#### 🛠️ Tools Used
- Cisco Packet Tracer  
- Optional diagramming tools for exporting network images

#### ✍️ Author
**Shubham Kumar**  
🌐 [https://darkdev-sk.netlify.app/](https://darkdev-sk.netlify.app/)

