# Digital Forensics
**Forensics** is the **application of science to investigate** crimes and establish facts. With the use and spread of digital systems a new branch of forensics was born to investigate related crimes: _digital forensics_.

In defensive security, the focus of digital forensics shifts to analyzing evidence of an attack and its perpetrators and other areas such as intellectual property theft, cyber espionage, and possession of unauthorized content. Consequently, digital forensics will focus on different areas, such as:
- File System: Analyzing a digital forensics image (low-level copy) of a system’s storage reveals much information, such as installed programs, created files, partially overwritten files, and deleted files.
- System memory: If the attacker runs their malicious program in memory without saving it to the disk, taking a forensic image (low-level copy) of the system memory is the best way to analyze its contents and learn about the attack.
- System logs: Each client and server computer maintains different log files about what is happening. Log files provide plenty of information about what happened on a system. Even if the attacker tries to clear their traces, some traces will remain.
- Network logs: Logs of the network packets that have traversed a network would help answer more questions about whether an attack is occurring and what it entails.

# Incident response
An _incident_ usually refers to a data breach or cyber attack; in some cases, it can be something less critical, such as a misconfiguration, an intrusion attempt, or a policy violation.

Examples of a cyber attack include an attacker making our network or systems inaccessible, **defacing** (changing) the public website, and **data breach** (stealing company data). 

**Incident response** specifies the methodology that should be followed to **handle cyber attacks**. 

The four major phases of the incident response process are:
1. **Preparation**: This requires a team trained and ready to handle incidents. Ideally, various measures are put in place to prevent incidents from happening in the first place.
2. **Detection and Analysis**: The team has the necessary resources to detect any incident; moreover, it is essential to analyze any detected incident further to learn about its severity.
3. **Containment, Eradication, and Recovery**: Once an incident is detected, it is crucial to stop it from affecting other systems, eliminate it, and recover the affected systems. For instance, when we notice that a system is infected with a computer virus, we would like to stop (contain) the virus from spreading to other systems, clean (eradicate) the virus, and ensure proper system recovery.
4. **Post-Incident Activity**: After a successful recovery, a report is produced, and the lesson learned is shared to prevent similar future incidents.
![[attachments/b162600f5990f249d921aa0e8b7822f7.png]]

# Malware Analysis
Malware stands for malicious software, it includes many types like:
- A **virus** is a piece of code that attaches itself to a program. It is designed to spread from one computer to another and works by altering, overwriting, and deleting files once it infects a computer. The result ranges from the computer becoming slow to unusable.
- **Trojan Horse** is a program that shows one desirable function but hides a malicious function underneath.
- **Ransomware** is a malicious program that encrypts the user’s files to make them pay a ransom in exchange of the encryption password.

Malware analysis aims to learn about such malicious programs using various means:
1. **Static analysis** works by inspecting the malicious program without running it. This usually requires solid knowledge of **assembly language**.
2. **Dynamic analysis** works by running the malware in a controlled environment and monitoring its activities. It lets you observe how the malware behaves when running

#tryhackme 