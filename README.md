# cyber-security
## Vocabulary
# Module 1 (Welcome to Cyber Security)
**Cybersecurity (or security):** The practice of ensuring confidentiality, integrity, and availability of information by protecting networks, devices, people, and data from unauthorized access or criminal exploitation.

**Threat Actor:** Any person or group who presents a security risk.

**Benefits of Security:**
* Protects against external and internal threats
* Meets regulatory compliance
* Maintain and improves business productivity
* Reduces expenses
* Maintains brand trust

**Common Job Titles**
* Security Analyst or Specialist
* Cybersecurity Analyst or Specialist
* Security Operations Center (SOC) Analyst
* Information Security Analyst

**Security Analyst Responsibilities:**
* Protecting computer and network systems
* Installing prevention softwares
* Conducting periodic security audits

**Operations:** Responding to detections and doing investigations

**Projects:** Working with other teams to build new detections or improve the current detections

"A playbook is a list how to go through a certain detection, and what the analyst needs to look at in order to investigate those incidents."

**Common Cybersecurity Terminology**
* **Compliance**: is the process of adhering to internal standards and external regulations and enables organizations to avoid fines and security breaches.
* **Security frameworks**: are guidelines used for building plans to help mitigate risks and threats to data and privacy.
* **Security controls**: are safeguards designed to reduce specific security risks. They are used with security frameworks to establish a strong security posture.
* **Security posture**: is an organization's ability to manage its defense of critical assets and data and react to change. A strong security posture leads to lower risk for the organization.
* **A threat actor**: or malicious attacker, is any person or group that presents a security risk. This risk can relate to computers, applications, networks, and data.
* **An internal threat**: can be a current or former employee, an external vendor, or a trusted partner who poses a security risk. At times, an internal threat is accidental. For example, an employee who accidentally clicks on a malicious email link would be considered an accidental threat. Other times, the internal threat actor *intentionally* engages in risky activities, such as unauthorized data access.
* **Network security**: is the practice of keeping an organization's network infrastructure secure from unauthorized access. This includes data, services, systems, and devices that are stored in an organization's network.
* **Cloud security**: is the process of ensuring that assets stored in the cloud are properly configured, or set up correctly, and access to those assets is limited to authorized users. The cloud is a network made up of a collection of servers or computers that store resources and data in remote physical locations known as data centers that can be accessed via the internet. Cloud security is a growing subfield of cybersecurity that specifically focuses on the protection of data, applications, and infrastructure in the cloud.
* **Programming**: is a process that can be used to create a specific set of instructions for a computer to execute tasks. These tasks can include:
  * Automation of repetitive tasks (e.g., searching a list of malicious domains)
  * Reviewing web traffic
  * Alerting suspicious activity

**Security Analyst transferable skills**
* Communication
* Collaboration
* Analysis
* Problem-solving

**Security Analyst technical skills**
* Programming languages
* SIEM tools
* Data analysis

**Personally Identifiable Information (PII)**: Any information used to infer an individual's identity.

**Sensitive Personally Identifiable Information (SPII)**: A specific type of PII that falls under stricter handling guidelines.

**Threat**: Any circumstance or event that can negatively impact assets.


# Module 2 (Evolution of Cyber Security)

**Computer Virus**: Malicious code written to interfere with computer operations and cause damage to data and software.

**Malware**: A software designed to harm devices or networks.
- **Viruses**: Malicious code written to interfere with computer operations and cause damage to data and software. A virus needs to be initiated by a user (i.e., a threat actor), who transmits the virus via a malicious attachment or file download. When someone opens the malicious attachment or download, the virus hides itself in other files in the now infected system. When the infected files are opened, it allows the virus to insert its own code to damage and/or destroy data in the system.
- **Worms**: Malware that can duplicate and spread itself across system on its own. In contract to a virus, a worm does not need to be downloaded by a user. Instead, it self-replicates and spreads from an already infected computer to other devices on the same network.
- **Ransomware**: A malicious attack where threat actors encrypt an organization's data and demand payment to restore access.
- **Spyware**: Malware that's used to gather and sell information without consent. Spycare can be used to access devices. This allows threat actors to collect personal data, such as private emails, texts, voice and image recordings, and locations.

