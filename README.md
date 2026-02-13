# cyart-vapt-team
This repository contains the Week 2 VAPT lab workflow, including scanning, exploitation, and reporting. It demonstrates the use of tools like Nmap, OpenVAS, Nikto, WhatWeb, and Metasploit to identify and exploit vulnerabilities, along with a professional VAPT report for documentation.”
Week2 VAPT Workflow
1. Reconnaissance
Identify the target IP/hostname.
Gather information about open ports using Nmap.
Detect services running on each port.
Determine server software and operating system fingerprints.
Collect publicly available information about the target.

2. Scanning
Perform Nmap scans for version detection (-sV).
Run OpenVAS for vulnerability scanning.
Generate detailed OpenVAS reports.
Use WhatWeb to detect tech stack (web server, CMS, frameworks).
Use Nikto for web vulnerability scanning.

3. Enumeration
Enumerate open services to find potential attack vectors.
Check for misconfigurations in services like FTP, SSH, HTTP.
Gather banner information to identify software versions.
Verify user accounts or accessible directories if applicable.
Document all findings for exploitation planning.

4. Exploitation
Use Metasploit to exploit vulnerable services.
Obtain shell access on the target.
Verify stability and persistence of the shell.
Test exploit success without causing system crashes.
Save screenshots and command logs in Exploitation/ folder.

5. Reporting
Document all findings in VAPT_Report.pdf.
Include timestamped screenshots for clarity.
Categorize vulnerabilities by severity (High / Medium / Low).
Provide remediation recommendations for each issue.
Maintain clear folder structure for scans, exploitation, and reports.
