# MeterPwrShell
Generate A Powershell Oneliner That Can Create Meterpreter Shell On Metasploit And Bypass AMSI

This tool is powered by [Metasploit-Framework](https://github.com/rapid7/metasploit-framework),[Xencrypt](https://github.com/the-xentropy/xencrypt),and [amsi.fail](https://amsi.fail)
# Features (v1.1.0) (All features is tested on Windows 10 v20H2)
- Full undetectable payload.Even if the payload detected,the AV can't do anything cause the payload has been automaticly migrated to another process.
- Bypasses AMSI Successfully (if you choose amsibypasscode technique with shortened payload)
- Short One-Liner (if you choose amsibypasscode technique with shortened payload)
- Great CLI
- A Lot More (Try it by yourself)
# Requirements
- Kali Linux,Ubuntu,Or Debian (If you dont use on of those,the tool will not work!!!)
- Metasploit Framework
- Internet Connection
# Installation
```
apt update && apt install wget
mkdir MeterPwrShell
cd MeterPwrShell && wget https://github.com/GetRektBoy724/MeterPwrShell/releases/download/v1.1.0/meterpwrshellexec
chmod +x meterpwrshellexec
```
# Usage
```
# ./meterpwrshellexec -c help
 Available arguments : help, version, showbanner, showlastdebuglog, disablerootdetector, disableinternetdetector, disablealldetector                                  
 help : Show this page                                                                                                                                                
 version : Show MeterPwrShell's version                                                                                                                               
 showbanner : Show MeterPwrShell's Banner                                                                                                                             
 showlastdebuglog : Well,Its kinda self-explanatory tho                                                                                                               
 disablerootdetector : Well,Its kinda self-explanatory tho                                                                                                            
 disableinternetdetector : Well,Its kinda self-explanatory tho                                                                                                        
 disablealldetector : Disable all detector except Linux distribution detector
 ```
 You also can use MeterPwrShell Without Any Flags/Arguments
 # Attack Vectors
 - BadUSBs
 - Malicious Shortcuts ([lnk2pwn](https://github.com/it-gorillaz/lnk2pwn/))
 - Extreme Way : Type it in by yourself
 - Any exploit/vulns that let you execute command to victim
 - Idk i have run out of idea lmao
 # Demonstration
 Coming Soon :D
