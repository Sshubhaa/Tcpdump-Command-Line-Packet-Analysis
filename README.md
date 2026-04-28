## About This Project
This project is part of my hands-on cybersecurity learning journey as I transition into the field.

# Tcpdump-Command-Line-Packet-Analysis
This lab introduced tcpdump as a command-line tool for capturing and analysing network traffic.

## Objectives
- Capture packets via CLI
- Apply filters for targeted analysis
- Understand traffic without GUI tools

## Tools & Technologies
- tcpdump
- Linux terminal

  ## Key Concepts Covered
- Packet sniffing
- Command-line filtering
- Network troubleshooting

  ## Practical Tasks Performed
- Captured traffic on specific interfaces
- Filtered packets by port and protocol
- Saved packet captures for analysis

## Key Commands
bash
tcpdump -i eth0
tcpdump -i eth0 port 80
tcpdump -i eth0 -w capture.pcap
