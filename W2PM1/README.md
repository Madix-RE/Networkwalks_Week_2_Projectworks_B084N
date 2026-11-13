<div align="center">

# 🔐 Footprinting And Reconisance

**Making use of Kali Tools To Aid In Footprintig & Reconisance**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
</p>

<h2>Introduction</h3>
<p> This project work for week 2 was based on footprintig and reconnaissance using some kali tools. This step is usually considered as the baseline for ethical hacking. Below are some explanations and screenshots of the tools used and what information it displays.
</p>
<h3>WHOIS</h3>
<p>With this command it is used to query online servers to retrieve public registration details for domain names and IP address blocks, helping users identify ownership, registrar information, and infrastructure details. In this instance networkwalks.com was used as shown below.  </p>

![](Pictures/Screenshot(253).png)
![](Pictures/Screenshot(254).png)

<h3>Whatweb</h3>
<p>This command answers the question "What is that website running?" by analyzing HTTP headers, HTML content, cookies, and JavaScript to identify the technologies behind a target site.  </p>

![](Pictures/Screenshot(259).png)


<h3>Nslookup</h3>
<p>In Kali Linux, nslookup is a DNS lookup utility used to query domain name servers for hostname-to-IP mappings and other DNS record types.Below is a screenshot</p>

![](Pictures/Screenshot(260).png)


<h3>Curl</h3>
<p>  curl (Client URL) is a versatile HTTP/HTTPS request utility used to fetch web content, inspect headers, and interact with web services from the command line.  It operates at the application layer — giving you full control over every aspect of an HTTP request, which makes it invaluable for both recon and exploitation.
</p>

![](Pictures/Screenshot(261).png)


<h3>WAF Identifier (wafw00f)</h3>
<p>In Kali Linux, wafw00f (Web Application Firewall Fingerprinting) is a Python-based tool used to identify and fingerprint WAF products protecting a target website.  It answers the question "Is there a WAF in front of this site, and which one?" — critical intel before crafting payloads. Below is a demonstration.</p>

![](Pictures/Screenshot(262).png)

<h3>Dnsrecon</h3>
<p>
  Dnsrecon is an advanced DNS enumeration tool that goes far beyond what nslookup does individually. It automates multiple DNS reconnaissance tasks in a single run — records, zone transfers, brute force, reverse lookups, cache snooping, and DNSSEC zone walks.
</p>

![](Pictures/Screenshot(263).png)

 
