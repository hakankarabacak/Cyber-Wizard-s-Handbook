<h1 align="center">THE CYBER-WIZARD'S HANDBOOK</h1>

#### This repository contains all of the resources, guidelines, tools that I use in my daily life and in my career. Sometimes, I like things and add them here. I believe that this repository reflects my learning path because it shows what I have learned and how I improved. Thus, it can be a good resource for newbies(like me) who want to improve in this field. Have fun.

---

### Table of contents:
- [Tools](#Tools)
    - [Recon](#Recon)
        - [Subdomain Enumeration](#Subdomain-Enumeration)
        - [Port Scanning](#Port-Scanning)
        - [Screenshots](#Screenshots)
        - [Technologies](#Technologies)
        - [Content Discovery](#Content-Discovery)
        - [Links](#Links)
        - [Parameters](#Parameters)
        - [Fuzzing](#Fuzzing)
    - [Authentication Bypass](#Authentication-Bypass)
    - [Phishing](#Phishing)
    - [XSS](#XSS)
    - [Twitter Tools](#Twitter-Tools)
    - [Generators](#Generators)
    - [Web-based](#Web-based)
    - [OSINT](#OSINT)

- [Tweets](#Tweets)
- [Courses and Guides](#Courses-and-Guides)
- [Polygon](#Polygon)
- [Reminder](#Reminder)

---

Tools
=====

### Recon
##### Subdomain Enumeration

- [Sublist3r](https://github.com/aboul3la/Sublist3r) - Fast subdomains enumeration tool for penetration testers
- [Amass](https://github.com/OWASP/Amass) - In-depth Attack Surface Mapping and Asset Discovery
- [massdns](https://github.com/blechschmidt/massdns) - A high-performance DNS stub resolver for bulk lookups and reconnaissance (subdomain enumeration)
- [Findomain](https://github.com/Findomain/Findomain) - The fastest and cross-platform subdomain enumerator, do not waste your time.
- [Sudomy](https://github.com/Screetsec/Sudomy) - Sudomy is a subdomain enumeration tool to collect subdomains and analyzing domains performing automated reconnaissance (recon) for bug hunting / pentesting
- [chaos-client](https://github.com/projectdiscovery/chaos-client) - Go client to communicate with Chaos DNS API.
- [domained](https://github.com/TypeError/domained) - Multi Tool Subdomain Enumeration
- [bugcrowd-levelup-subdomain-enumeration](https://github.com/appsecco/bugcrowd-levelup-subdomain-enumeration) - This repository contains all the material from the talk "Esoteric sub-domain enumeration techniques" given at Bugcrowd LevelUp 2017 virtual conference
- [shuffledns](https://github.com/projectdiscovery/shuffledns) - shuffleDNS is a wrapper around massdns written in go that allows you to enumerate valid subdomains using active bruteforce as well as resolve subdomains with wildcard handling and easy input-output…
- [censys-subdomain-finder](https://github.com/christophetd/censys-subdomain-finder) - Perform subdomain enumeration using the certificate transparency logs from Censys.
- [Turbolist3r](https://github.com/fleetcaptain/Turbolist3r) - Subdomain enumeration tool with analysis features for discovered domains
- [censys-enumeration](https://github.com/0xbharath/censys-enumeration) - A script to extract subdomains/emails for a given domain using SSL/TLS certificate dataset on Censys
- [tugarecon](https://github.com/LordNeoStark/tugarecon) - Fast subdomains enumeration tool for penetration testers.
- [as3nt](https://github.com/cinerieus/as3nt) - Another Subdomain ENumeration Tool
- [Subra](https://github.com/si9int/Subra) - A Web-UI for subdomain enumeration (subfinder)
- [Substr3am](https://github.com/nexxai/Substr3am) - Passive reconnaissance/enumeration of interesting targets by watching for SSL certificates being issued
- [domain](https://github.com/jhaddix/domain/) - enumall.py Setup script for Regon-ng
- [altdns](https://github.com/infosec-au/altdns) - Generates permutations, alterations and mutations of subdomains and then resolves them
- [brutesubs](https://github.com/anshumanbh/brutesubs) - An automation framework for running multiple open sourced subdomain bruteforcing tools (in parallel) using your own wordlists via Docker Compose
- [dns-parallel-prober](https://github.com/lorenzog/dns-parallel-prober) - his is a parallelised domain name prober to find as many subdomains of a given domain as fast as possible.
- [dnscan](https://github.com/rbsec/dnscan) - dnscan is a python wordlist-based DNS subdomain scanner.
- [knock](https://github.com/guelfoweb/knock) - Knockpy is a python tool designed to enumerate subdomains on a target domain through a wordlist.
- [hakrevdns](https://github.com/hakluke/hakrevdns) - Small, fast tool for performing reverse DNS lookups en masse.
- [dnsx](https://github.com/projectdiscovery/dnsx) - Dnsx is a fast and multi-purpose DNS toolkit allow to run multiple DNS queries of your choice with a list of user-supplied resolvers.
- [subfinder](https://github.com/projectdiscovery/subfinder) - Subfinder is a subdomain discovery tool that discovers valid subdomains for websites.
- [assetfinder](https://github.com/tomnomnom/assetfinder) - Find domains and subdomains related to a given domain
- [crtndstry](https://github.com/nahamsec/crtndstry) - Yet another subdomain finder
- [VHostScan](https://github.com/codingo/VHostScan) - A virtual host scanner that performs reverse lookups
- [scilla](https://github.com/edoardottt/scilla) - Information Gathering tool - DNS / Subdomains / Ports / Directories enumeration
- [sub3suite](https://github.com/3nock/sub3suite) - A research-grade suite of tools for subdomain enumeration, intelligence gathering and attack surface mapping.

##### Port Scanning

- [masscan](https://github.com/robertdavidgraham/masscan) - TCP port scanner, spews SYN packets asynchronously, scanning entire Internet in under 5 minutes.
- [RustScan](https://github.com/RustScan/RustScan) - The Modern Port Scanner
- [naabu](https://github.com/projectdiscovery/naabu) - A fast port scanner written in go with focus on reliability and simplicity.
- [nmap](https://github.com/nmap/nmap) - Nmap - the Network Mapper. Github mirror of official SVN repository.
- [sandmap](https://github.com/trimstray/sandmap) - Nmap on steroids. Simple CLI with the ability to run pure Nmap engine, 31 modules with 459 scan profiles.
- [ScanCannon](https://github.com/johnnyxmas/ScanCannon) - Combines the speed of masscan with the reliability and detailed enumeration of nmap

##### Screenshots

- [EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness) - EyeWitness is designed to take screenshots of websites, provide some server header info, and identify default credentials if possible.
- [aquatone](https://github.com/michenriksen/aquatone) - Aquatone is a tool for visual inspection of websites across a large amount of hosts and is convenient for quickly gaining an overview of HTTP-based attack surface.
- [screenshoteer](https://github.com/vladocar/screenshoteer) - Make website screenshots and mobile emulations from the command line.
- [gowitness](https://github.com/sensepost/gowitness) - gowitness - a golang, web screenshot utility using Chrome Headless
- [WitnessMe](https://github.com/byt3bl33d3r/WitnessMe) - Web Inventory tool, takes screenshots of webpages using Pyppeteer (headless Chrome/Chromium) and provides some extra bells & whistles to make life easier.
- [eyeballer](https://github.com/BishopFox/eyeballer) - Convolutional neural network for analyzing pentest screenshots
- [scrying](https://github.com/nccgroup/scrying) - A tool for collecting RDP, web and VNC screenshots all in one place
- [Depix](https://github.com/beurtschipper/Depix) - Recovers passwords from pixelized screenshots
- [httpscreenshot](https://github.com/breenmachine/httpscreenshot/) - HTTPScreenshot is a tool for grabbing screenshots and HTML of large numbers of websites.

##### Technologies

- [wappalyzer](https://github.com/AliasIO/wappalyzer) - Identify technology on websites.
- [webanalyze](https://github.com/rverton/webanalyze) - Port of Wappalyzer (uncovers technologies used on websites) to automate mass scanning.
- [python-builtwith](https://github.com/claymation/python-builtwith) - BuiltWith API client
- [whatweb](https://github.com/urbanadventurer/whatweb) - Next generation web scanner
- [retire.js](https://github.com/RetireJS/retire.js) - scanner detecting the use of JavaScript libraries with known vulnerabilities
- [httpx](https://github.com/projectdiscovery/httpx) - httpx is a fast and multi-purpose HTTP toolkit allows to run multiple probers using retryablehttp library, it is designed to maintain the result reliability with increased threads.
- [fingerprintx](https://github.com/praetorian-inc/fingerprintx) - fingerprintx is a standalone utility for service discovery on open ports that works well with other popular bug bounty command line tools.

##### Content Discovery

- [gobuster](https://github.com/OJ/gobuster) - Directory/File, DNS and VHost busting tool written in Go
- [recursebuster](https://github.com/C-Sto/recursebuster) - rapid content discovery tool for recursively querying webservers, handy in pentesting and web application assessments
- [feroxbuster](https://github.com/epi052/feroxbuster) - A fast, simple, recursive content discovery tool written in Rust.
- [dirsearch](https://github.com/maurosoria/dirsearch) - Web path scanner
- [dirsearch](https://github.com/evilsocket/dirsearch) - A Go implementation of dirsearch.
- [filebuster](https://github.com/henshin/filebuster) - An extremely fast and flexible web fuzzer
- [dirstalk](https://github.com/stefanoj3/dirstalk) - Modern alternative to dirbuster/dirb
- [dirbuster-ng](https://github.com/digination/dirbuster-ng) - dirbuster-ng is C CLI implementation of the Java dirbuster tool
- [gospider](https://github.com/jaeles-project/gospider) - Gospider - Fast web spider written in Go
- [hakrawler](https://github.com/hakluke/hakrawler) - Simple, fast web crawler designed for easy, quick discovery of endpoints and assets within a web application
- [crawley](https://github.com/s0rg/crawley) - fast, feature-rich unix-way web scraper/crawler written in Golang.

##### Links

- [LinkFinder](https://github.com/GerbenJavado/LinkFinder) - A python script that finds endpoints in JavaScript files
- [JS-Scan](https://github.com/zseano/JS-Scan) - a .js scanner, built in php. designed to scrape urls and other info
- [LinksDumper](https://github.com/arbazkiraak/LinksDumper) - Extract (links/possible endpoints) from responses & filter them via decoding/sorting
- [GoLinkFinder](https://github.com/0xsha/GoLinkFinder) - A fast and minimal JS endpoint extractor
- [BurpJSLinkFinder](https://github.com/InitRoot/BurpJSLinkFinder) - Burp Extension for a passive scanning JS files for endpoint links.
- [urlgrab](https://github.com/IAmStoxe/urlgrab) - A golang utility to spider through a website searching for additional links.
- [waybackurls](https://github.com/tomnomnom/waybackurls) - Fetch all the URLs that the Wayback Machine knows about for a domain
- [gau](https://github.com/lc/gau) - Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl.
- [getJS](https://github.com/003random/getJS) -  A tool to fastly get all javascript sources/files
- [linx](https://github.com/riza/linx) - Reveals invisible links within JavaScript files

##### Parameters

- [parameth](https://github.com/maK-/parameth) - This tool can be used to brute discover GET and POST parameters
- [param-miner](https://github.com/PortSwigger/param-miner) - This extension identifies hidden, unlinked parameters. It's particularly useful for finding web cache poisoning vulnerabilities.
- [ParamPamPam](https://github.com/Bo0oM/ParamPamPam) - This tool for brute discover GET and POST parameters.
- [Arjun](https://github.com/s0md3v/Arjun) - HTTP parameter discovery suite.
- [ParamSpider](https://github.com/devanshbatham/ParamSpider) - Mining parameters from dark corners of Web Archives.
- [x8](https://github.com/Sh1Yo/x8) - Hidden parameters discovery suite written in Rust.

##### Fuzzing

- [wfuzz](https://github.com/xmendez/wfuzz) - Web application fuzzer
- [ffuf](https://github.com/ffuf/ffuf) -  Fast web fuzzer written in Go
- [fuzzdb](https://github.com/fuzzdb-project/fuzzdb) - Dictionary of attack patterns and primitives for black-box application fault injection and resource discovery.
- [IntruderPayloads](https://github.com/1N3/IntruderPayloads) - A collection of Burpsuite Intruder payloads, BurpBounty payloads, fuzz lists, malicious file uploads and web pentesting methodologies and checklists.
- [fuzz.txt](https://github.com/Bo0oM/fuzz.txt) - Potentially dangerous files
- [fuzzilli](https://github.com/googleprojectzero/fuzzilli) - A JavaScript Engine Fuzzer
- [fuzzapi](https://github.com/Fuzzapi/fuzzapi) - Fuzzapi is a tool used for REST API pentesting and uses API_Fuzzer gem
- [qsfuzz](https://github.com/ameenmaali/qsfuzz) - qsfuzz (Query String Fuzz) allows you to build your own rules to fuzz query strings and easily identify vulnerabilities.
- [vaf](https://github.com/d4rckh/vaf) - very advanced (web) fuzzer written in Nim.

---

### Authentication Bypass
- [Evilginx2](https://m0chan.github.io/2019/07/26/Bypassing-2FA-For-Fun-With-Evilginx2.html) - MITM attack framework used for phishing login credentials along with session cookies, which in turn allows to bypass 2-factor authentication protection.

---

### Phishing
- [MaxPhisher](https://github.com/KasRoudra/MaxPhisher) - A python phishing script for login phishing, image phishing, video phishing and many more.

---

### XSS
- [XSStrike](https://github.com/s0md3v/XSStrike) - XSStrike is a Cross Site Scripting detection suite

---

### Twitter Tools
- [tinfoleak](https://tinfoleak.com/#page-top)
- [twdown](https://twdown.net/)
- [treeverse](https://treeverse.app/)
- [#onemilliontweetmap](https://onemilliontweetmap.com/?center=41.08530320586984,28.85044097900391&zoom=11&search=beykent&timeStep=0&timeSelector=0&hashtag1=&hashtag2=sad&sidebar=yes&hashtagBattle=0&timeRange=0&timeRange=25&heatmap=0&sun=0&cluster=1)

---

### Generators
- [passgen](https://github.com/hakankarabacak/passgen) - Simply password generator for social medias, written by me.
- [hashgen](https://github.com/hakankarabacak/hashgen) - Simply hash generator for encrypting data written by me.
- [QR Encoding/Decoding](https://github.com/hakankarabacak/QR)

---

### Web-based
- [IntelTechniques](https://inteltechniques.com/index.html)
- [Corrupt file](https://corrupt-a-file.net/)
- [ToS Didn't Read](https://tosdr.org/)
- [haveibeenpwned](https://haveibeenpwned.com/)
- [Simple Login](https://simplelogin.io/)
- [termbin](https://termbin.com/)
- [Undesign](https://undesign.learn.uno/remove-background/)
- [Watermark Remover](https://www.watermarkremover.io/)
- [GTFOBins](https://gtfobins.github.io/)

---

### OSINT
- [Shodan](https://www.shodan.io/) - Shodan is search engine for Internet-connected devices.
- [Maltego](https://www.maltego.com/) - Quickly pull data from profiles, posts, and comments into one graph, where we can conduct text searches and see connections.
- [Recon-ng](https://github.com/lanmaster53/recon-ng) - Recon-ng is a full-featured Web Reconnaissance framework written in Python.
- [Wayback Machine](https://archive.org/web) - The Internet Archive Wayback Machine is a service that allows people to visit archived versions of Web sites.

---

Tweets
------

- [VirusTotal virus flag bypass](https://twitter.com/Alh4zr3d/status/1610291517792321536)
- [Cyber Security Certifications](https://twitter.com/LetsDefendIO/status/1511728038865772544)
- [Easy way to get good vulns with shodan search](https://twitter.com/atomiczsec/status/1560104164641935360)
- [This OSINT page full of resources](https://twitter.com/startme/status/1563225274673942532)
- [hashquine!](https://twitter.com/David3141593/status/1573218394358386688)
- [temp VPS/SSH services](https://twitter.com/mertcangokgoz/status/1584450382612176896)
- [SpoolSploit - Auto Exploit Windows](https://twitter.com/0dayCTF/status/1610379627725262850)
- [Found PHPinfo page?](https://twitter.com/therceman/status/1611663113807355908)
- [xss using css](https://twitter.com/spyerror/status/1156698710128115713)
- [How to learn reverse engineering fast](https://twitter.com/CristiVlad25/status/1612467610003685377)
- [Having trouble finding new bugs for your program?](https://twitter.com/therceman/status/1612698610730438659)
- [How about some AI straight into your terminal?](https://twitter.com/CristiVlad25/status/1612430853962866688)
- [Jenkins](https://twitter.com/BhatAasim9/status/1614486810331328515)
- [Hacking admin panels](https://twitter.com/sachin_pandey98/status/1614915640799952898)
- [Easy information disclosure P4](https://twitter.com/ADITYASHENDE17/status/1616715101188558854)
- [Tips to stay safe while working with malware samples](https://twitter.com/struppigel/status/1617384467731185665)

---

Courses and Guides
------------------

- [Password Storage (OWASP)](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)
- [Red Team Guide](https://redteam.guide/)
- [OFFENSIVE SECURITY & REVERSE ENGINEERING & OFFENSIVE SOFTWARE EXPLOITATION](https://exploitation.ashemery.com/)
- [Bug Bounty cheatsheet](https://github.com/EdOverflow/bugbounty-cheatsheet)
- [XSS: Arithmetic Operators & Optional Chaining To Bypass Filters & Sanitization](https://www.secjuice.com/xss-arithmetic-operators-chaining-bypass-sanitization/)
- [[BOOK] Practical Cryptography for Developers](https://cryptobook.nakov.com/)
- [Publications of International Association for Cryptologic Research](https://iacr.org/publications/)
- [What is DNS the hard way (TR)](https://drive.google.com/file/d/1h1ae1zf2JSlSUoo76Rp1LPwygbodKObJ/view)
- [Hacksplaining](https://www.hacksplaining.com/lessons)
- [Here are 10 interesting ChatGPT use cases](https://www.linkedin.com/posts/generative-artificial-intelligence_innovation-technology-artificialintelligence-activity-7019606828040781824-nOcN?utm_source=share&utm_medium=member_desktop)
- [How to Bypass ChatGPT Sorry msg](https://www.linkedin.com/feed/update/urn:li:activity:7022583580237180928/)


###### Courses
- [[COURSE] University of Maryland Cryptography](https://www.coursera.org/learn/cryptography/home/week/1)
    - [CBC-MAC](https://en.wikipedia.org/wiki/CBC-MAC)
    - [HMAC](https://en.wikipedia.org/wiki/HMAC)
    - [Authenticated Encryption](https://en.wikipedia.org/wiki/Authenticated_encryption#:~:text=Authenticated%20Encryption%20(AE)%20are%20forms,confidentiality%20and%20authenticity%20of%20data.)
    - [Diffie-Hellman key exchange](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange)
    - [Discrete-Log-Based Public-Key Encryption](https://www.di-mgt.com.au/public-key-crypto-discrete-logs-0.html)
    - [RSA-Based Public-Key Encryption](https://en.wikipedia.org/wiki/RSA_(cryptosystem))
    - [Digital Signatures](https://www.docusign.com/how-it-works/electronic-signature/digital-signature/digital-signature-faq)
    - [RSA Signatures](https://cryptobook.nakov.com/digital-signatures/rsa-signatures)
    - [PKI](https://en.wikipedia.org/wiki/Public_key_infrastructure)

---

Polygon
-------

- [XSS Firing Range](https://public-firing-range.appspot.com/) - Firing Range is a test bed for automated web application security scanners.
- [PortSwigger Labs](https://portswigger.net/web-security/all-labs) - Featuring over 190 topics and interactive labs that cover even the latest vulnerabilities.
- [TryHackMe](https://tryhackme.com/) - TryHackMe is an online platform that teaches cyber security through short, gamified real-world labs.
- [Hack The Box](https://www.hackthebox.com/) - TryHackMe alternative.
- [alert(1) to win](https://alf.nu/alert1?world=alert&level=alert0)
- [Cryptohack](https://cryptohack.org/) - A fun, free platform for learning modern cryptography
- [Command Challenge](https://cmdchallenge.com/)
- [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/) - BlueTeam Challenges
- [Google CTF](https://capturetheflag.withgoogle.com/)
- [OverTheWire](https://overthewire.org/wargames/) - Learn and practice security concepts in the form of fun-filled games.

---

Reminder
--------
- [AutoRecon](https://github.com/Tib3rius/AutoRecon) - AutoRecon is a multi-threaded network reconnaissance tool which performs automated enumeration of services.
- [Burp Suite](https://portswigger.net/burp) - Burp Suite is an integrated platform and graphical tool for performing security testing of web applications.
- [Subfinder](https://github.com/projectdiscovery/subfinder) - subfinder is a subdomain discovery tool that returns valid subdomains for websites.

---