**Social engineering**: A manipulation technique that exploits human error to gain private information, access, or valuables.
Some of the most common types of social engineering attacks today include:
- **Social media phishing**: A threat actor collects detailed information about their target from social media sites. Then, they initiate an attack.
- **Watering hole attack**: A threat actor attacks a website frequently visited by a specific group of users.
- **USB Baiting**: A threat actor strategically leaves a malware USB stick for an employee to find and install, to unknowningly infect a network.
- **Physical social engineering**: A threat actor impersonates an employee, customer, or vendor to obtain unauthorized access to a physical location.

**Phishing**: The use of digital communications to trick people into revealing sensitive data or deploying malicious software.
Some of the most common types of phishing attacks today include:
- **Business Email Compromise (BEC)**: A threat actor sends an email message that seems to be from a known source to make a seemingly legitimate request for information, in order to obtain a financial advantage.
- **Spear phishing**: A malicious email attack that targets a specific user or group of users. The email seems to originate from a trusted source.
- **Whaling attack**: A form of spear phishing. Threat actors target company executives to gain access to sensitive data.
- **Vishing**: The exploitation of electronic voice communication to obtain sensitive information or to impersonate a known source.
- **Smishing**: The use of text messages to trick users, in order to obtain sensitive information or to impersonate a known source.

During a data breach, you have to stay calm.
"The first thing you're going to do is, contain the breach."

**The eight CISSP security domains**
**Eight Domains**
1. **Security and Risk Management**: Defines security goals and objectives, risk mitigation, compliance, business continuity, and the law.
2. **Asset Security**: Secures digital and physical assets. It's also related to the storage, maintenance, retention, and destruction of data.
3. **Security Architecture and Engineering**: Optimizes data security by ensuring effective tools, systems, and processes are in place.
4. **Communication and Network Security**: Manage and secure physical networks and wireless communications.
5. **Identity and Access Management**: Keeps data secure, by ensuring users follow established policies to control and manage physical assets, like office spaces, and logical assets, such as networks and applications.
6. **Security Assessment and Testing**: Conducting security control testing, collecting and analyzing data, and conducting security audits to monitor for risks, threats, and vulnerabilities.
7. **Security Operations**: Conducting investigations and implementing preventative measures.
8. **Software Development Security**: Uses secure coding practices, which are a set of recommended guidelines that are used to create secure applications and services.

**Determine the type of attack**

**Attack Types** <br>
Password attack: A password attack is an attempt to access password-secured devices, systems, networks, or data. Some forms of password attacks that I'll learn about later are:
- Brute force
- Rainbow table

Password attacks fall under the communication and network security domain

- **Social engineering attack**: Social engineering is a manipulation technique that exploits human error to gain private information, access, or valuables. Some forms of social engineering attacks that I will continue to learn about throughout are:
   - Phishing
   - Smishing
   - Vishing
   - Spear phishing
   - Whaling
   - Social media phishing
   - Business Email Compromise (BEC)
   - Waterin hole attack
   - USB (Universal Serial Bus) baiting
   - Physical social engineering
Some social engineering attacks are related to the security and risk management domain.

- **Physical attack**: A physical attack is a security incident that affects not only digital but also physical environments where the incident is deployed. Some forms of physical attacks are:
   - Malicious USB cable
   - Malicious flash drive
   - Card cloning and skimming
Physical attacks fall under the asset security domain.

- **Adversarial artificial intelligence**: Adversarial artificial intelligence is a technique that manipulates artificial intelligence and machine learning technology to conduct attacks more efficiently. Adversarial artificial intelligence falls under both the communication and network security and the identity and access management domains.

- **Supply-chain attack**: A supply-chain attack targets systems, applications, hardware, and/or software to locate a vulnerability where malware can be deployed. Because every item sold undergoes a process that involves third parties, this means that the security breach can occur at any point in the supply chain. These attacks are costly because they can affect multiple organizations and the individuals who work for them. Supply-chain attacks can fall under several domains, including but not limited to the security and risk management, security architecture and engineering, and security operations domains.

- **Cryptographic attack**: A cryptographic attack affects secure forms of communication between a sender and intended recipient. Some forms of cryptographic attacks are:
   - Birthday
   - Collision
   - Downgrade
Cryptographic attacks fall under the communication and network security domain.

- **Key takeaways**: The eight CISSP security domains can help an organization and its security team fortify against and prepare for a data breach. Data breaches range from simple to complex and fall under one or more domains. Note that the methods of attack discussed are only a few of many. These and other types of attacks will be discussed throughout.

**Reading: Understand attackers** <br>
Previously, I was introduced to the concept of threat actors. As a reminder, a threat actor is any person or gorup who presents a security risk. In this reading, I'll learn about different types of threat actors. I will also learn about their motivations, intentions, and how they've influenced the security industry. <br>

