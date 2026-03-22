# Nmap Network Scanning Lab

## Objective
Identify active hosts and analyze exposed services within a virtual network, then validate security changes.

## Tools
- Nmap (CLI)
- Windows 11 Pro VM
- Windows Server (Active Directory)

## Network
- Subnet: 192.168.64.0/24

## Steps

### 1. Network Identification
Identified local network configuration using ipconfig.

![ipconfig](1-ipconfig.png)

### 2. Network Discovery
Performed host discovery to identify active systems on the network.

![discovery](2-network-dsicovery.png)

### 3. Service Enumeration
Scanned target system to identify open ports and services.

![services](3-service-enumeration.png)

### 4. RDP Exposure (Before)
Confirmed Remote Desktop (port 3389) was open.

![rdp-open](4-rdp-open.png)

### 5. RDP Disabled (After)
Disabled RDP and confirmed port 3389 changed to filtered.

![rdp-filtered](5-rdp-filtered.png)

## Key Takeaways
- Identified active hosts using Nmap
- Enumerated services including Active Directory components
- Validated security changes by testing port exposure