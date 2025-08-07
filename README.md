# vul
🔍 Nmap Scan Report – 192.168.1.155
🗓 Scan Details
Scan Dates: August 7, 2025

Target IP: 192.168.1.155

Scan Types:

r.txt: Service and OS detection (-A)

r1.txt: Vulnerability scripts and service detection (--script vuln -A)

📡 Host Information
Host Status: ✅ Up (Latency: ~1.8–1.9 ms)

MAC Address: 08:00:27:10:63:68 (Oracle VirtualBox NIC)

Device Type: General Purpose

Operating System: Microsoft Windows 7 Home Basic SP1 / Vista / 2008 R2 / 8.1

Workgroup: WORKGROUP
Computer Name: WIN7

🚪 Open Ports and Services
Port	State	Service	Version
135/tcp	open	msrpc	Microsoft Windows RPC
139/tcp	open	netbios-ssn	Microsoft Windows netbios-ssn
445/tcp	open	microsoft-ds	Windows 7 - 10 (WORKGROUP)
49152-49157/tcp	open	msrpc	Microsoft Windows RPC

🧠 OS and Service Detection
OS Matches: Windows Vista SP2 / 7 / Server 2008 R2 / 8.1

SMB Information:

SMB Version: 2.x

Signing: Enabled, not required

Guest Access: Allowed (authentication level: user)

Time Skew: ~1h 50m behind

🛡 Vulnerability Results
⚠ Vulnerable
MS17-010 – SMBv1 Remote Code Execution

Status: ✅ VULNERABLE

CVE: CVE-2017-0143

Risk: HIGH

Reference: Microsoft TechNet

❌ Not Vulnerable / Access Denied
samba-vuln-cve-2012-1182: Access Denied

smb-vuln-ms10-054: Not Vulnerable

smb-vuln-ms10-061: Access Denied

🛰 Traceroute
Copy
Edit
1   192.168.1.155   ~1.8 ms
