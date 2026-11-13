<div align="center">

# NETWORKWALKS-B084-WK2

This project involves conducting footprinting, reconnaissance and network scanning against an authorised domain and within a controlled local network environment.

</div>

# 1. Liability Disclaimer
This report was prepared as part of the NetworkWalks Cybersecurity Internship Program (B084) for educational and professional development purposes. Written authorisation was obtained prior to conducting the security assessments. All activities were performed within the authorised scope and were limited to footprinting, reconnaissance and network scanning.

No attempts were made to exploit vulnerabilities, disrupt services, bypass authentication or gain unauthorised access to systems. The findings are intended solely for educational and security awareness purposes and should not be interpreted as confirmed vulnerabilities unless supported by sufficient evidence.

# 2. Introduction

This report documents the activities completed during Week 2 of the NetworkWalks Cybersecurity Internship Program (B084). The exercises focused on footprinting and reconnaissance, alongside network scanning using Zenmap (W2-PM5).

The first activity involved gathering publicly available information about the authorised `networkwalks.com` domain using various Kali Linux utilities. This included WHOIS lookups, DNS enumeration, web technology fingerprinting, HTTP response header analysis and Web Application Firewall (WAF) detection. These techniques were used to examine domain registration information, identify associated network infrastructure and understand the technologies and security mechanisms protecting the target website.

The second activity focused on identifying active devices within my local network using Zenmap on Windows. This involved performing ping scans to discover responsive hosts and examining their associated IP addresses and available MAC address information. Windows Command Prompt utilities were also used to examine local network configuration.

The purpose of these exercises was to develop practical skills in information gathering, domain reconnaissance, network discovery and identifying potential security risks. Each activity is supported by relevant commands, observations, screenshots and explanations of the findings.

# 3. Tools Used

The following table outlines the tools and technologies used throughout the assessment and their respective purposes.

| **Tool** | **Purpose** |
| -------- | ----------- |
| Kali Linux | Operating system used to conduct domain footprinting and reconnaissance activities. |
| Windows 11 | Operating system used to perform local network discovery and examine network configurations. |
| WHOIS | Retrieves publicly available domain registration information, including registrar details, registration dates and name servers. |
| WhatWeb | Fingerprints websites to identify detectable technologies, web servers and frameworks. |
| nslookup | Performs DNS queries to resolve domain names into IP addresses and retrieve DNS information. |
| curl -I | Retrieves HTTP response headers to examine server responses and potentially disclosed configuration information. |
| Wafw00f | Identifies whether a website appears to be protected by a Web Application Firewall. |
| DNSRecon | Performs DNS enumeration to identify available records, including A, NS, MX, TXT and SRV records. |
| Zenmap (Nmap GUI) | Provides a graphical interface for Nmap and performs network discovery to identify responsive hosts, IP addresses and available MAC addresses. |
| Windows Command Prompt | Executes network configuration commands to identify local IP addresses, MAC addresses and network information. |

# 4. Activities Performed

