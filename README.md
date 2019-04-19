# Linux-Sniffer (original project forked from am0nt031r0) -> https://github.com/am0nt31r0/Linux-Sniffer

# Description
The python script creates a raw socket and sniffs the incoming packets. The Ethernet, IP, ICMP, TCP and UDP headers are displayed in the terminal plus the payload packet.

# Tested on
Manjaro

# Before Running Install
Install Python3.6. Checkout this tutorial: https://docs.python-guide.org/starting/install3/linux/#install3-linux

# Run
Execute the script with super-user permissions.
The script makes use of 'socket' library which needs administration level to create a raw socket.

Usage: sudo ./sniffer.py

-------------------------------------------------------------------------------------------------------------------------------
# Expansion / Other module

I would like to elaborate and use the payload part:
1) Send payload somewhere else
2) Re-build the payload to re-create (for example) one PDF downloaded.

These above are the main activities that I would like to achieve.

