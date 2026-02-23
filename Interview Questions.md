# INTERVIEW QUESTIONS
## What is Wireshark used for?

Wireshark is a network protocol analyzer.
It is used to capture and inspect network traffic in real time.
It helps users see what data is being sent and received over a network.
Cybersecurity professionals use it to detect suspicious activity.
It is also used for troubleshooting and learning how networks work.

## What is a packet?

A packet is a small unit of data sent over a network.
When you browse a website, the data is broken into packets.
Each packet contains source and destination information.
Packets travel separately and are reassembled at the destination.
They are the basic building blocks of network communication.

## How to filter packets in Wireshark?

Packets can be filtered using the Display Filter bar at the top.
You type the protocol name like http, dns, or tcp.
After typing the filter, press Enter to apply it.
Wireshark will then show only matching packets.
Filtering helps focus on specific traffic and reduces clutter.

## What is the difference between TCP and UDP?

TCP is a connection-based protocol.
It ensures data is delivered correctly and in order.
UDP is a connectionless protocol.
UDP is faster but does not guarantee delivery.
TCP is used for web browsing, while UDP is used for streaming and DNS.

## What is a DNS query packet?

A DNS query packet is a request sent to a DNS server.
It asks for the IP address of a domain name.
For example, it converts google.com into an IP address.
This happens before you access a website.
Without DNS queries, we would need to remember IP addresses.

## How can packet capture help in troubleshooting?

Packet capture shows what is happening on the network.
It helps identify connection problems.
You can see if packets are being lost or delayed.
It shows error messages and failed connections.
This makes it easier to find and fix network issues.

## How can packet capture help in troubleshooting?

Packet capture shows what is happening on the network.
It helps identify connection problems.
You can see if packets are being lost or delayed.
It shows error messages and failed connections.
This makes it easier to find and fix network issues.

## Can Wireshark decrypt encrypted traffic?

Wireshark cannot automatically read encrypted traffic.
HTTPS traffic appears as encrypted data.
However, it can decrypt traffic if you provide encryption keys.
Without the keys, the content remains unreadable.
This protects sensitive information from attackers.
