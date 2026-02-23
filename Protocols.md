# PROTOCOLS
## ARP (Address Resolution Protocol)

Resolves IP addresses to MAC addresses within a local network. It appears when a device tries to identify another device on the same network.

## DNS (Domain Name System)

Converts domain names (like google.com) into IP addresses. DNS queries usually appear before accessing a website.

## TCP (Transmission Control Protocol)

Provides reliable, connection-based communication. It uses a 3-way handshake (SYN, SYN-ACK, ACK) before data transfer.

## UDP (User Datagram Protocol)

Connectionless protocol used for fast communication. Commonly used by DNS and streaming services.

## HTTP (Hypertext Transfer Protocol)

Transfers web data in plaintext. Displays GET/POST requests and server responses like “200 OK”.

## HTTPS (TLS)

Secure version of HTTP. Data is encrypted, and Wireshark shows TLS handshake messages like “Client Hello”.

## ICMP (Internet Control Message Protocol)

Used for network diagnostics such as ping. Shows Echo Request and Echo Reply packets.

# Table

| Protocol | Port Number | Filter | Example in Wireshark        |
| -------- | ----------- | ------ | --------------------------- |
| ARP      | No Port     | `arp`  | Who has 192.168.x.x         |
| DNS      | 53          | `dns`  | Standard query A google.com |
| TCP      | Varies      | `tcp`  | SYN, ACK                    |
| UDP      | Varies      | `udp`  | Source → Destination        |
| HTTP     | 80          | `http` | GET / HTTP/1.1              |
| HTTPS    | 443         | `tls`  | Client Hello                |
| ICMP     | No Port     | `icmp` | Echo request                |
