# Packet Capture and Network Intrusion Analysis
This project demonstrates network traffic analysis and intrusion detection capabilities using Wireshark. The lab involves capturing and analyzing malicious network traffic, identifying anomalies, and extracting Indicators of Compromise (IOCs) from various attack scenarios.

## Objectives
- Capture and analyze malicious network traffic using Wireshark
- Identify network-based attack patterns including port scans and brute force attempts
- Extract IOCs for threat intelligence and incident response
- Document findings and demonstrate network forensics skills

## Lab Environment
Tools Used:
- Wireshark (packet capture and analysis)
- Target VMs (Windows/Linux)
- Virtual network environment(VirtualBox)

## Attack Scenarios Analyzed
1. Port Scan Detection
- Simulated an Nmap port scan and analyzed the traffic in Wireshark.

What I Found:
- Multiple connection attempts to different ports from the same IP
- Most connections were rejected (RST packets)
- Pattern shows attacker looking for open services

2. Brute Force Attack
- Simulated repeated login attempts to SSH/RDP.

What I Found:
- Many failed authentication attempts from single source
- High frequency of login attempts over short time period
- Clear pattern of automated attack tool

## Skills Demonstrated
- Packet capture and analysis (Wireshark)
- Network protocol analysis (TCP/IP, HTTP, DNS)
- Intrusion detection and pattern recognition
- IOC extraction and threat intelligence
- Network forensics and incident investigation
- Security monitoring and anomaly detection
- Technical documentation and reporting

## Future Enhancements
- Automate IOC extraction with Python/Scapy
- Integrate with SIEM for real-time alerting
- Develop custom Wireshark dissectors
- Create Snort/Suricata IDS rules based on findings
- Build threat intelligence feed from extracted IOCs
