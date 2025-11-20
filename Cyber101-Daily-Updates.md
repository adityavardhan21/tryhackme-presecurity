## Day 1 — Search Skills (Nov 17, 2025)

Today I completed the **Search Skills** module from the Cyber101 path on TryHackMe.  
This module focused on developing the ability to find technical information quickly and accurately — a skill every cybersecurity professional depends on.

### What I learned

#### 🔍 Using Search Engines Effectively
I learned how to structure search queries to get relevant technical results faster:
- Using quotes `" "` for exact search terms  
- Using operators like `AND`, `OR`, and `-` to narrow down results  
- Searching for specific file types (e.g., `filetype:pdf`)  
- Searching within specific websites (e.g., `site:docs.python.org`)  

These are small but powerful techniques that save a lot of time when researching vulnerabilities, commands, protocols, or tools.

#### 📚 Reliable Technical Sources
The module reinforced the importance of referring to trusted and authoritative sources, such as:
- Official documentation pages  
- Developer blogs  
- Security research blogs  
- Vendor knowledge bases  
- Community forums (StackOverflow, Reddit, etc.)  

In cybersecurity, bad or outdated information can lead to mistakes, so learning how to filter sources is important.

#### 🔧 Searching for Commands, Errors & Tools
I practiced searching for:
- Linux/Windows commands and their usage  
- Specific error messages  
- Tool installation guides  
- CVE details  
- Security configurations  

The goal is to build the habit of researching **before** getting stuck.

### Why This Matters in Cybersecurity
Cybersecurity requires constant learning. Threats evolve, tools update, and techniques change.  
Search skills help with:
- Troubleshooting  
- Understanding tools and exploits  
- Investigating vulnerabilities  
- Working faster during CTFs or real-world tasks  

Being able to find the right information quickly is a core skill for penetration testers, analysts, and defenders.

---

This completes Day 1 of my Cyber101 journey.  
Tomorrow, I will continue with the next topic and update this file with my progress. 
## Day 2 Linux Fundamentals  — Cyber101 (Write-Up) (Nov 18 , 2025 )

Over the past sessions, I worked through the *Linux Fundamentals* modules in the **Cyber101** path on TryHackMe. Even though I covered Linux earlier in the Pre-Security path, this time I focused on using it from a practical cybersecurity angle — commands, permissions, navigation, and the basic mindset needed to work in a real system.

This write-up covers everything I completed across Linux Fundamentals 1, 2, and 3.

---

## 1. Linux Fundamentals 1 — Terminal & Navigation

This section focused on getting comfortable with the terminal and learning how to move through the Linux filesystem confidently.

### Key Concepts
- Understanding the Linux directory structure  
- Using the terminal efficiently  
- Relative vs absolute paths  
- Basic file visibility and navigation

### Commands Practiced
```
pwd
ls
ls -la
cd /home
cd ..
```

These commands are simple but essential. Knowing where you are and what’s around you is the foundation of working on any Linux machine.

---

## 2. Linux Fundamentals 2 — Files, Directories & Editing

This section was about hands-on file management and working with text inside the system.

### Key Concepts
- Creating and deleting files/directories  
- Viewing and editing text files  
- Managing data inside the terminal  

### Commands Practiced
```
mkdir practice_dir
touch notes.txt
nano notes.txt
cat notes.txt
rm notes.txt
rmdir practice_dir
```

Being able to quickly open, read, and edit files is crucial during CTFs, penetration tests, and while investigating systems.

---

## 3. Linux Fundamentals 3 — Permissions, Users & Processes

This part connected Linux to real-world cybersecurity. Understanding permissions and processes helps identify misconfigurations and privilege escalation paths.

### Key Concepts
- File and directory permissions  
- User, group, and other access levels  
- Modifying permissions safely  
- Managing running processes  

### Commands Practiced
```
ls -l
chmod 755 script.sh
sudo -l
ps aux
kill <PID>
```

A single incorrect permission or an exposed process can create vulnerabilities. This part helped reinforce why secure configuration matters.

---

## Final Thoughts

Linux appears everywhere in cybersecurity — from servers and CTF machines to real penetration testing environments. The Cyber101 Linux modules strengthened the foundations I’ll rely on in the upcoming sections.

Next step: revisiting Windows Fundamentals, capturing screenshots for both Linux and Windows, and continuing with the rest of the Cyber101 path.

---

# Cyber101 Progress — Windows Fundamentals Completed (Before Active Directory) (Nov 20 , 2025 ) 

I’ve finished all three parts of the **Windows Fundamentals** section in the Cyber101 path on TryHackMe. I’m stopping right before *Active Directory Basics* because it’s an important topic and I want to give it proper time and attention. Here’s everything I’ve covered so far.

---

## 🔹 Windows Fundamentals 1 — Getting Familiar With the System

This section helped me understand how Windows is structured behind the scenes.  
I went through key system components, navigation, and explored how Windows manages files and settings.

### What I learned:
- The Windows directory structure  
- System Information and Control Panel basics  
- User profiles and system settings  
- Navigating File Explorer properly  

---

## 🔹 Windows Fundamentals 2 — CMD & PowerShell Basics

This part focused on using the command-line tools in Windows — **CMD** and **PowerShell**.  
I learned how system information, networking details, and basic operations can be done directly through commands.

### Commands I practiced (CMD):
```
whoami
ipconfig
dir
```

### Commands I practiced (PowerShell):
```
Get-ChildItem
Get-Process
```

These tools are essential in cybersecurity for enumeration, investigation, and automation.

---

## 🔹 Windows Fundamentals 3 — Processes, Task Manager & Security

This was the practical part that connected Windows to actual security workflows.  
I explored how Windows handles processes, services, updates, and security features.

### Key things I worked through:
- Understanding the **Task Manager** (processes, startup, details)
- Checking active services using `services.msc`
- Exploring Windows Defender’s security settings
- Basic system monitoring concepts

These areas form the base of how attackers and defenders interact with Windows systems.

---

## 🔸 Status Update (Before Active Directory)

I’m pausing here before starting **Active Directory Basics**.  
This topic is extremely important in cybersecurity — especially for penetration testing, privilege escalation, and corporate network understanding — so I want to learn it properly.

Next step:  
I’ll start the Active Directory module, take my time with it, and then post the next detailed update once I complete it.

---
