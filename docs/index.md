# Ethical Hacking Toolbelt

# Table Of Contents
- [General Commands](#general-commands)
- [Extensions](#extensions)
- [Metasploit](#metasploit)
- [Python Scripts](#python-scripts)

## Tools
> DNS Scanners = dnsenum, dig<br>
> Network and Port Scanners = nmap<br>

# General Commands

## File Commands:

* `locate (WORD)` = Find file with the WORD in it<br>
* `nano FILE` = Text editor for terminal<br>
* `cat FILE` = open a file<br>
* `cat word.txt | grep password` = This will search words.txt for the word password<br>
* `echo john > words.txt` = Replace the word.txt with john<br>
* `cp FILE DIR` =  Copy the FILE into DIR<br>
* `mv FILE DIR` =  Move the FILE into DIR<br>
* `cp FILE FILE2` =  Rename the FILE into FILE2<br>

## General Commands:

* `history` = Shows last ran commands<br>
* `man COMMAND` = Shows all options for the COMMAND - Like a help per command<br>

## Terminal Processes & Systems:

* `ps` = Show running processes<br>
* `top` = Shows all the processes running on the machine + Shows some system stats<br>
* `uname` = Print system name (man uname)<br>
* `uname -a` = Prints all the OS Info<br>

## System:

* `apt install (Program)` = Install a program<br>
* `apt update` = Update the OS<br>
* `apt upgrade` = Upgrade the system (MAIN UPDATE)<br>
* `shutdown` = Sets timer for system shutdown (1 Minute)<br>
* `reboot` = Reboot the system<br>
* `exit` = Close the terminal<br>

## Networking:

* `ifconfig` = Shows Network and IP Info<br>
* `netstat -nr` = Shows IP Gateway Info<br>
* `netstat -antp` = Shows Active Connections<br>
* `netstat -ntp` = Shows Active Connections<br>

# Extensions

## Commands:
* `nslookup (Domain / IP)` = Shows name of IP Address

## Proxychain (Proxy Server Chain):

* `proxychain (Command)` = Runs the command in the Proxychain<br>

## theHarvestor (Search For Email Addresses On a Website)
* `theHarvestor -h` = Shows theHarvestor Help Menu
* `theHarvestor -d (DOMAIN)` = theHarvestor Domain Search
* `theHarvestor -b (SEARCH ENGINE)` = theHarvestor Search Engine
* `theHarvestor -l (PORT)` = theHarvestor With a Port

## Nmap
* `nmap [options] (IP Address)` = Scan IP Address With Options<br>
* All Options - https://www.stationx.net/nmap-cheat-sheet/<br>

### Nmap Options Main
* `-sS` = Stealth Scan
* `-sA` = TCP ACK port scan
* `-sW` = TCP Window port scan
* `-sT` = TCP connect port scan
* `-sU` = UDP port scan
* `-Pn` = Disable host discovery. Port scan only
* `-A` = Enables OS detection, version detection, script scanning, and traceroute
* `-O` = Remote OS detection using TCP/IP stack fingerprinting
* `-T{NUMBER}` = Change the number for different speeds. `1, 2` =  Intrusion Detection System evasion, `3` = Slower Scan, `3` = Normal, `4, 5` = Insane
* `-D` = Send scans from spoofed IPs
* `-v` = Increase the verbosity level (use -vv or more for greater effect)
* `-F` = Makes the scan go faster

### Nmap Bypass Firewalls

**Security Rating:**<br>
⭐⭐⭐ = Very Secure<br>
⭐⭐ = Secure<br>
⭐ = Less Secure<br>

* `nmap -sA (TARGET)` = Uses ACK Port Scan (Tricks The Router) (⭐⭐⭐)
* `nmap --script firewall-bypass (TARGET)` = Uses a script to bypass firewall (⭐⭐) [Source Code (nmap site)](https://nmap.org/nsedoc/scripts/firewall-bypass.html)
* `nmap -S <IP_Address> (TARGET)` = Spoof Source Address (⭐⭐⭐)
* `namp --spoof-mac <MAC address> (TARGET)` = Spoof MAC Address (⭐⭐)
* `nmap --proxies <Comma-separated list of proxy URLs> (TARGET)` = Use Proxy (⭐⭐)

## Dig (DNS Scanner)
* `dig --help` = Shows help menu
* `dig google.com` = Shows the DNS for google.com or any other domain
* `dig axfr (DOMAIN) @{DNS}` = Would start a zone transfer

## DNSENUM (DNS Records Scanner)
* DNSEnum is a command-line tool that automatically identifies basic DNS records such as MX, mail exchange servers, NS, domain name servers, or A—the address record for a domain. It also attempts zone transfers on all identified servers, and it has the ability to attempt reverse resolution (that is, getting the hostname given an IP address) and brute forcing (querying for the existence of hostnames in order to get their IP address) of subdomains and hostnames.
* `dnsenum -h` = Shows Help Menu
* `dnsenum google.com` = Checks the DNS for google.com or any domain you choose there

## Whois
* `whois amazon.com` = Shows Whois Info About amazon.com

# Metasploit
Metasploit is one of the biggest penetration testing frameworks out there, that's why have a entire section dedicated for it! 
