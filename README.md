### Hi there 👋 here is a overview of my OSS.

<!--
**killswitch-GUI/killswitch-GUI** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=killswitch-gui&show_icons=true&&count_private=true&hide_border=true&theme=radical" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=killswitch-gui&hide_border=true&theme=radical" />
</p>

### ⚡ Offensive Security Research & Tools
Over the years I have worked on various projects ranging from small research projects to team based projects in support of OSS. The following work spans over 10 years of OSS development, training, and research. Most of the code is research for other operational projects for red teaming, pentesting and IR.

#### 💬 Confrence Talks & Research

* [RAT - Repurposing Adversarial Tradecraft](https://www.slideshare.net/AlexanderRymdekoHarv/rat-repurposing-adversarial-tradecraft) - [Video](https://www.youtube.com/watch?v=v2jU8EsJMVc)
* [Malvertizing Like a Pro](https://www.slideshare.net/AlexanderRymdekoHarv/malvertizing-like-a-pro-65910846) - [Video](https://www.youtube.com/watch?v=boDRePkLo2g)
* [THE {PHISHING} {PATH} TO {INFO} WE MISSED](https://www.slideshare.net/AlexanderRymdekoHarv/the-phishing-path-to-info-we-missed)
* [External to DA, the OS X Way](https://www.slideshare.net/StephanBorosh/hackmiamifinal)
* [Building an EmPyre with Python](https://www.youtube.com/watch?v=79qzgVTP3Yc) - [Video](http://www.securitytube.net/video/16668?utm_source=HT&utm_medium=gplus&utm_campaign=SM)

##### OSINT

* [SimplyEmail](https://github.com/SimplySecurity/SimplyEmail) - OSINT collection tool with various modules to extract emails for targeted phishing
* [SimplyTemplate](https://github.com/SimplySecurity/SimplyTemplate) - Phishing Template Generation for large scale phishing
* [simplydomain](https://github.com/SimplySecurity/simplydomain) - SimplyDomain uses a framework approach to build and deploy modules within. This allows for fast, easy and, concise output to feed into larger OSINT feeds of subdomain collection.

##### Agents

* [DeepFreeze-Agent](https://github.com/killswitch-GUI/DeepFreeze-Agent) - Custom C++ agent to learn various Windows C APIs and WMI process, service, driver monitoring supporting dynamic rule creation. See confrence talk https://www.slideshare.net/AlexanderRymdekoHarv/rat-repurposing-adversarial-tradecraft
* [EmPyre](https://github.com/EmpireProject/EmPyre) - Core contributor on a team to develop EmPyre, a pure Python post-exploitation agent for OSX that was used on various Red Team engagements as limited OSS agents existed.
* [Empire](https://github.com/EmpireProject/Empire) - Core contributor on a team to support and develop on Empire after the python agent was merged into the Empire branch for cross platform operations.


##### Infrastructure

* [Rapid Attack Infrastructure (RAI)](https://github.com/obscuritylabs/RAI) - Team project to automate C2 redirector setup for Red Team OP's
* [flask_heroku_redirector](https://github.com/killswitch-GUI/flask_heroku_redirector) - Python Flask example application that demonstrates using Heroku as a C2 redirector
* [flask_pythonanywhere_redirector](https://github.com/killswitch-GUI/flask_pythonanywhere_redirector) - Python Flask example application that demonstrates using python-anywhere as a C2 redirector
* [flask_appengine_redirector](https://github.com/killswitch-GUI/flask_appengine_redirector) - Python Flask example application that demonstrates using Google App engine as a C2 redirector
* [CobaltStrike-ToolKit](https://github.com/killswitch-GUI/CobaltStrike-ToolKit) - Various collection of tools and scripts built over the years for CS


##### Host Collection & Modules

* [SetWindowsHookEx-Keylogger](https://github.com/killswitch-GUI/SetWindowsHookEx-Keylogger) - Example implementation of a Windows C++ Native Keylogger using SetWindowsHookEx
* [HastySeries](https://github.com/obscuritylabs/HastySeries) - C# toolset for offensive operators to triage, asses and make intelligent able decisions. 
* [minidump-lib](https://github.com/killswitch-GUI/minidump-lib) - C++ MiniDumpWriteDump static lib example, with CLI
* [Invoke-EncryptedZip.ps1](https://github.com/killswitch-GUI/PenTesting-Scripts/blob/master/Invoke-EncryptedZip.ps1) - Utility to make a encrypted and compressed Zip file from a provided folder. This allows users to stage files in a designated folder for exfil, or protection from final storage location.
* [Invoke-RPCArchitectureCheck%20.ps1](https://github.com/killswitch-GUI/PenTesting-Scripts/blob/master/Invoke-RPCArchitectureCheck%20.ps1) - A simple utility to use a crafted RPC packet to check a remote host's arch. Returns x86 or x64. It is based off research into remote service kernel exploitation and loaders.


##### Sniffers

* [Winsock-PCAP](https://github.com/killswitch-GUI/Winsock-PCAP) - Demonstrates a POC of how an older, yet still safe, method of native PCAP can take place using the Winsock2 library on Windows. This uses a reflective DLL injection to deploy and name pipes using a PowerShell POC communicator.
* [NIX-Sniffer-Examples](https://github.com/killswitch-GUI/NIX-Sniffer-Examples) - Linux Python 2.7 Socket sniffer (Layer 3 and up), OSX Libpcap monitor mode test and sniffer research
* [osx-libpcap-fullcap.py](https://gist.github.com/killswitch-GUI/ce347f79f5cdb90bd8056100c90e9be2) - OSX PCAP using python 2.7, libpcap, libc, and ctypes implemented in pure Python

##### Payloads & Loaders 

* [InfoPhish](https://github.com/obscuritylabs/InfoPhish) - InfoPath C# embded .NET DLL with remote Process Hollowing 
* [HotLoad-Driver](https://github.com/killswitch-GUI/HotLoad-Driver) - Loading Windows Drivers using Service Control Manager (SC) & Native Windows API's while embedding WinPCAP into RDI with Windows Pipes for control
* [PeFixUp](https://github.com/obscuritylabs/PeFixup) - Windows PE Tainting pre-flight op checks for delivering PE's to disk. Provides operator ability to capture metadata, ensure opsec and taint/check key characteristics to prevent AV/Analysis.


##### Persistence 

* [Persistence-Survivability](https://github.com/killswitch-GUI/Persistence-Survivability) - Research based on Duqu style persistence as a TTP to locate high uptime hosts within a network and calculate a Persistence Survivability Rating (PSR).
* [Invoke-InstallPsGPOPersistence](https://gist.github.com/killswitch-GUI/28f7af7c29b4de3cc3456ad48a1cacbe) - Provides the install of PS or Scripts persistence using reg keys and the proper .ini file to insert into GPO startup


##### Fuzzing

* [Fuzz-FFmpeg](https://github.com/killswitch-GUI/Fuzz-FFmpeg) - Docker container to support AFL (afl-multicore) to Fuzz FFmpeg in a contained environment


##### 🔭 Research

* [IsDebuggerPresent](https://github.com/killswitch-GUI/IsDebuggerPresent) - Comparing three excellent debugger check TTPs for necessary sandbox and anti-reversing techniques and their detection ratios. With interest in the ability to alert on IR actions and potentially beacon out with maybe a magic packet or some other TTP to ID that we have been burnt.
* [C-OSX-Shellcode](https://github.com/killswitch-GUI/C-OSX-Shellcode) - Used to learn X86_x64 shellcode generation using ASM and compiled C code on OSX
* [Domain-WIFILocate](https://github.com/killswitch-GUI/Domain-WIFILocated)

