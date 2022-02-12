# Spoofed-SYNFlood

SYNFlood DoS attack that spoofs the source IP address.

## Execution

1. Execute the script via cli: `python SpoofedSYNFlood.py`.
> The script must be executed with root privileges, so add `sudo` on Linux or open a cmd with administrator privileges on Windows

2. Provide target IP address, target port and the number of packets you wish to send.

## Execution Results

### Console Output

![Console output](/Screenshots/console.PNG)

### Wireshark Logs

![Wireshark logs](/Screenshots/wireshark.PNG)

## Dependencies

- pcap
- scapy
