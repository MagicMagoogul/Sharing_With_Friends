awesome-cyber

A curated list of awesome cybersecurity tools for both red, blue, and purple team operations.
Contributions?

Contributions are welcome! The goal of this repository is to be an up-to-date source of tools for all facets of cybersecurity. The landscape changes constantly and so do the tools. It's hard keeping track of everything! If you want to add (or remove outdated) tools, feel free to create an issue or a PR.
Quick links

    General
        Operating Systems
        Other awesome-Collections
    Red Team Tools
        Defense Evasion
        OSINT
        Reconaissance
        Social Engineering
        Leaked Credentials
        Web Exploitation
        Wireless
        Initial Access
        C2 Frameworks
        Post Exploitation
        Exfiltration
        Credential Dumping
    Blue Team Tools
        Forensics
        Deobfuscation
        Reverse Engineering
        Malware Analysis
        Hardening
    CTF stuff

General
Operating Systems
OS 	Description
FlareVM 	Windows distribution for malware analysis and incident response.
Kali 	Open-source, Debian-based Linux distribution geared towards various information security tasks, such as Penetration Testing.
Parrot 	Parrot Security (ParrotOS, Parrot) is a Free and Open source GNU/Linux distribution based on Debian Stable designed for security experts, developers and privacy aware people.
REMnux 	Linux toolkit for reverse engineering malware.
Other awesome-Collections

    This repository is just a brief (and generalized) list of resources and tools for both sides of cyber: blue and red team operations. As such, this is not meant to be in-depth resources. If you are looking for more specific information and/or tools, this contains a list of resource collections.