**Threat actor types**: <br>
**Advanced Persistent Threat**: Advanced Persistent Threats (APTs) have significant expertise accessing an organization's network without authorization. APTs tend to research their targets (e.g., large corporations or government entities) in advance and can remain undetected for an extended period of time. Their intentions and motivations can include:

- Damaging critical infrastructure, such as the power grid and natural resources
- Gaining access to intellectual property, such as trade secret or patents

**Insider threats**: Insider threats abuse their authorized access to obtain data that may harm an organization. Their intentions and motivations can include:

- Sabotage
- Corruption
- Espionage
- Unauthorized data access or leaks

**Hacktivists**: Hacktivists are threat actors that are driven by a political agenda. They abuse digital technology to accomplish their goals, which may include:

- Demonstrations
- Propaganda
- Social change campaigns
- Fame

**Hacker types**: A hacker is any person who uses computers to gain access to computer systems, network, or data. They can be beginner or advanced technology professionals who use their skills for variety of reasons. There are three main categories of hackers:
* Authorized hackers are also called ethical hackers. They follow a code of ethics and adhere to the law to conduct organizational risk evaluations. They are motivated to safeguard people and organizations from malicious threat actors.
* Semi-authorized hackers are considered researchers. They search for vulnerabilites but don't take advantage of the vulnerabilities they find.
* Unauthorized hackers are also caled unethical hackers. They are malicious threat actors who do not follow or respect the law. Their goal is to collect and sell confidential data for financial gain.

**Note**: There are multiple hackers types that fall into one or more of these three categories.

New and unskilled threat actors have various goals, including:
* To learn and enhance their hacking skills
* To seek revenge
* To exploit security weakness by using existing malware, programming scripts, and other tactics

Other types of hackers are not motivated by any particular agenda other than completing the job they were contracted to do. These type of hackers can be considered unethical or ethical hackers. They have been known to work on both illegal and legal tasks for pay.

Therer are also hackers who consider themselves vigilantes. Their main goal is to protect the world from unethical hackers.

**Key takeways**
Threat actors are defined by their malicious intent and hackers are defined by their technical skills and motivations. Understanding their motivations and intentions will help me be better prepared to protect your organization and the people it serves from malicious attacks carried out by some of these individuals and groups.

# Module 3 (Protect Against Threats, Risks, & Vulnerabilites)
**Learning Objectives**
* Define security frameworks and controls
* Define the CIA triad and NIST CSF
* Discuss how the CIA triad and NIST CSF are used to develop procedures and processes to address security threats, risks, & vulnerabilites
* Explain security ethics

**Frameworks and Controls** <br>
**Security frameworks**: Guidelines used for building plans to help mitigate risk and threats to data and privacy.

**Purpose of security frameworks**
* Protecting Personally Identifiable Information (PII)
* Securing financial information
* Identifying security weakness
* Managing organizational risks
* Aligning security with business goals

**Components of security frameworks**
1. Identifying and documenting security goals
2. Setting guidelines to acheive security goals
3. Implementing security processes
4. Monitoring and communicating results

**Security controls**: Safeguards designed to reduce specific security risks.

**CIA Triad**: A foundational model that helps inform how organizations consider tisk when setting up systems and security policies.

**Confidentiality**: Only authorized users can access specific assets or data.
**Integrity**: Data is correct, authentic, and reliable.
**Availability**: Data is accessible to those who are authorized to access it.
**Asset**: An item perceived as having value to an organization.

**NIST Cybersecurity Framework (CSF)**: A voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk.

**Controls, frameworks, and compliance** <br>
**How controls, frameworks, and compliance are related** <br>
The confidentiality, integrity, and availability (CIA) triad is a model that helps inform how organizations consider risk when setting up systems and security policies.

**Ethics in Cybersecurity** <br>
**Security ethics**: Guidelines for making appropriate decisions as a security professional.

**Ethical principles in security**
* Confidentiality
* Privacy protection means safeguarding personal information from unauthorized use.
* Laws are rules that are recognized by a community and enforced by a governing entity.

**Ethical concepts that guide cybersecurity decisions** <br>
As a future security professional, ethics will play a large role in my daily work. Understanding ethics and laws will help me make correct choices if and when you encounter a security threat or an incident that results in a breach.

