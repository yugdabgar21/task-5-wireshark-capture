# Task 5: Network Traffic Capture with Wireshark

#### By: Yug Dabgar (aka MASTERxD)

## Overview
In this task, I used Wireshark to capture and analyze live network traffic. The main goal was to identify different network protocols and understand how data flows across the system.

## Tool Used
- Wireshark (Latest version)
- Platform: Windows 11

## Steps Performed

1. Opened Wireshark and selected the active network interface (Wi-Fi).
2. Started the packet capture.
3. Generated traffic by:
   - Visiting multiple websites
   - Running commands like `ping google.com`
4. Stopped the capture after ~1 minute.
5. Applied filters to analyze protocol types.

## Protocols Observed

### 1. DNS (Domain Name System)
- Resolves domain names to IP addresses.
- Observed during `ping` and website access.

### 2. HTTP (Hypertext Transfer Protocol)
- Standard web traffic protocol.
- Captured while browsing websites.

### 3. TCP (Transmission Control Protocol)
- Handles reliable data transfer between systems.
- Seen as the underlying protocol for both DNS and HTTP.

## Files Included
- `network_capture.pcap` – Full Wireshark capture
- `screenshots/` – Optional views of filtered traffic (HTTP, DNS, TCP)

## Conclusion
This task helped me understand how to work with packet captures and identify various protocols in real-time. Tools like Wireshark are essential for monitoring, debugging, and securing network traffic.
