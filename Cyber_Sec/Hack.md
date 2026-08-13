# Intro to Cyber_Sec/Ethical Hacking
## 1, CIA triad
- ==**Elements of Information Security**== 
	- The there letter in **CIA triad** stand for **Confidentiality**, **Integrity** and **Availability**.
	- The **CIA triad** is a common model that forms the basis for the **development of security system**.
	- All security measures are based on one or more of these three principles.

		1. ==**Confidentiality** / **ሚስጥራዊነት**== 
			- **Confidentiality** involves the efforts of an organization to make sure **data is kept secret or private**.
			- To accomplish this access to information must be controlled to prevent the **unauthorized sharing of data-whether** intentional or accidental.

		2. ==**Integrity** / **ታማኝነት**== 
			- Integrity involves making sure your data is **trustworthy and free from tampering/change**.
			- The integrity of your data is maintained only if the data is **authentic, accurate and reliable**.

		3. ==**Availability** / **ተገኝነት**== 
			- Availability means information resources are **accessible when you need them**.
			- Even if data is kept confidential and its integrity maintained, it is often useless unless it is **available to those in the organization and the customer they serve**.
			- This means the system, network, and application **must be functioning as they should and when they should**.

![[Pasted image 20260805122035.png]]



## 2, Phases of hacking
- Both **malicious Cyber_Criminals** and **Cyber_Security professionals** follow a systematic playbook known as the **5 Phases of Hacking** to compromise networks, systems, and data.
- Ethical hacking follows a structured process to identify vulnerabilities in systems, networks, and applications before malicious attackers exploit them. This methodology helps security professionals **simulate real-world attacks** in a controlled and authorized environment to strengthen Cyber_Security defenses.
- Helps identify security weaknesses before attackers can exploit them.
- Simulates real-world **Cyber_Attacks** in a controlled and legal environment.
- Assists organizations in **improving** their security infrastructure.
- Reduces the risk of data breaches and cyber threats.

	1. ==**Reconnaissance (Foot_printing Phase)**== 
		- Reconnaissance is the first phase of ethical hacking where security professionals gather information about the target system or organization. The goal of this phase is to understand the target environment and identify potential entry points for security testing.
		- Collects information such as domain names, IP addresses, and DNS records.
		- Identifies technologies, servers, and network infrastructure used by the target.
		- Uses publicly available sources like websites, search engines, and social media.
		- Helps ethical hackers understand the system before performing further security testing.

		- ==**Types of Reconnaissance**==
			- ==**1. Passive Reconnaissance**==
				- Passive reconnaissance involves collecting information without directly interacting with the target system. This method is difficult to detect because the hacker relies on publicly available sources.
				- ==**Examples:**==
				- Searching company information on Google
				- Checking employee profiles on LinkedIn
				- Reviewing public DNS records
				- Using WHOIS lookup services

			- ==**2. Active Reconnaissance**==
				- Active reconnaissance involves direct interaction with the target system to gather information. This may include scanning networks or querying servers.
				- ==**Examples:**== 
				- Ping sweeps to detect active hosts.
				- DNS queries to identify servers.
				- Network scanning to detect services.

	![[Pasted image 20260805125019.png]]


	2. ==**Scanning**== 
		- Scanning is the second phase of ethical hacking where the gathered information is analyzed to identify potential vulnerabilities in the target system. In this phase, ethical hackers examine the system to discover open ports, running services, and possible security weaknesses.
		- Identifies open ports and active services on the target system.
		- Detects operating systems and software versions running on the network.
		- Finds vulnerabilities and misconfigurations that attackers could exploit.
		- Helps determine possible entry points for further security testing.

		- ==**Types of Scanning**== 
			- **1. Port Scanning**: Port scanning identifies open ports and services running on a system.
			- **2. Vulnerability Scanning:** This scanning detects known vulnerabilities in operating systems, applications, and network services.
			- **3. Network Mapping:** Network mapping identifies devices connected to the network and how they communicate with each other.

	![[Pasted image 20260805140205.png]]

	3. ==**Gaining Access**== 
		- In this phase, the ethical hacker attempts to exploit the vulnerabilities discovered during scanning. The goal is to determine whether these vulnerabilities can actually be used to gain unauthorized access to the system. This phase simulates real-world Cyber_attacks in a controlled environment.

		- ==**Common Exploitation Techniques**== 
			- **SQL Injection:** Exploiting database vulnerabilities.
			- **Cross-Site Scripting (XSS):** Injecting malicious scripts into web applications.
			- **Password Cracking:** Breaking weak passwords.
			- **Buffer Overflow Attacks:** Exploiting memory vulnerabilities.
			- **Exploiting outdated software vulnerabilities.** 

	![[Pasted image 20260805140258.png]]

	4. ==**Maintaining Access**== 
		- Maintaining Access is the phase where the ethical hacker evaluates how long an attacker could remain inside a compromised system. The goal is to assess the potential impact of the attack and understand the level of control an attacker could achieve.
		- Tests whether privileges can be escalated to administrator or root level.
		- Checks if the attacker can move laterally across other systems in the network.
		- Identifies access to sensitive data or confidential information.
		- Evaluates how long unauthorized access can be maintained in the system.

		- ==**Activities Performed in Maintaining Access**== 
			- **Privilege Escalation:** Gaining higher-level permissions such as administrator or root access.
			- **Lateral Movement:** Moving from one compromised system to another within the network.
			- **Persistence:** Maintaining long-term access to the system.
			- **Data Exfiltration:** Accessing sensitive data.

	![[Pasted image 20260805140412.png]]

	5. ==**Covering Tracks**== 
		- Covering Tracks is the phase where an attacker attempts to hide their activities after gaining unauthorized access to a system. The goal is to remove or modify evidence of the attack so that security teams cannot easily detect or investigate the intrusion.
		- Deletes or modifies system logs to hide traces of the attack.
		- Hides malicious files, processes, or backdoors from security tools.
		- Alters file timestamps to confuse forensic investigations.
		- Helps attackers remain undetected and maintain stealth within the system.

		- ==**Activities Performed in This Phase**== 
			- **Log Deletion:** Attackers remove or modify system logs to hide traces of their activities.
			- **File and Process Hiding:** Malicious files or processes are hidden to avoid detection by security tools.
			- **Timestamp Manipulation:** Changing file timestamps to make it difficult to track when the attack happened.
			- **Backdoor Concealment:** Hiding backdoors or persistent access mechanisms to maintain undetected access.

	![[Pasted image 20260805140452.png]]



