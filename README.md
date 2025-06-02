# task3

Basic Vulnerability Scan on Local Machine
🔍 Objective:
To identify common security vulnerabilities on the local Windows PC using Nessus Essentials, a free vulnerability scanning tool.

🧰 Tools Used:
Nessus Essentials (by Tenable)

Target: 127.0.0.1 (Localhost)

📋 Scan Summary:
Total Vulnerabilities Detected: 23

Medium Severity: 1

Informational: 22

⚠️ Top Vulnerabilities Found:
SMB Signing Not Required

Risk: May allow man-in-the-middle (MitM) attacks on SMB connections

Fix: Enable SMB signing via Windows Group Policy

SSL Configuration Issues

Risk: Weak encryption protocols enabled (SSLv2/SSLv3)

Fix: Enforce TLS 1.2 or 1.3 and disable older SSL versions

SMBv1 Protocol Enabled

Risk: Vulnerable to known exploits like EternalBlue

Fix: Disable SMBv1 via Windows Features

📝 Deliverables:
Vulnerability scan report (PDF/screenshots)

README file (this file)

Summary of findings and remediation suggestions
