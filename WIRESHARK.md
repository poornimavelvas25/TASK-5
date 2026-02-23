# WIRESHARK

1.What is Wireshark?

Wireshark is an open-source network protocol analyzer used to capture and analyze network traffic in real time.
It allows users to inspect packets at a detailed level for troubleshooting and security analysis.

Packet Monitor:There are color codes for each type of packet. The packets are shown with the following information : 

1.Source IP address

2.Destination IP address

3.Protocol (TCP, UDP, HTTP, etc.)

4.Packet length

5.Packet number

6.Source port (if applicable)

7.Destination port (if applicable)

8.Hexadecimal dump

9.ASCII/text content (if readable)

2.Wireshark can color packets based on rules that match particular fields in packets, to help the user identify the types of traffic.

Light blue → TCP traffic

Light green → HTTP traffic

Black/Red → TCP errors or retransmissions

Purple → DNS

3.Flitering Commands:-

tcp - Shows only tcp packets.

udp - Shows only udp packets.

ip.addr == ip - Shows packets from or to this IP.

ip.src == ip - Shows packets only from this source IP.

ip.dst == ip - Shows packets only to this destination IP.

tcp.port == 80 - Shows HTTP traffic.

tcp.analysis.retransmission - Shows retransmitted packets.

tcp.flags.syn == 1 - Shows SYN packets (used in TCP handshake).

http - Shows HTTP packets.

dns - Shows DNS packets.

4.Important Wireshark Features

Follow TCP Stream → Reconstruct entire communication session

Statistics → Shows protocol hierarchy

IO Graph → Network traffic graph

Expert Information → Highlights warnings & errors

Export Objects → Extract files from HTTP traffic

5.Why Wireshark is Important?

Detect suspicious traffic

Analyze attacks (DoS, SYN flood, ARP spoofing)

Troubleshoot network problems

Monitor bandwidth usage

6.Conclusion

Wireshark is a powerful packet analyzer used for network troubleshooting, monitoring, and security analysis. 
Using filters effectively allows analysts to quickly identify relevant traffic and detect potential threats.