## 3, Penetration Testing
- Penetration Testing or pen_testing is a practice where a simulated [**cyber attack**](https://www.geeksforgeeks.org/ethical-hacking/what-is-a-cyber-attack/)  is conducted on your [computer systems](https://www.geeksforgeeks.org/computer-organization-architecture/computer-system-level-hierarchy/) to **find and fix any weak spots before real attackers can exploit them**.
- Penetration Testing is a method of evaluating the Security of an information system or network by simulating an real world attack to:
- find vulnerability
- security measures
- documenting and reporting preparation

- Why we need Penetration testing?
	- identification of threats
	- security protections and controls
	- assessment of organization's security
	- evaluation of network security
	- upgradation of infrastructure
	- d
	- s
	- ## Penetration Testing Stages

Penetration testing follows a structured process to identify vulnerabilities, validate security controls, and provide recommendations for improving security.

- ****Planning and Reconnaissance****: In this stage, the scope and objectives of the test are defined. The tester collects information about the target system, such as domains, IPs, technologies, and possible entry points.
- ****Scanning****: The target system is scanned to identify open ports, running services, and known vulnerabilities. This helps understand how the system behaves and where weaknesses may exist.
- ****Gaining Access****: The tester attempts to exploit identified vulnerabilities to gain unauthorized access to the system. This shows how an attacker could reach sensitive data or critical functions.
- ****Maintaining Access****: After gaining access, the tester checks whether access can be maintained over time. This helps assess the severity of the vulnerability and the risk of long-term compromise.
- ****Analysis and Reporting****: All findings are documented in a report that includes vulnerabilities, their impact, supporting evidence, and recommended fixes. This helps the organization improve its security posture.


## Penetration Testing Methods

- ****External Testing:**** Targets internet-facing systems such as websites, servers, and DNS to find vulnerabilities that attackers could exploit from outside the organization.
- ****Internal Testing:**** Simulates attacks from within the organization’s network to test internal security controls and identify insider or compromised-account risks.
- ****Blind Testing:**** The tester has very limited information about the system, which helps simulate a realistic external attack and evaluate detection capabilities.
- ****Double-Blind Testing:**** Neither the tester nor the security team knows the full test details in advance, making it useful for assessing real-time response to unexpected attacks.
- ****Targeted Testing:**** The tester and security team work together during the assessment, allowing quick identification of vulnerabilities and better communication throughout the process.


## Types of Penetration Testing

Here are the Types of Penetration Testing:

- ****Black Box Penetration Testing:**** In black box testing, the tester has no prior knowledge of the target system. It simulates a real-world external attack and helps identify vulnerabilities from an attacker’s perspective. test as an attacker.
- ****Grey Box Penetration Testing:**** In grey box testing, the tester has partial knowledge of the system, such as limited access or network details. It allows more focused testing while combining both external and internal viewpoints. test as ans user.
- ****White Box Penetration Testing:**** In white box testing, the tester has complete knowledge of the system, including source code and architecture. It enables a deep security assessment and helps uncover hidden vulnerabilities and misconfigurations. test as an developer.


## Rules of the Penetration Testing Process

Penetration testing must be conducted safely, ethically, and within agreed boundaries to avoid legal, operational, or security issues.

- Obtain proper written authorization before starting the test
- Clearly define the scope, objectives, timeline, and allowed techniques
- Avoid disrupting systems or causing unnecessary downtime
- Maintain confidentiality of sensitive information discovered during testing
- Document findings responsibly and report vulnerabilities clearly
























## 4, Cyber Security Field Terms
## 5, Jobs with Cyber Security










# Networking
# Network Scanning
# Steganography and Cryptography
# Osint
# Social Engineering
# Anonymity & DarkWeb
# Malware Threats
# Network Hacking
# Wireless Network Hacking
# System Hacking
# CTF