Repository 	Description
awesome-reversing 	A curated list of awesome reversing resources.
awesome-hacking 	A list of hacking resources and tools: RE, web, forensics, etc.
awesome-osint 	A curated list of amazingly awesome OSINT.
awesome-pentest 	A collection of awesome penetration testing resources, tools and other shiny things.
awesome-social-engineering 	A curated list of awesome social engineering resources.
awesome-asset-discovery 	List of Awesome Asset Discovery Resources.
awesome-incident-response 	A curated list of tools for incident response.
awesome-red-teaming 	List of Awesome Red Teaming Resources.
awesome-malware-analysis 	A curated list of awesome malware analysis tools and resources.
awesome-ida-x64-olly-plugin 	A list of plugins for IDA, Ghidra, GDB, OllyDBG, etc.
awesome-forensics 	A curated list of awesome forensic analysis tools and resources
awesome-pcaptools 	Tools for PCAP files
awesome-windows-post-exploitation 	Windows post-exploitation tools, resources, techniques and commands to use during post-exploitation phase of penetration test.
Red Team
Defense Evasion
Repository 	Description
Amsi-Bypass-PowerShell 	AMSI bypasses (most are patched, but can be obfuscated to bypass).
AMSITrigger 	Finds which string(s) trigger AMSI.
chameleon 	PowerShell script obfuscator.
Invisi-Shell 	Used to bypass PowerShell security (logging, AMSI, etc).
Invoke-Obfuscation 	PowerShell script obfuscator.
ISESteroids 	PowerShell script obfuscator.
Invoke-Stealth 	PowerShell script obfuscator.
UPX 	PE packer.
Unprotect 	Contains malware evasion techniques along with PoC.
OSINT
Repository 	Description
Cloudmare 	Cloudflare, Sucuri, Incapsula real IP tracker.
crt.sh 	Find certificates based on a domain name. Can be used to find subdomains.
DorkSearch 	Premade Google dork queries.
ExifTool 	Read (and modify) metadata of files.
FaceCheck.ID 	Reverse image lookup based on facial-recognition.
Hunter 	Find company email format and list of employee email addresses.
osintframework 	An online database of OSINT tools.
PimEyes 	Reverse image lookup based on facial-recognition.
Recon-NG 	Reconaissance and OSINT framework. Has many modules such as port scanning, subdomain finding, Shodan, etc.
ScrapeIn 	Scrapes LinkedIn to create a list of employee email addresses (for use in Initial Access).
SecurityTrails 	Extensive DNS information.
Shodan 	Scans for all digital assets.
SpiderFoot 	Automatic OSINT analysis.
TheHarvester 	Collects names, emails, IPs, and subdomains of a target.
Reconaissance
Repository 	Description
altdns 	Subdomain enumeration using mutated wordlists.
AWSBucketDump 	Enumerate AWS S3 buckets to find interesting files.
CameRadar 	Cameradar hacks its way into RTSP videosurveillance cameraa
CloudBrute 	Enumerates "the cloud" (Google, AWS, DigitalOcean, etc) to find infrastructure, files, and apps for a given target.
dirb 	Web application directory / file fuzzer to find other pages.
DNSDumpster 	Online tool for DNS information of a domain.
feroxbuster 	Web application directory / file fuzzer to find other pages.
gobuster 	Web application directory / file fuzzer to find other pages, and support for DNS and vhost fuzzing.
GoWitness 	Screenshots webpages. Supports multi-domain lists and Nmap output.
Masscan 	Like nmap, but faster (thus, not stealthy.)
Nikto 	Web server scanner to perform security checks on a web server.
Nmap 	Finds open ports on a network. Additionally can detect version, OS, and more.
Raccoon 	All-in-one reconaissance. port/service scans, dirbusting, and web application retrieval.
Recon-NG 	Reconaissance and OSINT framework. Has many modules such as port scanning, subdomain finding, Shodan, etc.
subfinder 	Passive subdomain discovery tool.
wappalyzer 	Identify what frameworks a website runs
wpscan 	Automatic WordPress scanner to identify information about a WordPress site and possible vulnerabilities.
Social Engineering
Repository 	Description
evilginx 	Standalone man-in-the-middle attack framework used for phishing login credentials along with session cookies, allowing for the bypass of 2-factor authentication
GoPhish 	Phishing campaign framework to compromise user credentials.
msfvenom 	Generate malicious payloads for social engineering (ie: VBA, .exe, etc)
Social Engineering Toolkit 	Social engineering framework.
SpoofCheck 	Checks if a domain can be spoofed.
zphisher 	Phishing campaign framework to compromise user credentials.
Leaked Credentials
Repository 	Description
Dehashed 	Leaked credential search engine.
LeakCheck 	Leaked credential search engine.
Snusbase 	Leaked credential search engine.
Web Exploitation
Repository 	Description
Arachni 	Web Application Security Scanner Framework
burpsuite 	Full web testing suite, including proxied requests.
Caido 	Full web testing suite, including proxied requests. (Like Burp but written in Rust)
dirb 	Web application directory/file fuzzer.
dotGit 	A Firefox and Chrome extension that shows you if there is an exposed .git directory
feroxbuster 	Web application directory/file fuzzer.
flask-unsign 	Decode, bruteforce, and craft Flask session tokens.
gobuster 	Web application directory/file/DNS/vhost fuzzing.
Nikto 	Web server scanner to perform security checks on a web server.
nosqlmap 	Performs automated NoSQL injection tests.
PayloadsAllTheThings 	Useful payloads for a variety of attacks such as SQLi, IDOR, XSS, etc.
sqlmap 	Performs automated SQL injection tests.
w3af 	Web application attack and audit framework.
wappalyzer 	Identify what frameworks a website runs.
wpscan 	Automatic WordPress scanner to identify information about a WordPress site and possible vulnerabilities.
Wireless
Repository 	Description
Aircrack-ng 	Aircrack-ng is a complete suite of tools to assess WiFi network security.
Kismet 	sniffer, WIDS, and wardriving tool for Wi-Fi, Bluetooth, Zigbee, RF, and more
Reaver 	Reaver implements a brute force attack against Wifi Protected Setup (WPS) registrar PINs in order to recover WPA/WPA2 passphrases
Wifite 	Python script to automate wireless auditing using aircrack-ng tools
WifiPhisher 	The Rogue Access Point Framework
Initial Access
Repository 	Description
Easysploit 	Automatic Metasploit payload generator and shell listener.
Impacket 	A tool to perform Kerberos pre-auth bruteforcing (ASREP roast) via GetNPUsers.py
Kerbrute 	A tool to perform Kerberos pre-auth bruteforcing (ASREP roast)
Medusa 	Bruteforcer with multiple protocol support.
Metasploit 	Exploit framework that can be used for intial access and/or post-exploitation.
NetExec 	Bruteforce common Windows protocols (WinRM, LDAP, RDP, SMB, WMI, etc.). Try username null or '' and password '' for unauthenticated access.
Searchsploit 	Search ExploitDB for exploits.
TeamFiltration 	Cross-platform framework for enumerating, spraying, exfiltrating, and backdooring O365 AAD accounts
THC-Hydra 	Bruteforcer with multiple protocol support.
TREVORspray 	Advanced password spraying tool for Active Directory environments.
C2 Frameworks

    C2 frameworks can be considered both initial access and post-exploitation, as they generate payloads to be used in phishing campaigns (initial access) and will provide access to the host machine when ran (post exploitation).

