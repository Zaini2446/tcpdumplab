# TCPdump Lab

TCPdump is a robust, yet user-friendly, network packet analyzer that showcases network traffic from your network interfaces. You can easily apply elementary filters to focus on specific IP addresses, networks, TCP/UDP ports, and ICMP packets, thereby narrowing down the displayed or recorded traffic. Notably, TCPdump refrains from interpreting the data, leaving this task to the discretion of the analyst. The tool leans on the libpcap driver interface for the actual process of capturing Ethernet frames from the network wire. For more comprehensive information about the TCPdump and libpcap project, please visit https://www.tcpdump.org.

## Lab Overview

- **Objectives**:
  - Introduction to tcpdump and basic commands.
  - Running tcpdump and sniffing network traffic.
  - Analyzing hex and ASCII data.
  - Connecting to a non-listening TCP port.
- **Duration**: 20 minutes
- **Prerequisites**:
  - Basic knowledge of the Linux command line.
  - A Linux-based system with TCPdump installed.

## Lab Steps

1. [Introduction to TCPdump and Basic Commands](Intrototcpdump.md)
2. [Running TCP dump and Sniffing Network Traffic](runningtcpdump.md)
3. [Filtering Packets](Instructions/03-Filtering-Packets.md)
4. [Saving Captured Data](Instructions/04-Saving-Data.md)
5. [Advanced TCPdump Usage](Instructions/05-Advanced-Usage.md)
6. [Analyzing Captured Data](Instructions/06-Analyzing-Data.md)

## Sample Capture Files

Explore different types of network traffic with these sample capture files:

- [HTTP Traffic](Capture_Files/http_capture.pcap)
- [DNS Queries](Capture_Files/dns_capture.pcap)
- [SSH Session](Capture_Files/ssh_capture.pcap)

## Additional Resources

- [TCPdump Official Documentation](https://www.tcpdump.org/tcpdump_man.html)

Feel free to ask questions or provide feedback by creating issues in this repository.

Happy packet hunting!
