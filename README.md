# Networking and Configuration Project

This project demonstrates the configuration and testing of a computer network connecting a server, IT, Sales and Human Resources (HR) departments, PCs, switches, and a router. It covers IP address configuration, DHCP, DNS, HTTP, FTP, and router connectivity to establish communication between devices and departmental networks.

## Table of Contents

- [Project Overview](#project-overview)
- [Network Topology](#network-topology)
- [Tools and Technologies](#tools-and-technologies)
- [Configuration Steps](#configuration-steps)
- [Results and Findings](#results-and-findings)
- [Author](#author)

## Project Overview

The purpose of this project was to configure and test a network infrastructure for a company with a central server and separate Sales and HR departments.

The project focused on:

- Configuring the server with a static IP address.
- Setting up DHCP to automatically assign IP addresses to client PCs.
- Configuring DNS to use the server's IP address.
- Connecting departmental networks to a router through switches.
- Configuring IP helper addresses to support communication between departmental PCs and the server.
- Configuring and testing HTTP and FTP services.
- Troubleshooting network connectivity issues.

## Network Topology

The network consists of a central server, departmental PCs, switches, and a router. The server provides network services, while the Sales and HR PCs obtain their IP configuration through DHCP.

### Network Components

- **Server:** Configured with a static IP address and used for DHCP, DNS, HTTP, and FTP services.
- **Sales Department:** Contains client PCs configured to obtain network settings automatically through DHCP.
- **HR Department:** Contains client PCs configured to obtain network settings automatically through DHCP.
- **Switches:** Connect departmental devices and provide links to the router.
- **Router:** Connects the departmental networks and supports communication between network segments.
- **IP helper addresses:** Configured to enable DHCP requests from the Sales and HR networks to reach the server.

### IP Addressing

- **Server:** Configured with a static IP address.
- **DNS:** Configured to use the server's IP address.
- **Sales PCs:** Configured to obtain IP addresses automatically through DHCP.
- **HR PCs:** Configured to obtain IP addresses automatically through DHCP.
- **Subnet mask:** `255.255.255.0` was used for the router interface configurations described in the assignment.

*Note: The assignment screenshots document the configurations, but the exact IP addresses and complete subnet allocation are not specified in the accompanying text.*

## Tools and Technologies

- **Cisco Packet Tracer:** Network simulation and configuration, as indicated by the network topology and configuration screenshots.
- **DHCP (Dynamic Host Configuration Protocol):** Automatic IP address assignment to client PCs.
- **DNS (Domain Name System):** Configured to use the server's IP address.
- **HTTP (Hypertext Transfer Protocol):** Web service configuration and connectivity testing.
- **FTP (File Transfer Protocol):** File transfer service configuration and troubleshooting.
- **IP addressing:** Static IP configuration and automatic client addressing.
- **Subnet mask:** `255.255.255.0` for the documented router interface configurations.
- **Router and switch configuration:** Network connectivity and communication between departmental segments.
- **Ping:** Connectivity testing and troubleshooting.

## Configuration Steps

1. **Configure the server IP address.**
   - Assign a static IP address to the server.
   - Configure the appropriate subnet mask and DNS settings.

2. **Configure DHCP and DNS.**
   - Set up DHCP to provide IP configuration to client PCs.
   - Configure DNS to use the server's IP address.
   - Apply the configuration to the Sales and HR departmental networks.

3. **Configure the departmental PCs.**
   - Change the client PCs' IP configuration from static addressing to DHCP.
   - Verify that the PCs automatically receive their network settings without manual entry.

4. **Connect the switches to the router.**
   - Configure the router interfaces with the appropriate IP addresses.
   - Apply the subnet mask `255.255.255.0` to the relevant interfaces.
   - Verify that the switch-to-router links become active.

5. **Configure IP helper addresses.**
   - Configure the router's IP helper addresses to allow DHCP requests from the Sales and HR networks to reach the server.

6. **Configure and test HTTP.**
   - Set up the HTTP service on the server.
   - Test the service to confirm that the HTTP connection is working.

7. **Configure and troubleshoot FTP.**
   - Configure the FTP service using the company's name.
   - Test FTP connectivity.
   - Investigate the initial FTP timeout and failed ping.
   - Resolve the connectivity issue and re-test the service.

8. **Verify the complete network.**
   - Review the final network topology.
   - Confirm the router and switch connections are active.
   - Check client IP configuration and the availability of network services.

## Results and Findings

The project demonstrated the configuration of a basic departmental network and the use of common networking services.

### Successful Outcomes

- **Static server addressing:** The server was configured with a static IP address.
- **DHCP configuration:** Sales and HR PCs were configured to obtain their IP addresses automatically.
- **DNS configuration:** The server's IP address was used as the DNS address in the documented configurations.
- **Router and switch connectivity:** The initially inactive connections became active after configuration, with the links changing from red to green.
- **HTTP service:** The screenshots confirmed that the HTTP service was working.
- **FTP troubleshooting:** FTP initially timed out, and ping testing also failed. The issue was subsequently resolved, as recorded in the assignment.

### Key Findings

- DHCP reduces the need to configure IP addresses manually on individual PCs.
- A consistent and appropriate IP addressing scheme is important for network communication.
- IP helper addresses support DHCP communication between clients on different network segments and a central server.
- Router and switch interface configuration is essential for establishing network connectivity.
- Testing services and using ping helps identify connectivity problems during network configuration.

Overall, the project provided practical experience in network setup, IP addressing, DHCP and DNS configuration, service testing, and basic troubleshooting.

## Author

**Name:** LouisaNenns

**Project:** Introduction to Networking Assignment
