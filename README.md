RapidScan v1.2 - The Multi-Tool Web Vulnerability Scanner
RapidScan has been ported to Python3 i.e. v1.2. The Python2.7 codebase is available on v1.1 releases section. Download and use it if you still haven't upgraded to Python 3. Kindly note that the v1.1 (Python2.7) will not be enhanced further.

Evolution:
It is quite a fuss for a pentester to perform binge-tool-scanning (running security scanning tools one after the other) sans automation. Unless you are a pro at automating stuff, it is a herculean task to perform binge-scan for each and every engagement. The ultimate goal of this program is to solve this problem through automation; viz. running multiple scanning tools to discover vulnerabilities, effectively judge false-positives, collectively correlate results and saves precious time; all these under one roof.

Features
one-step installation.
executes a multitude of security scanning tools, does other custom coded checks and prints the results spontaneously.
some of the tools include nmap, dnsrecon, wafw00f, uniscan, sslyze, fierce, lbd, theharvester, amass, nikto etc executes under one entity.
saves a lot of time, indeed a lot time!.
checks for same vulnerabilities with multiple tools to help you zero-in on false positives effectively.
extremely light-weight and not process intensive.
legends to help you understand which tests may take longer time, so you can Ctrl+C to skip if needed.
association with OWASP Top 10 & CWE 25 on the list of vulnerabilities discovered. (under development)
critical, high, medium, low and informational classification of vulnerabilities.
vulnerability definitions guides you what the vulnerability actually is and the threat it can pose.
remediation tells you how to plug/fix the found vulnerability.
executive summary gives you an overall context of the scan performed with critical, high, low and informational issues discovered.
FYI:
program is still under development, works and currently supports 80 vulnerability tests.
parallel processing is not yet implemented, may be coded as more tests gets introduced.
Vulnerability Checks
✔️ DNS/HTTP Load Balancers & Web Application Firewalls.
✔️ Checks for Joomla, WordPress and Drupal
✔️ SSL related Vulnerabilities (HEARTBLEED, FREAK, POODLE, CCS Injection, LOGJAM, OCSP Stapling).
✔️ Commonly Opened Ports.
✔️ DNS Zone Transfers using multiple tools (Fierce, DNSWalk, DNSRecon, DNSEnum).
✔️ Sub-Domains Brute Forcing (DNSMap, amass, nikto)
✔️ Open Directory/File Brute Forcing.
✔️ Shallow XSS, SQLi and BSQLi Banners.
✔️ Slow-Loris DoS Attack, LFI (Local File Inclusion), RFI (Remote File Inclusion) & RCE (Remote Code Execution).
& more coming up...
Requirements
Python 3
Kali OS (Preferred, as it is shipped with almost all the tools)
Tested with Parrot & Ubuntu Operating Systems.

Usage
python3 rapidscan.py example.com

Installation
Alternatively, your can install the rapidscan python module with pip. This will create a link for rapidscan in your PATH.

git clone https://github.com/skavngr/rapidscan.git 
cd rapidscan
python3 -m pip install .
