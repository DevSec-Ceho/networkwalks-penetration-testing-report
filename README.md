# PENETRATION TESTING REPORT
## FOOTPRINTING & NETWORK SCANNING PHASES

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Cybersecurity-blue?style=for-the-badge" alt="Cybersecurity">
  <img src="https://img.shields.io/badge/Program-Networkwalks-orange?style=for-the-badge" alt="Networkwalks">
  <img src="https://img.shields.io/badge/Batch-B084-green?style=for-the-badge" alt="Batch B084">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Completed">
</p>

<p align="center">
  <strong>W2-PM-FINAL | CYBERSECURITY | NETWORKWALKS</strong>
</p>

---

## 📌 Table of Contents

- [Report Information](#report-information)
- [Liability Disclaimer](#liability-disclaimer)
- [Introduction](#introduction)
- [Tools Used](#tools-used)
- Activities Performed
  - Footprinting and Reconnaissance
  - Network Scanning with Zenmap
- [Risk Analysis and Potential Impact](#risk-analysis-and-potential-impact)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [Evidence and Screenshots](#evidence-and-screenshots)
- [Author](#author)

---

## 📋 Report Information

<table>
  <tr>
    <th>Category</th>
    <th>Details</th>
  </tr>
  <tr>
    <td><strong>Pentester Name</strong></td>
    <td>Chijioke Henry Okoye</td>
  </tr>
  <tr>
    <td><strong>Program / Batch</strong></td>
    <td>B084 – Networkwalks</td>
  </tr>
  <tr>
    <td><strong>Date</strong></td>
    <td>10th November 2026</td>
  </tr>
  <tr>
    <td><strong>Modules Completed</strong></td>
    <td>W2-PM1 – Multiple Kali Tools<br>W2-PM5 – Zenmap Scanning</td>
  </tr>
  <tr>
    <td><strong>Client / Target</strong></td>
    <td>Networkwalks (networkwalks.com) and personal local LAN</td>
  </tr>
  <tr>
    <td><strong>Permission Secured</strong></td>
    <td>Yes</td>
  </tr>
  <tr>
    <td><strong>Phases Covered</strong></td>
    <td>Phase 1: Reconnaissance & Footprinting<br>Phase 2: Scanning & Network Discovery</td>
  </tr>
</table>

---

## ⚖️ Liability Disclaimer

<p>
  I performed these activities only on systems and networks for which I had appropriate authorization or that I personally own. These exercises were completed strictly for educational and research purposes as part of my cybersecurity training with Networkwalks.
</p>

<p>
  The information contained in this report demonstrates my practical understanding of reconnaissance, footprinting, and network scanning. Unauthorized access to computer systems and networks is illegal and may attract serious legal consequences.
</p>

<p>
  I accept responsibility for ensuring that the knowledge and techniques acquired during these exercises are applied ethically and within authorized environments.
</p>

---

## 🎯 Introduction

This report documents my practical activities during Week 2 of the Networkwalks Cybersecurity and Ethical Hacking Internship.

The practical exercises covered two major areas of penetration testing:

<ol>
  <li><strong>Footprinting and Reconnaissance (W2-PM1)</strong></li>
  <li><strong>Network Scanning with Zenmap (W2-PM5)</strong></li>
</ol>

For the footprinting exercise, I used multiple Kali Linux tools to gather publicly available information about the <code>networkwalks.com</code> domain.

The assessment involved:

<ul>
  <li>Domain registration information gathering.</li>
  <li>Website technology fingerprinting.</li>
  <li>DNS resolution and enumeration.</li>
  <li>HTTP response header inspection.</li>
  <li>Web Application Firewall identification.</li>
</ul>

For the network scanning exercise, I used Zenmap to discover active devices on my local network, identify their IP and MAC addresses, and generate a visual representation of the network topology.

Both practical exercises were successfully completed by following the instructions provided by my instructor.

---

## 🛠️ Tools Used

The following tools and technologies were used during the practical exercises:

<table>
  <tr>
    <th>Tool</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td><strong>Kali Linux</strong></td>
    <td>Operating system used for footprinting and reconnaissance.</td>
  </tr>
  <tr>
    <td><strong>WHOIS</strong></td>
    <td>Obtaining publicly available domain registration information.</td>
  </tr>
  <tr>
    <td><strong>WhatWeb</strong></td>
    <td>Identifying technologies and frameworks used by a website.</td>
  </tr>
  <tr>
    <td><strong>Nslookup</strong></td>
    <td>Resolving domain names to their corresponding IP addresses.</td>
  </tr>
  <tr>
    <td><strong>cURL</strong></td>
    <td>Inspecting HTTP response headers using the <code>-I</code> option.</td>
  </tr>
  <tr>
    <td><strong>Wafw00f</strong></td>
    <td>Identifying the presence and type of Web Application Firewall.</td>
  </tr>
  <tr>
    <td><strong>DNSRecon</strong></td>
    <td>Enumerating DNS records and gathering DNS-related information.</td>
  </tr>
  <tr>
    <td><strong>Zenmap</strong></td>
    <td>Performing network discovery and visualizing network topology.</td>
  </tr>
  <tr>
    <td><strong>Windows CMD</strong></td>
    <td>Identifying local network configuration and IP information.</td>
  </tr>
</table>

---

## 🔍 Activities Performed

### 1. Footprinting and Reconnaissance

I began the first practical by performing footprinting and reconnaissance on the authorized target domain:

<p align="center">
  <strong>Target Domain: networkwalks.com</strong>
</p>

The objective was to understand how publicly available information can reveal details about a website's infrastructure and technologies without attempting to exploit the target.

I used six different Kali Linux tools, each serving a specific purpose.

#### 1.1 WHOIS

I used WHOIS to obtain publicly available domain registration information.

This helped me understand how domain registration details, name servers, and other ownership-related information can be gathered during the reconnaissance phase.

#### 1.2 WhatWeb

I used WhatWeb to identify the technologies and frameworks associated with the target website.

This exercise demonstrated how website technology fingerprinting can help security professionals understand the technologies exposed by a web application.

#### 1.3 Nslookup

I used Nslookup to resolve the target domain name and obtain its corresponding IP address.

This demonstrated how DNS resolution helps establish the relationship between domain names and network addresses.

#### 1.4 cURL (HTTP Header Inspection)

I used cURL with the <code>-I</code> option to inspect the HTTP response headers returned by the target website.

This helped me understand how HTTP headers can expose useful technical information about a web server and its application.

#### 1.5 Wafw00f

I used Wafw00f to identify whether the target website was protected by a Web Application Firewall (WAF).

This exercise introduced me to the process of identifying security technologies that organizations use to protect their web applications.

#### 1.6 DNSRecon

Finally, I used DNSRecon to enumerate DNS information associated with the target domain.

This helped me understand how DNS enumeration can reveal information about name servers, mail servers, and other DNS records.

---

### 2. Network Scanning with Zenmap

For the second practical, I used Zenmap, the graphical interface for Nmap, to perform network discovery on my own local network.

The objective was to identify active devices, examine their network addresses, and generate a visual representation of the network topology.

#### Activities Performed

<ol>
  <li>Opened Windows Command Prompt to identify my local network configuration.</li>
  <li>Used the <code>ipconfig</code> command to obtain my local IP address and network information.</li>
  <li>Identified the appropriate network subnet for scanning.</li>
  <li>Opened Zenmap and entered the identified subnet.</li>
  <li>Selected the Ping Scan option to discover active hosts.</li>
  <li>Examined the scan results to identify live devices.</li>
  <li>Reviewed the IP and MAC address information returned by the scan.</li>
  <li>Opened the Topology section in Zenmap to visualize the discovered network.</li>
  <li>Enabled the topology legend and generated the network topology.</li>
  <li>Saved the resulting topology as a PDF document.</li>
</ol>

The exercise helped me understand how network scanning can be used to identify active devices and visualize the structure of a local network.

---

## ⚠️ Risk Analysis and Potential Impact

The activities performed during these exercises demonstrated how reconnaissance and network scanning can expose useful information about a target environment.

The following table highlights potential security implications associated with the information gathered.

<table>
  <tr>
    <th>No.</th>
    <th>Risk / Finding</th>
    <th>Potential Impact</th>
    <th>Risk Level</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Publicly exposed website technologies</td>
    <td>Attackers may identify technologies that require further security assessment.</td>
    <td>Medium</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Domain IP address identification</td>
    <td>Provides information about the target's network infrastructure.</td>
    <td>Low</td>
  </tr>
  <tr>
    <td>3</td>
    <td>HTTP response header information</td>
    <td>May assist further technology fingerprinting and enumeration.</td>
    <td>Low</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Web Application Firewall identification</td>
    <td>Reveals information about the web application's security architecture.</td>
    <td>Low</td>
  </tr>
  <tr>
    <td>5</td>
    <td>DNS infrastructure information</td>
    <td>May help build a broader profile of the organization's infrastructure.</td>
    <td>Medium</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Multiple active devices on a local network</td>
    <td>Unknown devices may introduce potential security concerns if not properly managed.</td>
    <td>Medium</td>
  </tr>
</table>

<p>
  <strong>Important Note:</strong> These are potential security implications of information exposed during reconnaissance and network discovery. They should not be interpreted as confirmed vulnerabilities.
</p>

The exercises focused on information gathering and network discovery. No exploitation or vulnerability validation was performed as part of these two practical modules.

---

## 💡 Recommendations

Based on the activities covered in this practical, I recommend the following security measures:

<ol>
  <li>
    <strong>Review Publicly Exposed Information:</strong>
    Organizations should periodically examine the technical information their websites expose to the public.
  </li>
  <li>
    <strong>Keep Software Updated:</strong>
    Website platforms, plugins, and other technologies should be updated regularly to reduce exposure to known vulnerabilities.
  </li>
  <li>
    <strong>Review HTTP Response Headers:</strong>
    Organizations should ensure that unnecessary technical information is not exposed through HTTP headers.
  </li>
  <li>
    <strong>Monitor DNS Records:</strong>
    DNS configurations should be reviewed regularly to ensure that only necessary records and services are publicly available.
  </li>
  <li>
    <strong>Maintain Proper WAF Configuration:</strong>
    Web Application Firewalls should be properly configured, maintained, and monitored.
  </li>
  <li>
    <strong>Perform Regular Network Discovery:</strong>
    Organizations should periodically scan their internal networks to identify active devices.
  </li>
  <li>
    <strong>Investigate Unknown Devices:</strong>
    Unexpected devices discovered during network scanning should be investigated and verified.
  </li>
  <li>
    <strong>Maintain Network Documentation:</strong>
    Network topology, device addresses, and infrastructure information should be properly documented and updated.
  </li>
  <li>
    <strong>Conduct Authorized Security Assessments:</strong>
    Reconnaissance and scanning activities should always be performed within an approved scope.
  </li>
</ol>

---

## 🏁 Conclusion

During Week 2 of my Cybersecurity and Ethical Hacking Internship with Networkwalks, I successfully completed practical exercises covering footprinting, reconnaissance, and network scanning.

I used six Kali Linux tools: WHOIS, WhatWeb, Nslookup, cURL, Wafw00f, and DNSRecon to understand how information about a website and its infrastructure can be collected and analyzed.

I also used Zenmap to perform network discovery on my local network, identify active hosts, examine IP and MAC address information, and generate a network topology.

One important lesson I gained from these exercises is that effective penetration testing begins with understanding the target environment.

Before attempting any further security assessment, it is important to know what information is publicly available and how devices communicate within a network.

I also gained more practical understanding of how different reconnaissance tools complement one another and how network discovery contributes to the overall penetration testing process.

I completed the exercises by following the provided instructions and successfully generated the required network topology.

Overall, this practical improved my understanding of the reconnaissance and scanning phases of penetration testing and strengthened my ability to use industry-relevant cybersecurity tools.

---

## 📸 Evidence and Screenshots

This section is reserved for screenshots captured during my practical exercises. The screenshots serve as visual evidence of the tools used, commands executed, and results obtained.

### 8.1 Footprinting and Reconnaissance – W2-PM1

#### Screenshot 1: WHOIS Domain Information

<p align="center">
 <img width="1667" height="938" alt="whois" src="https://github.com/user-attachments/assets/15ceb9a6-9291-4cf0-9089-0a5ecdfb2903" />
  <br>
  <em>WHOIS domain registration information gathered during reconnaissance.</em>
</p>

#### Screenshot 2: WhatWeb Technology Fingerprinting

<p align="center">
  <img width="1919" height="621" alt="whatweb" src="https://github.com/user-attachments/assets/471abda2-eb39-4b24-af1b-40b9a114db2b" />
  <br>
  <em>Technology fingerprinting performed using WhatWeb.</em>
</p>

#### Screenshot 3: Nslookup Domain Resolution

<p align="center">
  <img width="1730" height="515" alt="nslookup" src="https://github.com/user-attachments/assets/5c5257f3-7197-446d-b127-c5616a4f353a" />
  <br>
  <em>DNS resolution of the target domain using Nslookup.</em>
</p>

#### Screenshot 4: cURL HTTP Response Headers

<p align="center">
  <img width="1919" height="579" alt="curl" src="https://github.com/user-attachments/assets/b77ddad3-99ff-48b1-aa40-f81f9bffdb35" />
  <br>
  <em>HTTP response header inspection using cURL.</em>
</p>

#### Screenshot 5: Wafw00f WAF Detection

<p align="center">
  <img width="1217" height="665" alt="wafw00f" src="https://github.com/user-attachments/assets/cc84da66-1b0b-45fb-8dbf-aff2888cc35e" />
  <br>
  <em>Web Application Firewall identification using Wafw00f.</em>
</p>

#### Screenshot 6: DNSRecon Enumeration

<p align="center">
  <img width="1255" height="472" alt="dnsrecon" src="https://github.com/user-attachments/assets/da43107b-4e8a-44b4-98db-a1be38a4541f" />
  <br>
  <em>DNS enumeration performed using DNSRecon.</em>
</p>

### 8.2 Network Scanning with Zenmap – W2-PM5


#### Screenshot 7: Zenmap Ping Scan Configuration

<p align="center">
 <img width="1920" height="1080" alt="zenmap" src="https://github.com/user-attachments/assets/6ed9f6b1-fce0-4e51-8b5e-3b7930e9e7c6" />
  <br>
  <em>Zenmap scan configuration for local network discovery.</em>
</p>


#### Screenshot 8: Zenmap Network Topology

<p align="center">
  <img width="1920" height="1080" alt="zenmap2" src="https://github.com/user-attachments/assets/83e7d009-d7e4-433d-9d1c-8dea13aa14ba" />
  <br>
  <em>Visual representation of the discovered local network topology.</em>
</p>



---

## 👨‍💻 Author

<p align="center">
  <strong>Chijioke Henry Okoye</strong>
  <br>
  Cybersecurity & Ethical Hacking Intern
  <br>
  Networkwalks – Batch B084
</p>

---

## 📚 Project Information

<table>
  <tr>
    <th>Field</th>
    <th>Details</th>
  </tr>
  <tr>
    <td>Program</td>
    <td>Networkwalks Cybersecurity Internship</td>
  </tr>
  <tr>
    <td>Week</td>
    <td>02</td>
  </tr>
  <tr>
    <td>Practical Modules</td>
    <td>W2-PM1 and W2-PM5</td>
  </tr>
  <tr>
    <td>Focus Areas</td>
    <td>Footprinting, Reconnaissance and Network Scanning</td>
  </tr>
  <tr>
    <td>Operating System</td>
    <td>Kali Linux</td>
  </tr>
  <tr>
    <td>Documentation</td>
    <td>GitHub README.md</td>
  </tr>
</table>

<p align="center">
  <strong>Disclaimer:</strong> This documentation is for educational purposes and reflects practical activities performed within an authorized testing scope.
</p>

<p align="center">
  <em>Learning. Practicing. Securing.</em>
</p>
