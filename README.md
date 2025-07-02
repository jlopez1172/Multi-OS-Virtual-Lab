🧪 Cybersecurity Lab in VirtualBox – Beginner Walkthrough
Welcome to my personal cybersecurity lab project! This setup is designed for hands-on learning in both offensive and defensive security using VirtualBox. It’s fully isolated, beginner-friendly, and perfect for experimenting with malware analysis, threat detection, and ethical hacking.

🖥️ Lab Overview
This lab consists of four virtual machines, each with a specific role and network configuration:

VM Name	Purpose	Network Mode	Key Tools & Features
macOS	Malware Analysis Sandbox	Internal Network	Snapshots, Wireshark, Static Analysis Tools
Security Onion	Defensive Monitoring	NAT	Suricata, Log Analysis, PCAP Import
Kali Linux	Offensive Testing	Bridged Adapter	Nmap, Metasploit, Hydra
Windows 10	Target Workstation	NAT	SMB/RDP, Sysmon, Logging
🔧 Setup Instructions
1. Prerequisites
VirtualBox installed

ISO images for macOS, Kali Linux, Security Onion, and Windows 10

Sufficient system resources (at least 16GB RAM and 100GB+ disk space recommended)

2. VM Configuration
🍏 macOS – Malware Analysis
Network: Internal Network (isolated)

Purpose: Safely open phishing attachments or suspicious executables

Tips: Use snapshots to revert after each test

🧅 Security Onion – Defensive Monitoring
Network: NAT

Purpose: Monitor traffic and detect threats using Suricata

Tips: Import PCAPs or simulate traffic for analysis

🐉 Kali Linux – Offensive Testing
Network: Bridged Adapter

Purpose: Simulate attacks on other VMs or devices

Tools: Nmap, Metasploit, Hydra

🪟 Windows 10 – Target Workstation
Network: NAT

Purpose: Simulate a vulnerable endpoint

Features: Exposed services (SMB, RDP), Sysmon for logging

🎯 Learning Goals
Practice ethical hacking techniques in a safe environment

Analyze malware behavior without risking your host system

Detect and respond to simulated threats using real-world tools

Understand how attackers exploit common vulnerabilities

Video of Lab Setup Available

📺 Coming Soon
I’ll be sharing walkthrough videos and tutorials on:

Malware analysis workflows

Threat detection with Security Onion

Ethical hacking scenarios using Kali Linux

🤝 Contributing
This project is a personal learning environment, but I’d love to hear your feedback or suggestions! Feel free to fork, adapt, or share your own lab setups.

📬 Contact
Connect with me on LinkedIn or drop a comment if you’re building something similar—I’d love to learn from your experience too!
