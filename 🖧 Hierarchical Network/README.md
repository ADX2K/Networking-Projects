# 🖧 **Hierarchical Network Design with VLAN Segmentation & Advanced Security**

## 📝 **Project Overview**
Welcome to the **Hierarchical Network Design** project! 🎉 In this project, I’ve designed a robust **three-layer hierarchical network** with **advanced security configurations** and **network segmentation** for optimal performance and security. The network incorporates **VLANs** (Virtual LANs), **Router-on-a-Stick** inter-VLAN routing, **EtherChannel (LACP)**, and **security features** like **SSH**, **Port Security**, and **Rapid Spanning Tree Protocol (RSTP)** to ensure a reliable and secure networking environment.

## 💡 **Key Features**

### **🌟 VLAN Segmentation**
Logical separation of network traffic is done using VLANs for **management**, **data**, and **voice** traffic. Here's how the VLANs are structured:
- **VLAN 10** – Block-A/Equipe-1 (Data VLAN)
- **VLAN 20** – Block-A/Equipe-2 (Data VLAN)
- **VLAN 30** – Block-A/Equipe-3 (Data VLAN)
- **VLAN 40** – Block-B/Equipe-1 (Data VLAN)
- **VLAN 50** – Block-B/Equipe-2 (Data VLAN)
- **VLAN 60** – Block-B/Equipe-3 (Data VLAN)
- **VLAN 99** – Gestion (Management VLAN)
- **VLAN 100** – Voix (Voice VLAN)

### **🔧 Advanced Network Configurations**
- **VTP (VLAN Trunking Protocol)** is used to manage VLAN configurations and propagate them across the network.
- **Router-on-a-Stick** is configured for **Inter-VLAN routing** with a single physical interface on the router.
- **EtherChannel (LACP)** is implemented for **link aggregation**, improving bandwidth and redundancy.
- **RSTP (Rapid Spanning Tree Protocol)** ensures **fast convergence** and **loop prevention**, with **PortFast** enabled for faster port transitions.
- **Port Security** ensures that only authorized devices can connect to the network.

### **💻 DMZ Zone Configuration**
In the **DMZ (Demilitarized Zone)**, several key services are configured to simulate a real-world production environment:
- **DHCP**: Dynamically assigns IP addresses within the DMZ.
- **FTP**: File transfer protocol for secure file sharing.
- **HTTP**: Web server accessible from the external network.
- **DNS**: Resolves domain names for services.
- **Mail**: A mail server is set up for email communication.

### **🔒 Security Features**
- **SSH** is configured to enable secure remote access to the network devices.
- **Port Security** is applied to prevent unauthorized devices from connecting.
- **Unused Ports** are disabled to minimize potential attack vectors.

## **🚀 Objectives**
This project aims to:
1. **Implement a hierarchical network topology** for scalability and performance.
2. **Segment traffic** into VLANs for improved security and traffic management.
3. **Configure Router-on-a-Stick** for inter-VLAN routing.
4. **Enhance redundancy** and bandwidth using **EtherChannel** with LACP.
5. **Increase network stability** using **RSTP**.
6. **Improve security** with **Port Security**, **SSH**, and the disabling of unused ports.

## **🛠 Getting Started**
1. Clone or download this repository to access all the project files and configurations.
2. Refer to the **documentation** for detailed steps on setting up the network and configuring services.
3. Feel free to **fork** the repository and adapt it to your needs!

## **📧 Contact**
- **Email**: [aiouazadel6@gmail.com](mailto:aiouazadel6@gmail.com)
- **LinkedIn**: [Mohamed Adel Aiouaz](https://www.linkedin.com/in/mohamed-adel-aiouaz-10662b282)

---
Happy Networking! 🚀