Repository 	Description
Cobalt Strike 	Most robust and advanced C2 framework (also paid).
Pupy 	Python and C C2 framework.
Sliver 	Go C2 framework.
Villain 	Python and Powershell C2 framework.
Post Exploitation

    Modules for lateral movement, exfiltration, system enumeration, and more.

Repository 	Description
BloodHound 	Active Directory visualizer, useful for finding misconfigurations and/or shortest path to Domain Admin.
BloodHound.py 	Remote Python data ingestor for BloodHound.
Impacket 	A collection of Python scripts useful for Windows targets: psexec, smbexec, kerberoasting, ticket attacks, etc.
Mimikatz 	Mimikatz is both an exploit on Microsoft Windows that extracts passwords stored in memory and software that performs that exploit.
nishang 	Offensive PowerShell for red team, penetration testing and offensive security.
PowerHub 	Post-exploitation module for bypassing endpoint protection and running arbitrary files.
PowerSploit 	A PowerShell post-exploitation framework with many modules: exfiltration, privelege escalation, etc.
SharpHound 	C# data ingestor for BloodHound. (Recommend SharpHound.ps1 for Bloodhound Kali version)
Privilege Escalation

    These tools automatically enumerate current user privileges and try to find misconfigurations that would allow escalation to root and/or NT AUTHORITY\SYSTEM.

Repository 	Description
BeRoot 	Automated Windows, Linux, and Mac privilege escalation path discovery tool.
GTFOBins 	Unix binaries that can be used to bypass local security restrictions in misconfigured systems.
Invoke-PrivescCheck 	Automated Windows privilege escalation path discovery tool.
PEASS-ng 	Automated Windows, Linux, and Mac privilege escalation path discovery tool.
PowerUp 	Automated Windows privilege escalation path discovery tool.
Exfiltration

    Data exfiltration

Repository 	Description
DNSExfiltrator 	Data exfiltration over DNS request covert channel
Credential Dumping

    These tools help dump cached credentials from a system.

Repository 	Description
certsync 	Dump NTDS with golden certificates and UnPAC the hash
Dumpert 	LSASS memory dumper using direct system calls and API unhooking.
Impacket 	Dump domain credentials via DCSync or from NTDS.DIT/SAM with secretsdump.py.
Mimikatz 	Dump local and domain credentials with sekurlsa, lsadump modules.
Password Cracking

    These tools assist in uncovering passwords, whether it be for a hash or for password spraying attempts.

Repository 	Description
CeWL 	Scrape websites to generate wordlists.
crunch 	Generate wordlists based on requirements such as minimum and maximum length, character sets, etc.
Cupp 	Utilize OSINT to create password candidates for a specific person.
hashcat 	Password cracking tool.
JohnTheRipper 	Password cracking tool.
Mentalist 	A GUI for wordlist generation based on rules such as appending, prepending, etc.
AI / LLM

    This section will probably be outdated quick.

