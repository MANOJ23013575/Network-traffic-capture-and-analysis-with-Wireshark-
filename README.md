### NAME : MANOJ K
### REG NO : 212222223001
# EX 9 : Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.



### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage
## 1. Open Wireshark and Select a Network Interface
• Launch Wireshark.
• Select an active interface (like Wi-Fi or Ethernet) to start capturing packets.

<img width="1810" height="832" alt="step 1" src="https://github.com/user-attachments/assets/ff94c406-3700-47e1-927b-725600c4abf1" />

## 2. Start Capturing Packets
• Click the blue shark fin icon or double-click the interface.
• Wireshark will start capturing all real-time traffic.

<img width="1910" height="1048" alt="step 2" src="https://github.com/user-attachments/assets/1b873bd1-f6bb-4967-985d-f8afd3a1437b" />


## 3. Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter
bar to narrow down results.

<img width="1908" height="1076" alt="step 3" src="https://github.com/user-attachments/assets/770871c3-3fa7-450b-a228-3370bc3c4522" />




## 4. Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,
IP, TCP/UDP layers, and data payload.


<img width="1727" height="1022" alt="step 4" src="https://github.com/user-attachments/assets/5306b9b4-029d-4c45-b6e8-90dd7fcd9920" />



## 5. Export or Save the Capture
• Go to File > Save As to store the capture in .pcap format for future analysis.

<img width="1617" height="793" alt="image" src="https://github.com/user-attachments/assets/093282d3-4a42-401e-8885-6ef4e116780d" />



<img width="1595" height="825" alt="10 last img" src="https://github.com/user-attachments/assets/66bd30fe-6d80-414d-a480-5eb46bf4c8fa" />




## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
