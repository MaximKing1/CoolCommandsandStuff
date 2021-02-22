# Extensions

## Commands:
* `nslookup (Domain / IP)` = Shows name of IP Address

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
