# TASK-5
## Objective

The objective of this lab is to capture live network traffic using Wireshark, analyze different protocols, and export the captured packets as a .pcap file for further investigation.

# Tools Used

Wireshark

Kali Linux (VirtualBox NAT Network)

Firefox Browser

# What I Did

Installed Wireshark on Kali Linux.

Opened Wireshark and selected the active network interface (eth0).

Started capturing live network traffic.

Generated traffic by:

Browsing a website (http://example.com)

Running ping google.com

Captured packets for about 1 minute.

Stopped the capture.

Applied protocol filters to analyze the traffic.

Exported the capture file as a .pcap file.

# Protocols Identified
## DNS
Used to resolve domain names to IP addresses.

Observed DNS query for google.com.

## TCP

Three-way handshake observed:

SYN

SYN-ACK

ACK

Used for reliable communication.
## HTTP

Observed GET request:

GET / HTTP/1.1

Server response: 200 OK

# Key Observations

DNS request occurs before HTTP communication.

TCP handshake happens before data transfer.

HTTP traffic is visible in plaintext.

## Always analyze:

Source IP

Destination IP

Port numbers

Packet length

Flags (SYN, ACK, FIN,RST)


# File Exported

Capture file saved as: test.pcap

# Conclusion 

Wireshark captures raw network data and breaks it down into readable protocol layers such as DNS, TCP and HTTP.Display filters help isolate specific protocols for focused analysis.Overall, Wireshark provides deep visibility into network communication, making it an essential tool for troubleshooting, monitoring, and cybersecurity analysis.

