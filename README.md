### Before MeterPwrShell v2.0.1 released,pls dont use the AutoGetSYSTEM Feature yet,the AutoGetSYSTEM Feature is getting detected by WD,everything else is fine tho,im so sorry for your inconvenience.
```
   _____          __              __________                _________.__           .__  .__  ________  
  /     \   _____/  |_  __________\______   \_  _  ________/   _____/|  |__   ____ |  | |  | \_____  \ 
 /  \ /  \_/ __ \   __\/ __ \_  __ \     ___| \/ \/ |_  __ \_____  \ |  |  \_/ __ \|  | |  |  /  ____/ 
/    Y    \  ___/|  | \  ___/|  | \/    |    \     / |  | \/        \|   Y  \  ___/|  |_|  |_/       \ 
\____|__  /\___  >__|  \___  >__|  |____|     \/\_/  |__| /_______  /|___|  /\___  >____/____|_______ \
        \/     \/          \/                                     \/      \/     \/                  \/   
```
# MeterPwrShell2
Automated Tool That Generate A Powershell Oneliner That Can Create Meterpreter Shell On Metasploit,Bypass AMSI,Bypass Firewall,Bypass UAC,And Bypass Any AVs.

This tool is powered by [Metasploit-Framework](https://github.com/rapid7/metasploit-framework) and [amsi.fail](https://amsi.fail)
# Notes
- NEVER UPLOAD THE PAYLOAD THAT GENERATED BY THIS PROGRAM TO ANY ONLINE SCANNER
- NEVER USE THIS PROGRAM FOR MALICIOUS PURPOSE
- SPREADING THE PAYLOAD THAT GENERATED BY THIS PROGRAM IS NOT COOL
- ANY DAMAGE GENERATED BY THIS PROGRAM IS NOT MY (As the program maker) RESPONSIBILTY!!!
- If you have some feature recommendation,post that on Issue
- If you have some issue with the program,try redownloading it again (trust me),cause sometimes i edit the release and fix it without telling 😂
- If you want to know how tf my payload bypass any AVs,you can check on [this](https://gist.github.com/GetRektBoy724/9383c9580cb1c9935fc04cc7eb7ef004) and [this](https://blog.sevagas.com/Bypass-Antivirus-Dynamic-Analysis)
- Dont even try to fork this repository,you'll dont get the releases!
- For everyone who has issue or want to contact me,pls use Discord. My Discord ID is : DeadSec#4077
- This tool is not fully Open-Source (i guess),yes you can redistribute it as much as you want but you'll never get the source code of the tool (dont ask me why)
# Features (v2.0.0)
- Automatic Migrate (using PrependMigrate)
- AutoGetSYSTEM (Automaticly escalates privilege from normal user to SYSTEM)
- Disable All Firewall Profile (If you use AutoGetSYSTEM feature)
- Fully Bypass Windows Defender Real-time Protection
- Disable Windows Defender Security Features (If you use AutoGetSYSTEM feature)
- Fully unkillable payload (If you use Automatic Migrate feature)
- Bypasses AMSI Successfully 
- Short One-Liner 
- Bypass Firewall (If you pick an unstaged payload)
- Great CLI
- A Lot More (Try it by yourself)
--------------------------------------------------------------
### All payload features is tested on Windows 10 v20H2
--------------------------------------------------------------
## Advantages Of MeterPwrShell Compared To The web_delivery Module From Metasploit Framework
- Shorter stager (Or short one-liner in this case)
- Dont need to setup a server for the stager 
- Support Ngrok built-in (so the victim doesnt need to be on the same local network)
- Automatic Built-in Privesc
- Easily Bypass Windows Defender 
# Thanks to
- Every single of my Discord Friends
- Special Thx to theia#8536 on Discord
- @FuzzySec for that awesome Masquerade PEB script
- @decoder-it for that amazing PPID Spoofing script
- Me for not dying when creating this tool
- Ed Wilson AKA Microsoft Scripting Guy for the great Powershell scripting tutorials
- and the last one is Emeric Nasi for the [research on bypassing AV dynamics](https://blog.sevagas.com/IMG/pdf/BypassAVDynamics.pdf)
# Requirements
- Kali Linux,Ubuntu,Or Debian (If you dont use on of those,the tool will not work!!!)
- Metasploit Framework
- Internet Connection (Both On Victim And Attacker Computer)
# Installation
just fucking download your binary on Release page and please choose your binary according to your OS.
i386 and all arm architecture is not supported yet.
# Usage
```
# ./MeterPwrShell2Kalix64 -c help
 Available arguments : help, version, showbanner, showlastdebuglog                                
 help : Show this page                                                                                                                                                
 version : Show MeterPwrShell's version                                                                                                                               
 showbanner : Show MeterPwrShell's Banner                                                                                                                             
 showlastdebuglog : Well,Its kinda self-explanatory tho                                                                                                               
 ```
 You also can use MeterPwrShell Without Any Flags And Arguments
 # Attack Vectors
 - BadUSBs
 - Malicious Shortcuts ([lnk2pwn](https://github.com/it-gorillaz/lnk2pwn/))
 - Document Macro Payload
 - MS DDE Exploit
 - Extreme Way : Type it in by yourself
 - Any exploit/vulns that let you execute command to victim
 - Idk i have run out of idea lmao
 # To-do List
