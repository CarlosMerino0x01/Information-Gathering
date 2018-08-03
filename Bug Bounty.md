https://medium.com/bugbountywriteup/whats-tools-i-use-for-my-recon-during-bugbounty-ec25f7f12e6d ----- POC of tools and recon

https://github.com/aboul3la/Sublist3r ----- Sublist3r is a python tool designed to enumerate subdomains of websites using OSINT. It helps penetration testers and bug hunters collect and gather subdomains for the domain they are targeting. Sublist3r enumerates subdomains using many search engines such as Google, Yahoo, Bing, Baidu, and Ask. Sublist3r also enumerates subdomains using Netcraft, Virustotal, ThreatCrowd, DNSdumpster, and ReverseDNS.

https://github.com/michenriksen/aquatone ----- AQUATONE is a set of tools for performing reconnaissance on domain names. It can discover subdomains on a given domain by using open sources as well as the more common subdomain dictionary brute force approach. After subdomain discovery, AQUATONE can then scan the hosts for common web ports and HTTP headers, HTML bodies and screenshots can be gathered and consolidated into a report for easy analysis of the attack surface.

https://github.com/EdOverflow/can-i-take-over-xyz ----- 
What is a sub-domain takeover?Subdomain takeover vulnerabilities occur when a subdomain (subdomain.example.com) is pointing to a service (e.g. GitHub pages, Heroku, etc.) that has been removed or deleted. This allows an attacker to set up a page on the service that was being used and point their page to that subdomain. For example, if subdomain.example.com was pointing to a GitHub page and the user decided to delete their GitHub page, an attacker can now create a GitHub page, add a CNAME file containing subdomain.example.com, and claim subdomain.example.com.

http://www.visualsitemapper.com/ ----- Create visualization of site

https://www.wappalyzer.com/download ----- Identify technology on websites
Wappalyzer is a cross-platform utility that uncovers the technologies used on websites. It detects content management systems, ecommerce platforms, web frameworks, server software, analytics tools and many more.

https://apollonsky.me/growth-hacking-google-dork/ ----- Article/POC of use of google dorks

https://www.shodan.io/ ----- Search of internet connected devices

https://censys.io/ ----- 
Find and analyze every reachable server and device on the Internet.

https://github.com/danielmiessler/SecLists ----- SecLists is the security tester's companion. It is a collection of multiple types of lists used during security assessments. List types include usernames, passwords, URLs, sensitive data grep strings, fuzzing payloads, and many more.

https://github.com/maurosoria/dirsearch ----- dirsearch is a simple command line tool designed to brute force directories and files in websites.

https://github.com/UltimateHackers/Arjun ----- Arjun is a python script for finding hidden GET & POST parameters using regex and bruteforce.

https://github.com/jobertabma/relative-url-extractor ----- A small tool that extracts relative URLs from a file.

https://github.com/jobertabma/virtual-host-discovery ----- This is a basic HTTP scanner that'll enumerate virtual hosts on a given IP address. During recon, this might help expand the target by detecting old or deprecated code. It may also reveal hidden hosts that are statically mapped in the developer's /etc/hosts file.

https://buckets.grayhatwarfare.com/ ----- Find open S3 buckets

https://takeover.cyberint.com/ ----- Discover if vulnerable to subdomain takeover