# Module 4 (Cybersecurity Tools & Programming Languages)
**Learning Objectives** <br>
* Identify common tools used by entry-level security analysts
* Identify the purposes of commonly used tools
* Identify commonly used programming languages and how entry-leve security analysts interact with those languages
* Discuss how entry-level security analysts use tools and programming languages to mitigate risk

**Important cybersecurity tools** <br>
**Log**: A record of events that occur within an organization's systems.
**SIEM tool**: An application that collects and analyzes log data to monitor critical activities in an organization.

**Other key security tools**
* **Playbook**: A manual that provides details about any operational action.
* **Network protocol analyzer (packet sniffer)**: A tool designed to capture and analyze data traffic within a network.
   - tcpdump, Wireshark
 
**Core cyberesecurity knowledge and skills** <br>
**Programming**: Used to create a specific set of instructions for a computer to execute tasks.
**Linux**: An open-source operating system.
**Structured Query Language (SQL)**: A programming language used to create, interact with, and request information from a database.
**Database**: An organized collection of information or data.
**Python**: Used to perform tasks that are repetitive and time-consuming, and that require a high level of detail and accuracy.

# Module 1.2 (CISSP)
**More about the CISSP security domains** <br>
**Learning objectives** <br>
* CISSP's eight security domains
* Threats, risks, and vulnerabilities
* Layers of the web
* The NIST Risk Management Framework (RMF)

**Security posture**: An organization's ability to manage its defense of all critical assets and data, and react to change <br>
**Security and risk management**: Focused on defining security goals and objectives, risk mitigation, compliance, business continuity, and legal regulations. <br>
**Risk mitigation**: The process of having the right procedures and rules in place to quickly reduce the impact of a risk like a breach <br>
**Business continuity**: An organization's ability to maintain their everyday productivity by establishing risk disaster recovery plans <br>
**Asset security**: Focused on securing digital and physical assets. It's also related to the storage, maintenance, retention, and destruction of data <br>
**Security architecture and engineering**: Focused on optimizing data security by ensuring effective tools, systems, and processes are in place to protect an organization's assets and data <br>
**Shared responsibility**: All individuals within an organization take an active role in lowering risk and maintaining both physical and virtual security. <br>
**Communication and network security**: Focused on managing and securing physical networks and wireless communications <br>
**Identity and Access Management (IAM)**: Focused on access and authorization to keep data secure, by making sure users follow established policies to control and manage assets. <br>
**Components of IAM**

   - Identification
   - Authentication
   - Authorization
   - Accountability

**Security Assessment and Testing**: Focused on conducting security control testing, collecting and analyzing data, and conducting security audits to monitor for risks, threats, and vulnerabilities <br>
**Security Operations**: Focused on conducting investigations and implementing preventative measures <br>
**Software Development Security**: Focused on using secure coding practices <br>

**Navigate threats, risks, and vulnerabilities** <br>
**Threat**: Any circumstance or event that can negatively impact assets. <br>
**Social Engineering**: A manipulation technique that exploits human error to gain private information, access, or valuables <br>
**Risk**: Anything that can impact the Confidentiality, Integrity, and Availability (CIA Triad) of an asset. <br>
**Low-risk Asset**: Information that would not harm the organization's reputation or ongoing operations, and would not cause financial damage if compromised <br>
**Medium-risk Asset**: Information that's not available to the public and may cause some damage to the organization's finances, reputation, or ongoing operations <br>
**High-risk Asset**: Information protected by regulations or laws, which if compromised would have a severe negative impact on an organization's finances, ongoing operations, or reputation <br>
**Vulnerability**: A weakness that can be exploited by a threat <br>
**Ransomware**: A malicious attack where threat actors (TAs) encrypt an organization's data and demand payment to restore access

**Layers of the web** <br>
- **Surface web**: Most people use, contains content that can be accessed using a web browser.
- **Deep web**: Generally requires authorization to access it.
- **Dark web**: Can only be accessed by using special software.

**Kep impacts (threats, risks, and vulnerabilities)** <br>
* Financial
* Identity theft
* Reputation

**Risk Management Framework (RMF)**
* **Prepare**: Activities that are necessary to manage security and privacy risks before a breach occurs
* **Categorize**: Used to develop risk management processes and tasks.
* **Select**: Choose, customize, and capture documentation of the controls that protect an organization.
* **Implement**: Implement security and privacy plans for the organization.
* **Assess**: Determine if established controls are implemented correctly.
* **Authorize**: Being accountable for the security and privacy risks that may exist in an organization.
* **Monitor**: Be aware of how systems are operating.

