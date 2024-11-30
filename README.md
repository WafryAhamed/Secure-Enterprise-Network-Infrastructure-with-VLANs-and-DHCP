# Secure-Enterprise-Network-Infrastructure-with-VLANs-and-DHCP


# Description  

**Secure-Enterprise-Network-Infrastructure-with-VLANs-and-DHCP** is a comprehensive network design and implementation project tailored for a mid-sized company. The project focuses on creating a secure and efficient network architecture using Cisco Packet Tracer. Key features include VLAN-based department separation, dynamic IP address allocation, robust firewall configurations, and internet connectivity to ensure seamless communication and security.

![image](https://github.com/user-attachments/assets/dad23662-7d31-4ba0-bb4c-6ad307f828fc)



---
# Network Components and Configuration:
VLANs and IP Addressing:

- **VLAN 10:**  User Department 1 - 192.168.10.0/24
- **VLAN 20:**  User Department 2 - 192.168.20.0/24
- **VLAN 30:**  User Department 3 - 192.168.30.0/24
- **VLAN 40:**  User Department 4 - 192.168.40.0/24
- **VLAN 50:**  Administrative Department - 192.168.50.0/24
- **VLAN 60:**  Academic Department 1 - 192.168.60.0/24
- **VLAN 70:**  Academic Department 2 - 192.168.70.0/24
- **VLAN 80:**  Academic Department 3 - 192.168.80.0/24
- **VLAN 90:**  Academic Department 4 - 192.168.90.0/24
- **VLAN 100:** Security and Emergency Response - 192.168.100.0/24

---

### Key Highlights:  
- **VLAN Configuration:** Logical separation of network traffic into 10 VLANs for user, administrative, academic, and security departments, ensuring enhanced security and streamlined management.  
- **Dynamic IP Allocation:** Setup of DHCP pools for each VLAN to automatically assign IP addresses, using the upper half of each VLAN's /24 subnet.  
- **Inter-VLAN Routing:** Implementation of router-on-a-stick for inter-VLAN communication, enabling efficient data exchange between departments.  
- **Firewall Setup:** Configured Access Control Lists (ACLs) on the router to restrict unauthorized access and secure network traffic.  
- **Internet Access:** Integration of a simulated cloud for internet connectivity, with a default route configured for external communication.  
- **Star Topology:** A centralized architecture connecting all VLANs through a central Layer 2 switch to a Layer 3 router for efficient traffic management.  

---

### Features and Benefits:  
1. **Security:** VLANs and firewalls ensure data integrity and prevent unauthorized access.  
2. **Scalability:** The architecture supports future expansions and upgrades.  
3. **Efficiency:** Dynamic IP assignment and centralized routing simplify network administration.  
4. **Connectivity:** Reliable internet access for all departments enhances productivity.  

---

### Learning Outcomes:  
- Design a secure and scalable enterprise network infrastructure.  
- Configure VLANs, DHCP, firewalls, and inter-VLAN routing.  
- Implement real-world networking practices using Cisco Packet Tracer.  

This project is an excellent demonstration of a secure, enterprise-grade network setup suitable for businesses aiming for reliable and secure IT infrastructure.

---