Repository 	Description
HarmBench 	A standardized evaluation framework for automated red teaming and robust refusal.
Adversarial Suffix 	Jailbreak based on prepending a potentially malicious query.
AutoDAN-Turbo 	Black-box jailbreak method that can automatically discover as many jailbreak strategies as possible from scratch.
Best-of-N 	Black-box algorithm that jailbreaks frontier AI systems across modalities (text, image, vision) by mutating the original query.
Blue Team
Forensics
Repository 	Description
Angle-Grinder 	Parse, aggregate, sum, average, min/max, percentile, and sort log files.
Autopsy 	Investigate disk images.
Autoruns 	Show persistence on Windows
Chainsaw 	Parse and threat hunt Windows EVTX files.
FTK Imager 	Investigate disk images.
KnockKnock 	Show persistence on macOS
Magika 	Detect file content types with deep learning.
Velociraptor 	Velociraptor is a tool for collecting host based state information using The Velociraptor Query Language (VQL) queries.
Volatility 	Analyze memory dump files.
ZimmermanTools 	Eric Zimmerman's toolset for Windows forensics: EVTX, registry, ShellBags, ShimCache, and more.
Network Analysis
Repository 	Description
mitmproxy 	CLI-based HTTP(S) proxy to intercept and modify HTTP requests.
Wireshark 	GUI-based pcap, pcapng analyzer and network traffic sniffer.
Deobfuscation & Unpacking
Repository 	Description
cfxc-deobf 	ConfuserEx unpacker.
de4dot-cex 	ConfuserEx unpacker.
de4dot 	.NET deobfuscator and unpacker.
deobfuscate.io 	Javascript deobfuscator.
FLOSS 	Automatically extract obfuscated strings from malware.
NoFuserEx 	ConfuserEx unpacker.
Packer-specific Unpackers 	List of unpackers for specific packers.
PSDecode 	PowerShell deobfuscator.
relative.im 	Javascript deobfuscator.
UnconfuserExTools 	ConfuserEx deobfuscation toolkit (old).
Reverse Engineering
Repository 	Description
awesome-ida-x64-olly-plugin 	A list of plugins for IDA, Ghidra, GDB, OllyDBG, etc.
Binary Ninja 	Decompiler, disassembler, and debugger GUI.
Cerberus 	Unstrips Rust and Go binaries.
cutter 	Decompiler, disassembler, and debugger GUI based on Rizin.
dnSpy 	.NET debugger and editor.
dotPeak 	.NET Decompiler and assembly browser
GDB 	CLI debugger for Linux executables.
GEF 	GDB addon with advanced features.
ghidra 	Decompiler and disassembler GUI.
JADX 	JAR, APK, DEX, AAR, AAB, and ZIP decompiler.
IDA 	Decompiler and disassembler GUI.
OllyDbg 	GUI debugger for Windows executables.
pycdc 	Decompile .pyc files into Python source code.
pyinstxtractor 	Extract .pyc files from PyInstaller compiled executables.
redress 	Analyzes stripped Go binaries.
rizin 	Disassembler and debugger CLI.
x64dbg 	GUI debugger for Windows executables.
XPEViewer 	PE file viewer (headers, libraries, strings, etc).
Malware Analysis
Repository 	Description
any.run 	Cloud-based sandbox.
CAPA 	Identify capabilities in executable files.
CAPEv2 	Self-hosted sandbox.
Cuckoo 	Self-hosted sandbox.
Detect-It-Easy 	Detect file type and packer used for Windows executables.
DRAKVUF 	Self-hosted sandbox.
Joe's Sandbox 	Cloud-based sandbox.
mac-monitor 	Advanced process monitoring for macOS
oletools 	Toolkit for Microsoft Office documents (Word, Excel, etc.) to extract VBA, embedded objects, etc.
PEiD 	Detect packer, cryptor, and compiler used for Windows executables.
Process Explorer 	Shows parent-child relationships between processes and open DLL handles.
Process Hacker 	Process Explorer + more
Process Monitor 	Tracks registry, file system, network, and process activity.
Hardening
Repository 	Description
BLUESPAWN 	An Active Defense and EDR software to empower Blue Teams
CISBenchmarks 	Benchmark for security configuration best practices
HardeningKitty 	HardeningKitty and Windows Hardening settings and configurations
Linux Hardening 	Linux Hardening
SteamRoller 	Automating basic security configurations across an Active Directory environment
