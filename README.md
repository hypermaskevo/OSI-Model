# OSI-Model
This repository contains a Cisco Packet Tracer project designed to help users understand and analyze the OSI model using simulation mode. The network topology demonstrates the flow of data and how different layers of the OSI model are used in practice.
![image](https://github.com/user-attachments/assets/6b4db77f-a8df-4777-9db8-42729d236444)
## 📁 File

- `Lab++OSI+Model.pkt` – Cisco Packet Tracer file with configured topology.

## 🧪 Objectives

1. Use **Simulation Mode** to analyze the various traffic sent throughout the network.
   - Identify which **OSI layers** are active during each step.
   - Track protocols such as ARP, DHCP, ICMP, TCP, and HTTP.

2. **Release and renew** PC1's IP address to generate DHCP Layer 7 traffic.
   - Observe and analyze how DHCP messages move through the layers.

## 🖥️ Network Topology Overview

- **Devices:**
  - PC1
  - SRV1 (Server)
  - SW2 (Switch)
  - R1, R2 (Routers)

- **Subnets:**
  - `192.168.1.0/24`
  - `10.0.0.0/24`

- **Connections:**
  - PC1 ↔ SW2 ↔ R1 ↔ R2
  - SRV1 ↔ SW2

## 🧩 OSI Model Analysis Tips

- Use filters in simulation mode to analyze specific protocols (e.g., DHCP, HTTP, TCP).
- Watch packet behavior as it traverses switches, routers, and the server.
- Focus on headers and encapsulation at each OSI layer.

## 🔧 How to Use

1. Open the `.pkt` file in Cisco Packet Tracer.
2. Switch to **Simulation Mode**.
3. Click on `PC1` > Desktop > IP Configuration → Click "DHCP".
4. Analyze the packet flow in the simulation event list.
5. Use filters to isolate layers or protocols.

## 📚 Learning Outcomes

- Understand how data travels across a network.
- Learn practical usage of each OSI layer.
- Develop analysis skills for real-world network troubleshooting.

---

✅ Built with [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)
