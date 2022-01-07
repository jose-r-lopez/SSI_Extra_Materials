# Extra materiales of our Computer System Security Course 

I am the coordinator of an undergraduate security course in a small university in the North of Spain (University of Oviedo, Asturias). It is taught in the *School of Computer Engineering* (EII), *University of Oviedo*, Spain (https://ingenieriainformatica.uniovi.es/) . We intend to introduce our future software engineers in the world of cybersecurity covering the major topics of this discipline. Unfortunately, the time is very limited and being an undergraduate course makes it impossible to go deep into any of the topics. To counter that, and for those that want to specialize in this amazing discipline, we provide extra materials that complement or reinforce the course teachings. These are not evaluable, but allows our students to better understand the concepts and also helps them to pursue a cybersecurity careers. As all these materials are extracted from free and public sources, we thought that it will be useful for many people to compile them in an structured and classified way (following the course syllabus) so anybody, not only our students, may be able to access them and contribute to the hacking community the best we can. We also incorporate some extra materials developed by our team in the mix, such as the tool cheatsheets and the Secure Coding Checklist. This repo is exactly the same one we will refer to our actual students that want to know more about some of the topics.

Happy Hacking! :)

**NOTE**: Please be patient, this repo will be updated frequently over time as we process or discover new materials.

## Extra materials from the Theory classes ##

### Topic 1. Introduction

### Topic 2. Cryptography applications

- **Practical Cryptography for Developers** by Svetlin Nakov: (https://cryptobook.nakov.com/)
- **Introduction to Quantum Computing** by Thomas Wong: (http://www.thomaswong.net/introduction-to-classical-and-quantum-computing.pdf)

### Topic 3. OS Security

### Topic 4. Security policies

### Topic 5. Perimeter and Network security

### Topic 6. Application Security

### Topic 7. Introduction to Red Team Techniques. CTFs


## Extra materials from the Seminar classes ##

### Seminar 1. Tools for Investigating on Internet

### Seminar 2. Physical security

### Seminar 3. Automated vulnerability scanning tools

### Seminar 4. Introduction to reversing

- **Ataque ROP** by scanthenet.net: (https://scanthenet.es/ataque-rop/)
- **Reversing Demo Malware 32bits** by Abraham Pasamar (Video): (https://youtu.be/FsQlk-Ut9fY)

### Seminar 5. Input validation

### Seminar 6. HTTP headers and CSP

### Seminar 7. Write-up of a CTF machine

## Extra materials from the Laboratory classes ##

### Lab 00. Creating your Virtual Machine for the Course and Automated Infrastructures

### Lab 01. System setup

### Lab 02. Information Discovery and OSINT

- **OSINT Tips** by blaCCkHatHacEEkr: (https://github.com/blaCCkHatHacEEkr/OSINT_TIPS)

### Lab 03-04. Cryptography Applications 

### Lab 05. Operating System Security (non-automatable)

### Lab 06. Automatable Linux Operating System. Security policies

### Lab 07. Network Security

### Lab 08-09. Network Enumeration

### Lab 10. Defending a web application

### Lab 11. Exploiting

### Lab 12. Privilege Scalation

## Tools and other cheatsheets ##

### Third-party Cheatsheets

- **Cheatsheet collection (miscellaneous tools, commands, concepts)** from elhacker.net: (https://ns2.elhacker.net/cheat-sheet/)

### Our own Cheatsheets
In the course *Seguridad de Sistemas Informáticos* (SSI, Computer Systems Security) from the *Escuela de Ingeniería Informática* of the University of Oviedo (https://ingenieriainformatica.uniovi.es/) we make extensive usage of cheatsheets for various tools. I have decided to share them to enable others to take advantage of these materials if they want. Please, be sure to also check my related repo *SSI_Materials* (https://github.com/jose-r-lopez/SSI_Materials) that contains how to create training labs to test these tools.

Each tool cheatsheet is provided in its own PDF file. The initial set of 33 cheatsheets (course 2020-2021) have been uploaded. Next course I will plan to create some more if needed, so this repo may get updated over time.  

Currently I offer 33 cheatsheets for these tools:

* **cewl**: Custom wordlist generation tool from a web page
* **crunch**: Tool that generates wordlists from a character set, to create custom password dictionaries
* **dirb**: HTTP directory and content discovery tool
* **dnsenum**: Multithreaded perl script to enumerate DNS information of a domain
* **dotdotpwn**: Automated scanning tool for File Inclusion vulnerabilities in URL paths
* **eyewitness**: Tool used to capture screenshots from a list of URLs
* **gpg**: Multipurpose GPL cipher/hash/pubkey software
* **gtfobins1**: Executables to enable privilege scalation in Linux systems (Part 1). GTFOBins is a collaborative project created by Emilio Pinna and Andrea Cardaci (https://gtfobins.github.io/). You should check the project site to know the specifics of each executable. The entries in the cheatsheet point to them.
* **gtfobins2**: Executables to enable privilege scalation in Linux systems (Part 2). GTFOBins is a collaborative project created by Emilio Pinna and Andrea Cardaci (https://gtfobins.github.io/). You should check the project site to know the specifics of each executable. The entries in the cheatsheet point to them.
* **hydra**: Offline password cracking tool
* **john**: Offline password cracking tool
* **knockpy**: Enumerates subdomains on a target domain through a wordlist
* **lolbas**: Executables to enable privilege scalation on Windows system. Please check the original project and the specifics of each executable in https://lolbas-project.github.io/. The entries in the cheatsheet point to them.
* **msfvenom**: A Metasploit standalone payload generator. 
* **netcat**: Multipurpose ("Swiss army knife") TCP/IP tool 
* **netdiscover**: An active / passive network scanner
* **nikto**: Lightweight web server vulnerability scanner
* **Nmap**: The reference swiss army knife in security. Cheatsheet are divided in 5 parts:
  * **nmap - recon**: Nmap part 1A: Basic recon
  * **nmap - advanced recon**: Nmap part 1B: Advanced recon
  * **nmap - enumeration**: Nmap part 2: Target Enumeration
  * **nmap - exploiting**: Nmap part 3: Target exploiting
  * **nmap - other options**: Nmap part 4: Other Nmap options
* **searchploit**: Public exploit offline browsing tool
* **snmpwalk**: Tool to discover flaws when using the SNMP protocol
* **steghide**: Classic steganography tool
* **sublist3r**: Python tool to enumerate subdomains of websites using OSINT
* **theHarvester**: OSINT tool for websites
* **tmux**: Console enhancer and multi-pane support tool
* **twint**: An Advanced Twitter Scraping Tool
* **ufw**: Tool to ease Ubuntu firewall management
* **wapiti**: Website vulnerability scanner
* **wpscan**: A vulnerability scanner for WordPress websites
* **zmap**: Fast internet-wide scanner

## Secure coding checklist ##

I have also added the "Secure Coding Checklist Template" that was aimed to enable my students to have a quick reference of common security checks that should be done to their code, enabling automatic calculation of implemented security controls similar to those that can be done with the *CIS Controls*. **This is by no means a methodology** (it was adapted from a rather old document from OWASP, the *OWASP Secure Coding Practices Quick Reference Guide v2.0*, https://owasp.org/www-pdf-archive/OWASP_SCP_Quick_Reference_Guide_v2.pdf), but enables the students to perform an adequate code review in a short time, turning those applications that use this checklist substantially more secure just by making sure several of these controls are correctly implemented in their code. Just remember that my students are beginning to learn security practices, so I thought it will be nice for them to have a centralized checklist of things to check that also enable some metrics so they can easily show their work. 

 
 Happy security training! :D
 
 
