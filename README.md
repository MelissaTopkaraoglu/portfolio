# Basic Network Scanner 

**Author:** Melissa Topkaraoglu  
**Role:** Cybersecurity Analyst | SOC Tier 3  
**GitHub:** [github.com/MelissaTopkaraoglu](https://github.com/MelissaTopkaraoglu/Portfolio/))

---

## Project Summary

This project simulates a basic internal threat detection tool by identifying active devices on a local network and scanning for open TCP ports using Python. It replicates fundamental functionalities used in **network enumeration**, **asset discovery**, and **initial reconnaissance** — key phases in penetration testing and SOC investigations.

---

## Why This Project?

As part of enhancing my hands-on cybersecurity skills, I built this scanner to:
- Understand how tools like **Nmap** and **Nessus** function under the hood
- Reinforce Python scripting for network monitoring
- Practice threat modeling using minimal open-source tooling

---

## Key Skills Demonstrated

- Python scripting & socket programming  
- Network scanning & IP subnetting  
- Port scanning and host discovery  
- Cybersecurity fundamentals (Enumeration, Recon, Asset Discovery)  
- Use of Linux CLI, Wireshark (for testing), and virtual networks

---

## How It Works

1. Pings devices in a user-defined subnet to discover live hosts  
2. For each host, scans commonly used ports (e.g., 22, 80, 443, 3389)  
3. Displays live hosts and which ports are open  
4. Can be used to simulate vulnerability footprinting in a lab

---

## Tech Stack

- Language: Python 3  
- Tools: `socket`, `ipaddress`, `subprocess`, `Wireshark` (testing)  
- Platform: Cross-platform (Tested on Linux and Windows 10)

---

## Run It Yourself

```bash
# Clone the repo
git clone https://github.com/yourusername/basic-network-scanner.git
cd basic-network-scanner

# Run the script
python3 network_scanner.py
Edit the subnet and port list in network_scanner.py to match your lab/network.

Example Output
nginx
Copy
Edit
Scanning network: 192.168.1.0/24
[+] Active Host Found: 192.168.1.5
[+] Port 22 open on 192.168.1.5
[+] Port 443 open on 192.168.1.5
Project Structure
bash
Copy
Edit
basic-network-scanner/
├── network_scanner.py     # Main script
├── README.md              # Project documentation
├── .gitignore             # GitHub hygiene
└── requirements.txt       # Dependencies (none required)
Educational Purpose
This tool is for cybersecurity learning and demonstration only. Please do not use on networks without authorization.

Contact
LinkedIn: linkedin.com/in/yourprofile
Email: youremail@example.com
