# Network Basics

This repository contains files and scripts designed to help you understand fundamental concepts of computer networking. Below is an overview of the tasks and their corresponding files.

---

## **Task 0: OSI Model**
- **File:** `0-OSI_model`
- **Description:**
  - Summarizes the seven layers of the OSI model and their primary functions.
  - Provides insight into how data travels from one system to another across a network.

---

## **Task 1: Types of Network**
- **File:** `1-types_of_network`
- **Description:**
  - Lists different types of networks: WAN, LAN, and Internet.
  - Highlights the differences and use cases of these network types.

---

## **Task 2: MAC and IP Addresses**
- **File:** `2-MAC_and_IP_address`
- **Description:**
  - Explains the difference between MAC and IP addresses.
  - Highlights how MAC addresses are hardware-specific, while IP addresses are logical and network-specific.

---

## **Task 3: TCP and UDP**
- **File:** `3-UDP_and_TCP`
- **Description:**
  - Differentiates between TCP and UDP protocols.
  - Identifies scenarios where each protocol is best suited.

---

## **Task 4: List TCP and UDP Ports**
- **File:** `4-TCP_and_UDP_ports`
- **Description:**
  - A script that lists all open TCP and UDP ports on the current machine.
  - Uses the `ss` or `netstat` command for compatibility.
- **Usage:**
  ```bash
  ./4-TCP_and_UDP_ports
  ```

---

## **Task 5: Check Network Connectivity**
- **File:** `5-is_the_host_on_the_network`
- **Description:**
  - A script to check if a host is reachable on the network using the `ping` command.
  - Takes the IP address of the target host as an argument.
- **Usage:**
  ```bash
  ./5-is_the_host_on_the_network <IP_address>
  ```

---

## **Getting Started**

### **Prerequisites**
- Ensure you have a Unix-based operating system (Linux, macOS, or WSL for Windows).
- Ensure the following tools are installed:
  - `bash`
  - `ping`
  - `ss` or `netstat`

### **Setup**
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the directory:
   ```bash
   cd <repository_name>
   ```
3. Make the scripts executable:
   ```bash
   chmod +x 4-TCP_and_UDP_ports 5-is_the_host_on_the_network
   ```

---

## **License**
This project is licensed under the MIT License. See the LICENSE file for details.

---

## **Author**
Salomon
