# TryHackMe Pre-Security Progress — What I’ve Completed So Far

Over the past few days, I’ve been working through the TryHackMe Pre-Security path to build a solid foundation before moving into penetration testing.  
Below is a clean summary of the sections I’ve completed so far and what I’ve learned from each of them.

---

# 1. Introduction to Cyber Security

This section was my starting point and helped me understand how the cybersecurity field is structured and what different roles look like.

## Offensive Security
This introduced me to the attacker’s mindset — analyzing systems for weaknesses, understanding how vulnerabilities are found, and how ethical hackers use controlled exploitation to secure organizations.  
The main takeaway: offensive security requires creativity, patience, and problem-solving.

## Defensive Security
Here I learned how defenders protect systems through logs, monitoring, threat detection, policies, and incident response.  
Defensive work is more process-driven and relies heavily on visibility and consistent analysis.

## Careers in Cybersecurity
I explored different career paths, including:
- SOC Analyst  
- Penetration Tester  
- Threat Hunter  
- DFIR  
- Malware Analyst  
- Cloud Security  

This gave me a clear understanding of where different skills fit into the industry and helped me identify areas I want to grow into.

---

# 2. Network Fundamentals

This section gave me a strong technical base and helped me understand how devices communicate across networks.

## What is Networking
I learned how computers exchange data using IP addressing, routing, and switching.  
Understanding how data moves across networks is essential for both attacking and defending systems.

## Introduction to LAN
LANs are internal networks like homes, colleges, or offices.  
I now understand the difference between:
- switches (handle internal traffic)
- routers (connect LANs to external networks)

## OSI Model
This section taught me to think about networking in layers.  
Breaking down communication into layers makes troubleshooting and understanding attacks much easier.

## Packets and Frames
This part explained:
- Packets carry IP-level information  
- Frames carry MAC-level information  

Seeing the difference helped me visualize what actually moves across a network.

## Extending Your Network
This covered how networks scale using routers, switches, subnets, and access points.  
It gave me a clearer picture of how enterprise environments are built.

---

# 3. How the Web Works

This section tied together networking fundamentals with how the internet actually functions.

## DNS in Detail
I learned how domain names get converted into IP addresses and how DNS queries move through:
- root servers  
- TLD servers  
- authoritative servers  

This section also highlighted why DNS is a common target for attacks.

## HTTP in Detail
Key things I understood:
- HTTP request methods (GET, POST, PUT, DELETE)  
- status codes (200, 301, 404, 500, etc.)  
- how requests and responses are structured  
- cookies and why HTTP is stateless  

These concepts are directly relevant to web penetration testing.

## How a Website Works
This section connected frontend, backend, browsers, and servers.  
It helped me understand how data flows and why vulnerabilities appear at different stages.

## Putting It All Together
This summary made the entire process very clear:
1. User enters a URL  
2. DNS resolves the domain  
3. Browser sends an HTTP request  
4. Server responds  
5. Packets move through layers  
6. Browser renders the final webpage  

Understanding this full flow is crucial before moving to offensive web security.

---

# Summary of My Progress

So far, I’ve completed three main sections of the Pre-Security path:
- Introduction to Cyber Security  
- Network Fundamentals  
- How the Web Works  

I now have a solid foundation in networking basics, DNS/HTTP, and the core concepts behind cyber roles.  
Next, I’ll be starting **Linux Fundamentals** and **Windows Fundamentals**, where I plan to include screenshots and command examples as well.
# Continuing My TryHackMe Journey — Linux & Windows Fundamentals

After completing the first three foundational sections of the Pre-Security path, I moved on to the next major components: **Linux Fundamentals** (Parts 1, 2, and 3) and **Windows Fundamentals** (Parts 1, 2, and 3). These modules helped me understand both operating systems from a practical and security-focused perspective.

---

## Linux Fundamentals (1, 2, and 3)

Working through the Linux modules gave me hands-on experience with the terminal, file systems, permissions, system processes, and essential administrative tools. Linux is heavily used in cybersecurity, so building comfort with the command line is important before moving toward penetration testing.

### Linux Fundamentals 1  
This module helped me get familiar with Linux navigation and the directory structure.

**What I learned:**  
- Linux directory hierarchy (/home, /etc, /var, /bin)  
- Terminal basics: ls, cd, pwd  
- Reading files using cat, less, head, tail  
- Creating and manipulating files  
- Understanding absolute vs relative paths  

### Linux Fundamentals 2  
This part covered permissions, users, and deeper command-line operations.

**Key learning points:**  
- File permissions and modifying them (chmod, chown, chgrp)  
- User and group management  
- Using sudo for privileged actions  
- Hard and symbolic links  
- Useful commands: cp, mv, rm, mkdir, rmdir, grep, find  
- Editing with nano and vim  

### Linux Fundamentals 3  
This module focused on system services, processes, and troubleshooting tools.

**Key takeaways:**  
- Process monitoring (ps, top, htop, kill)  
- Managing services with systemctl  
- Analyzing system logs in /var/log  
- Environment variables  
- Package management using apt  
- Network commands (ip, ifconfig, netstat, ss)  

By the end of these modules, I gained confidence navigating and managing Linux from the terminal.

---

## Windows Fundamentals (1, 2, and 3)

Since many environments run on Windows, understanding its internal structure, tools, and configurations is essential. These modules helped me learn how Windows organizes system files, permissions, logs, and user accounts.

### Windows Fundamentals 1  
This module introduced core Windows components.

**Key things I learned:**  
- Navigating File Explorer and system directories  
- Control Panel vs Settings  
- Important folders like System32, Users, Program Files  
- Basic use of Task Manager  
- Introduction to Command Prompt  

### Windows Fundamentals 2  
This section focused on users, permissions, and system configurations.

**What I learned:**  
- Managing users and groups  
- Using “net user” commands  
- NTFS permissions  
- Introduction to the Windows Registry  
- Basics of Local Security Policy  

### Windows Fundamentals 3  
This part covered monitoring and administrative tools used in real Windows environments.

**Key takeaways:**  
- Event Viewer and log analysis  
- Managing services using services.msc  
- System information with msinfo32  
- Task Scheduler basics  
- Introduction to PowerShell  
- Windows Defender and Firewall basics  

These tools are essential for both security monitoring and understanding how attackers interact with Windows systems.

---

## Summary

With Linux and Windows Fundamentals completed, I’ve now finished all the core foundation sections of the Pre-Security path. These operating system fundamentals are important before moving into more advanced concepts like privilege escalation, exploitation techniques, and penetration testing pathways. I will continue documenting each step as I progress deeper into cybersecurity.
