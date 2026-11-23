# Cyber Kill Chain

The Cyber Kill Chain describes the stages of a typical cyberattack, from initial research through the attacker’s final objective.

## 1. Reconnaissance

Attackers gather information about their target using search engines, websites, social media, and other available sources.

- **Passive reconnaissance:** Collecting information without directly interacting with the target.
- **Active reconnaissance:** Directly interacting with the target’s systems or infrastructure.

## 2. Weaponization

The attacker prepares the tools or malicious content needed for the attack.

Important terms:

- **Malware:** Malicious software.
- **Exploit:** Code or a technique that takes advantage of a vulnerability.
- **Payload:** The action or functionality delivered by the exploit or malware.

## 3. Delivery

The attacker delivers the malicious content to the target.

Examples include:

- Phishing emails
- Infected USB drives
- Watering-hole attacks, such as compromised websites visited by the target

## 4. Exploitation

The attacker takes advantage of a vulnerability or tricks the target into executing malicious content.

Examples include:

- Known CVEs
- Zero-day vulnerabilities
- Malicious macros

Exploitation does not always mean malware successfully executes. It means the attacker exploits a weakness to achieve an objective.

## 5. Installation

The attacker installs malware or establishes persistence so they can maintain access.

- A **backdoor** is one possible method of establishing persistence.
- A **web shell** is malicious script placed on a compromised web server to enable remote interaction.

## 6. Command and Control (C2)

The compromised system communicates with attacker-controlled infrastructure, allowing the attacker to send commands and receive information.

C2 does not necessarily mean the attacker has full virtual access to the system; it provides a communication channel.

## 7. Actions on Objectives

This is the final stage. The attacker carries out their actual goal, such as:

- Stealing confidential information
- Encrypting files using ransomware
- Disrupting services
