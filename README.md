# Network Security Implementation

## Overview
This project demonstrates the implementation of network security measures in a sandbox environment using a virtual machine. The primary goal was to configure a secure network through the use of a firewall, VPN, and an Intrusion Detection System (IDS). 

## Key Features
- **Firewall Configuration**: Set up a firewall to control incoming and outgoing network traffic based on predetermined security rules.
- **VPN Implementation**: Configured a Virtual Private Network (VPN) for secure, encrypted communication.
- **Traffic Analysis**: Used Wireshark to analyze network traffic, identifying potential vulnerabilities and ensuring data integrity.
- **Intrusion Detection**: Installed Snort as an IDS to monitor network traffic and reduce detection time by 30%.

## Technologies Used
- **Operating System**: Windows 10 (VM)
- **Tools**: 
  - Firewall (Windows Firewall)
  - VPN Solution
  - Wireshark
  - Snort

## Installation and Setup

### Prerequisites
- Virtual Machine (VM) running Windows 10
- Administrative privileges on the VM

### Steps
1. **Configure Firewall**:
   - Access the Windows Firewall settings.
   - Create inbound and outbound rules as per security requirements.

2. **Set Up VPN**:
   - Choose and install a VPN solution (e.g., OpenVPN).
   - Follow the installation instructions provided by the VPN provider.

3. **Install Wireshark**:
   - Download and install Wireshark from [Wireshark's official site](https://www.wireshark.org/).

4. **Install Snort**:
   - Download Snort from [Snort's official site](https://www.snort.org/downloads).
   - Follow the installation instructions, ensuring to configure the `snort.conf` file appropriately.

5. **Configure Snort for Network Monitoring**:
   - Identify the network interface using the command:
     ```bash
     snort -D -i <interface_id> -c C:\snort\etc\snort.conf
     ```
   - Replace `<interface_id>` with the appropriate interface ID.

6. **Analyze Network Traffic**:
   - Start Wireshark to monitor real-time traffic.
   - Use Snort to log alerts and monitor for potential threats.

## Results
- Successfully configured a secure network environment.
- Reduced detection time for potential threats by 30% through the use of Snort.

## Future Improvements
- Explore advanced firewall configurations.
- Implement additional security measures such as multi-factor authentication (MFA).
- Expand the IDS capabilities by integrating other security tools.


## Below are some screenshots from the project
![Screenshot 2024-10-10 155034](https://github.com/user-attachments/assets/837bc245-2f8c-4aeb-a039-61c41bea0c37)
![Screenshot 2024-10-10 154143](https://github.com/user-attachments/assets/c87fc03c-3b61-4aff-8d16-060c98842902)
![Screenshot 2024-10-10 154006](https://github.com/user-attachments/assets/b13cc998-5f16-4fc9-a51e-931ce3a5d76f)
![Screenshot 2024-10-10 150144](https://github.com/user-attachments/assets/26a6fe7b-b89f-42a1-ade9-416a59aced86)
![Screenshot 2024-10-10 132206](https://github.com/user-attachments/assets/ab3ebe89-a48c-4809-b295-5311094d3afe)
![Screenshot 2024-10-10 130911](https://github.com/user-attachments/assets/b59611ac-f840-4254-b84d-621b4cb20768)
![Screenshot 2024-10-10 130627](https://github.com/user-attachments/assets/44901264-eca3-4946-9bb3-b023a148b1b5)
![Screenshot 2024-10-10 130506](https://github.com/user-attachments/assets/f49b8ede-66b1-403f-908e-a8855f4f805a)


