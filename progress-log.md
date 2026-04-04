Day 1 – Lab Environment Set
-- Installed and verified VMware Workstation as the virtualization platform for creating the cybersecurity lab environment.

-- Set up Kali Linux as the attacker machine. Ensured the system is running properly and ready for performing security testing and analysis.

-- Installed Metasploitable2 as the target machine. This vulnerable machine will be used to practice penetration testing techniques in a safe and controlled environment.

-- Understood the purpose of using vulnerable machines like Metasploitable2 and DVWA for ethical hacking practice.

-- Configured a private network using Host-Only Adapter to ensure isolated communication between attacker (Kali Linux) and target (Metasploitable2).

-- Verified network connectivity between machines using basic commands like ping to confirm successful lab setup.

-- Gained understanding of how isolated lab environments help in safe cybersecurity experimentation without affecting external systems.

-- Successfully completed initial lab setup required for further cybersecurity tasks.

 Outcome:  A fully functional virtual lab environment with attacker and target machines ready for testing.

Day 2 – Cybersecurity Basics

-- Studied the CIA Triad, which is the core foundation of cybersecurity:

   -- Confidentiality:
      Ensuring that sensitive information is accessible only to authorized users.
      Learned about methods like encryption, authentication, and access control to protect data from unauthorized access.

   -- Integrity:
      Ensuring that data remains accurate, consistent, and unaltered during storage or transmission.
      Explored how hashing and validation mechanisms help detect unauthorized changes.

   -- Availability:
      Ensuring that systems, networks, and data are available to users when required.
      Understood how backups, redundancy, and protection against attacks like DDoS help maintain availability.

-- Explored different types of cyber threats in detail:

   -- Phishing:
      A social engineering attack where attackers trick users into revealing sensitive information through fake emails or websites.

   -- Malware:
      Malicious software designed to damage or gain unauthorized access to systems, including viruses, worms, and trojans.

   -- Ransomware:
      A type of malware that encrypts user data and demands payment for decryption, causing serious financial and operational damage.

   -- Distributed Denial of Service (DDoS):
      An attack where multiple systems flood a target server with traffic, making it unavailable to legitimate users.

   -- SQL Injection:
      A web-based attack where malicious SQL queries are inserted into input fields to manipulate or access database information.

   -- Brute Force Attack:
      A method where attackers try multiple combinations of usernames and passwords to gain unauthorized access.

-- Understood the real-world impact of these attacks:

   -- Data breaches leading to loss of sensitive information
   -- Financial losses for organizations and individuals
   -- Damage to reputation and trust
   -- Legal consequences and compliance issues

-- Learned the importance of cybersecurity best practices:

   -- Using strong and unique passwords
   -- Enabling multi-factor authentication (MFA)
   -- Keeping software and systems updated
   -- Avoiding suspicious links and emails
   -- Implementing proper security policies and awareness

Day 3 – Linux Fundamentals & Essential Commands

-- Gained hands-on understanding of Linux, which is widely used in cybersecurity for penetration testing, server management, and automation  

-- Explored basic Linux file system structure:
   -- /root → Root user directory  
   -- /home → User directories  
   -- /etc → Configuration files  
   -- /var → Logs and variable data  
   -- /bin & /usr/bin → Essential system commands  

-- Learned and practiced essential Linux commands:

   -- pwd → Displays current working directory  
   -- ls → Lists files and directories  
      -- ls -l → Detailed view  
      -- ls -a → Shows hidden files  

   -- cd → Navigate between directories  
      -- cd .. → Move one level up  
      -- cd / → Go to root directory  

   -- mkdir → Create new directory  
   -- rmdir → Remove empty directory  
   -- rm -r → Delete directory with contents  

   -- touch → Create new file  
   -- cp → Copy files  
   -- mv → Move or rename files  

   -- cat → View file content  
   -- nano → Edit files in terminal  

-- Understood file permissions and security:
   -- chmod → Change file permissions  
   -- chown → Change file ownership  

   -- Permission format:
      rwx r-x r--
      (Read, Write, Execute for Owner, Group, Others)

-- Learned importance of Linux in cybersecurity:
   -- Most security tools run on Linux (especially Kali Linux)  
   -- Faster command-line operations compared to GUI  
   -- Better control over system and processes  

-- Practiced commands in Kali Linux terminal to build familiarity  

