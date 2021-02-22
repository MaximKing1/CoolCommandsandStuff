# Linux-Commands

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

## Proxychain (Proxy Server Chain):

* `proxychain (Command)` = Runs the command in the Proxychain<br>

## theHarvestor (Search For Emails On a Website)
* `theHarvestor -h` = Shows theHarvestor Help Menu
* `theHarvestor -d (DOMAIN)` = theHarvestor Domain Search
* `theHarvestor -b (SEARCH ENGINE)` = theHarvestor Search Engine
* `theHarvestor -l (PORT)` = theHarvestor With a Port

## Nmap
* `nmap [options] (IP Address)` = Scan IP Address With Options<br>
* All Options - https://www.stationx.net/nmap-cheat-sheet/
### Nmap Options Main
* `-sS` = Stealth Scan
* `-sA` = TCP ACK port scan
* `-sW` = TCP Window port scan
* `-Pn` = Disable host discovery. Port scan only
* `-A` = Enables OS detection, version detection, script scanning, and traceroute
* `-O` = Remote OS detection using TCP/IP stack fingerprinting
* `-T{NUMBER}` = Change the number for different speeds. `1, 2` =  Intrusion Detection System evasion, `3` = Slower Scan, `3` = Normal, `4, 5` = Insane
* `-D` = Send scans from spoofed IPs
* `-v` = Increase the verbosity level (use -vv or more for greater effect)

<hr>

## Whois
* `whois amazon.com` = Shows Whois Info About amazon.com

<hr>

# Windows Commands

## Networking:

* `ipconfig` = Shows Network and IP Info
