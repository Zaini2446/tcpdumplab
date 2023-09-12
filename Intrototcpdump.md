# TCPdump Quick Start Guide

Learn how to use TCPdump with these step-by-step instructions. This guide will walk you through common TCPdump commands and arguments.

## Prerequisites

- A Linux virtual machine with tcpdump installed
- Basic knowledge of the Linux terminal

## Steps

#### Step 1: Start Your Linux Virtual Machine and Open a Terminal
 - Start your Linux virtual machine.
 - Open a terminal window. You will use this terminal to run TCPdump commands.

#### Step 2: Explore Common TCPdump Commands
 - Before we dive into the details, let's take a look at some common TCPdump commands and arguments.
 - Open your terminal and type the following command to view the help page:
```bash
tcpdump --help
```
 - This will display a list of available options and usage information for TCPdump.

#### Step 3: Common TCPdump Commands and Arguments

- Now that you've explored the help page, let's focus on some of the most commonly used TCPdump commands and arguments:
  
    - **-i**: Specifies the network interface to sniff.
    - **-s**: Specifies the number of bytes to capture per packet (default is 262,144 bytes).
    - **-c**: Specifies the number of packets to capture before stopping.
    - **-n**: Prevents hostname and port number resolution.
    - **-X**: Displays packet contents in hexadecimal and ASCII.
    - **-XX**: Displays packet contents in hexadecimal and ASCII, including the Ethernet header.
    - **-e**: Displays Ethernet header data.
