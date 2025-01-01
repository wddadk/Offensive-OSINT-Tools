# Offensive-OSINT-Tools

This repository contains tools and links that can be used during OSINT in Pentest or Red Team. Currently, there are numerous awesome lists with tons of tools, but Offensive Security specialists often don't need such an extensive selection. This motivated the creation of this list. These tools cover almost all the needs of Offensive Security specialists and will help you get the job done efficiently.


If the tool performs multiple functions, for example collecting subdomains **and** URLs, it will be listed in two places.

## 📖 Table of Contents

- [Search Engines](#-search-engines)
- [Email addresses](#-email-addresses)
- [Source code](#-source-code)
- [SubDomain's](#-subdomains)
- [URLs](#-urls)
- [Dark Web](#-dark-web)
- [Intelligence](#-intelligence)
- [Network Info](#-network-info)
- [DnsHistory](#-dnshistory)
- [Certifications](#-certifications)
- [FTP servers](#-ftp-servers)
- [Passive Infrastructure scanner](#-passive-infrastructure-scanner)
- [Microsoft Exchange](#-microsoft-exchange)
- [Telegram](#-telegram)
- [Google Dorks](#-google-dorks)
- [Nickname search](#-nickname-search)
- [Phone number](#-phone-number)
- [Wifi](#-wifi)
- [Cloud](#-cloud)
- [Information gathering tools](#-information-gathering-tools)
- [Usefull links](#-usefull-links)


## [↑](#-table-of-contents) Contributing 

**Welcome!** If you find that any of your favourite offensive tools is not on the list, you can suggest adding it. 

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## [↑](#-table-of-contents) Search Engines

Search Engines for Investigation Domains/IP Addresses.

* [Censys](https://censys.io/)
* [Shodan](https://www.shodan.io/)
* [Greynoise.io](https://viz.greynoise.io/)
* [ZoomEye](https://www.zoomeye.org/)
* [Onyphe](https://www.onyphe.io/)
* [Fofa](https://fofa.info/)
* [Binaryedge](https://app.binaryedge.io/)
* [FullHunt](https://fullhunt.io/)
* [Netlas](https://app.netlas.io/)
* [Quake360](https://quake.360.net/quake/#/index)
* [Criminalip](https://www.criminalip.io/)
* [Synapsint](https://synapsint.com/)
* [Natlas](https://natlas.io/)
* [Leakix](https://leakix.net/)
* [Dorki.io](https://dorki.io/)


## [↑](#-table-of-contents) Email addresses

Tools that help you collect email addresses. Usually the search requires the domain of the company.

* [Prospeo.io](https://app.prospeo.io/domain-search)
* [Hunter.io](https://hunter.io/)
* [Snov.io](https://snov.io/)
* [Phonebook](https://phonebook.cz/)
* [findemail.io](https://findemail.io/)
* [Omail](https://omail.io/leads/download.html)
* [Skymem](https://www.skymem.info/)
* [Signalhire](https://www.signalhire.com/)
* [Rocketreach](https://rocketreach.co/)
* [Eyes](https://github.com/N0rz3/Eyes) - Email osint tool
* [Infoga](https://github.com/m4ll0k/Infoga)
* [Poastal](https://github.com/jakecreps/poastal) - Tool that provides valuable information on any email address
* [Email-format](https://www.email-format.com/) - Analyses the company's mail format.
* [h8mail](https://github.com/khast3x/h8mail) - Email OSINT & Password breach hunting tool
* [EmailFinder](https://github.com/Josue87/EmailFinder) - Search emails from a domain through search engines
* [theHarvester](https://github.com/laramies/theHarvester)
* [Anymailfinder](https://anymailfinder.com/) - Find Verified Emails
* [Rextracter.streamlit](https://rextracter.streamlit.app/) - Gathers links and analyses content
* [ronin-recon](https://github.com/ronin-rb/ronin-recon#readme) - Recursive recon engine and framework that can enumerate subdomains, DNS records, port scan, grab TLS certs, spider websites, and collect email addresses.
* [Osintly](https://osint.ly/) - An all-in-one OSINT platform.

## [↑](#-table-of-contents) Source code

Tools for finding mentions in code. Useful to search for company/company mentions to find passwords/secrets/confidential information.

* [Publicwww](https://publicwww.com/)
* [Nerdydata](https://www.nerdydata.com/)
* [Searchcode](https://searchcode.com/)
* [Grep.app](https://grep.app/)

## [↑](#-table-of-contents) SubDomain's

Tools for automatic search of subdomains. Most of them require API keys to work correctly.

### Tools
* [Bbot](https://github.com/blacklanternsecurity/bbot)
* [Subdominator](https://github.com/RevoltSecurities/Subdominator)
* [sub.Monitor](https://github.com/e1abrador/sub.Monitor) - Passive subdomain continous monitoring tool
* [Sudomy](https://github.com/screetsec/Sudomy)
* [Amass](https://github.com/OWASP/Amass)
* [theHarvester](https://github.com/laramies/theHarvester)
* [Spiderfoot](https://github.com/smicallef/spiderfoot)
* [subchase](https://github.com/tokiakasu/subchase) - Chase subdomains by parsing the results of Google and Yandex search results
* [GooFuzz](https://github.com/m3n0sd0n4ld/GooFuzz) - Enumerate directories, files, subdomains or parameters without leaving evidence on the target's serve
* [SubGPT](https://github.com/s0md3v/SubGPT) - SubGPT looks at subdomains you have already discovered for a domain and uses BingGPT to find more.
* [alterx](https://github.com/projectdiscovery/alterx) - Fast and customizable subdomain wordlist generator using DSL.
* [Photon](https://github.com/s0md3v/Photon) - Incredibly fast crawler designed for OSINT.
* [ronin-recon](https://github.com/ronin-rb/ronin-recon#readme) - Recursive recon engine and framework that can enumerate subdomains, DNS records, port scan, grab TLS certs, spider websites, and collect email addresses.
* [subdomain-enum](https://github.com/chaitanyakrishna/subdomain-enum) - securitytrails api

*Only sites/tools whose search is not automated by the tools above are listed here.*
* [TI.defender.microsoft](https://ti.defender.microsoft.com/)
* [Securitytrails](https://securitytrails.com/)
* [Shrewdeye](https://shrewdeye.app/)
* [Phonebook](https://phonebook.cz/)
* [Nmmapper](https://nmmapper.com/)
* [subdomainfinder.c99.](https://subdomainfinder.c99.nl/) - A subdomain finder is a tool used to find the subdomains of a given domain.
* [SubDomainRadar.io](https://subdomainradar.io) - Discover hidden subdomains with unparalleled accuracy and speed

## [↑](#-table-of-contents) URLs

Tools for passive collection and analysis URLs

* [Gau](https://github.com/lc/gau)
* [Xurlfind3r](https://github.com/hueristiq/xurlfind3r)
* [Unja](https://github.com/ninjhacks/unja)
* [Urlfinder](https://github.com/projectdiscovery/urlfinder)
* [urlhunter](https://github.com/utkusen/urlhunter) - a recon tool that allows searching on URLs that are exposed via shortener services
* [Waymore](https://github.com/xnl-h4ck3r/waymore)
* [Spiderfoot](https://github.com/smicallef/spiderfoot)
* [theHarvester](https://github.com/laramies/theHarvester)
* [GooFuzz](https://github.com/m3n0sd0n4ld/GooFuzz) - Enumerate directories, files, subdomains or parameters without leaving evidence on the target's serve
* [Rextracter.streamlit](https://rextracter.streamlit.app/) - Gathers links and analyses content
* [Uscrapper](https://github.com/z0m31en7/Uscrapper) - Tool that allows users to extract various personal information from a website.
* [ronin-recon](https://github.com/ronin-rb/ronin-recon#readme) - Recursive recon engine and framework that can enumerate subdomains, DNS records, port scan, grab TLS certs, spider websites, and collect email addresses.
* [Ominis-Osint](https://github.com/AnonCatalyst/Ominis-Osint) - The tool extracts relevant information such as titles, URLs, and potential mentions of the query in the results.

## [↑](#-table-of-contents) Dark web

An undiscovered area, the author is too dumb for that. Will gradually expand.

* [Ahmia](https://ahmia.fi/)

## [↑](#-table-of-contents) Intelligence

Threat Intelligence tools containing extensive company information, subdomains, DNS information, URLs and much more.  

* [TI.defender.microsoft](https://ti.defender.microsoft.com/)
* [Securitytrails](https://securitytrails.com/)
* [Pulsedive](https://pulsedive.com/)
* [ThreatBook](https://threatbook.io/)
* [Alienvault](https://otx.alienvault.com/)
* [Hudson Rock - Cybercrime Intelligence Tools](https://www.hudsonrock.com/threat-intelligence-cybercrime-tools)


## [↑](#-table-of-contents) Network Info

IP/Domain network analysis tools.

* [Bgp.he](https://bgp.he.net/)
* [whoistory](http://whoistory.com/)
* [Asnlookup](https://asnlookup.com/)
* [centralops](http://centralops.net/)
* [Bgp.tools](https://bgp.tools/)
* [Myip](https://myip.ms/)
* [IpInfo](https://ipinfo.io/) | [Cmd version](https://github.com/ipinfo/cli)
* [Whoisxmlapi](https://main.whoisxmlapi.com/)

## [↑](#-table-of-contents) DnsHistory

Tools for viewing the DNS history of a domain.

* [Bigdomaindata](https://bigdomaindata.com)
* [Dnshistory](https://dnshistory.org/)
* [Viewdns](https://viewdns.info/)
* [TI.defender.microsoft](https://ti.defender.microsoft.com/)
* [Securitytrails](https://securitytrails.com/)
## [](#-table-of-contents) Certifications

* [Crt.sh](https://crt.sh/)
* [Web-check](https://github.com/Lissy93/web-check) + [Web version](https://web-check.as93.net/)

## [↑](#-table-of-contents) FTP servers

Tools allowing you to search for and download files located on public FTP servers. 

* [Searchftps](https://www.searchftps.net/)

## [↑](#-table-of-contents) Passive Infrastructure scanner

Tools for automated passive IP address/subnet scanning.

* [Smap](https://github.com/s0md3v/Smap)
* [Nmap-censys](https://github.com/censys/nmap-censys)


## [↑](#-table-of-contents) Microsoft Exchange 

Tools that help in passive/semi-passive analysis of Microsoft Exchange.

* [ExchangeFinder](https://github.com/mhaskar/ExchangeFinder) | #SemiOSINT

## [↑](#-table-of-contents) Telegram

Tools for investigating Telegram chats.

* [Telepathy](https://github.com/jordanwildon/Telepathy)

## [↑](#-table-of-contents) Google Dorks

Tools for Google Dorks.

* [Pagodo](https://github.com/opsdisk/pagodo)
* [Google hacking database](https://www.exploit-db.com/google-hacking-database)
* [Recruitin](https://recruitin.net/) - Compiles Google dorks to search on LinkedIn, Dribbble, GitHub, Xing, StackOverflow, Twitter
* [Search](https://github.com/pbkompasz/search) - Custom queries in Google

## [↑](#-table-of-contents) Nickname search

Nickname search tools.

* [maigret](https://github.com/soxoj/maigret)
* [Sherlock](https://github.com/sherlock-project/sherlock)
* [Social analyzer](https://github.com/qeeqbox/social-analyzer)
* [nexfil](https://github.com/thewhiteh4t/nexfil)
* [whatsmyname](https://github.com/webbreacher/whatsmyname)
* [snoop](https://github.com/snooppr/snoop)
* [userrecon](https://github.com/wishihab/userrecon)
* [NicknameFinder](https://github.com/restanse/NicknameFinder)
* [gideon](https://github.com/YouVBeenHacked/gideon)
* [Arina-OSINT](https://github.com/AlexC-ux/Arina-OSINT)
* [netizenship](https://github.com/rahulrajpl/netizenship)
* [Search4](https://github.com/0xknown/Search4)
* [socialscan](https://github.com/iojw/socialscan)
* [Sherlock](https://github.com/mesuutt/sherlock)
* [recon-ng](https://github.com/lanmaster53/recon-ng/)
* [SocialPath](https://github.com/woj-ciech/SocialPath)
* [Castrick](https://castrickclues.com/)
* [Osintly](https://osint.ly/) - All-in-one OSINT platform, specializing in username searches across a wide range of websites and social media platforms.

## [↑](#-table-of-contents) Phone number

Sometimes situations happen that require analysing an employee's phone number to get more information.

* [PhoneInfoga](https://github.com/sundowndev/PhoneInfoga) + [Web Demo](https://demo.phoneinfoga.crvx.fr/)
* [GhostTrack](https://github.com/HunxByts/GhostTrack)
* [Osint.industries](https://osint.industries/)
* [Emobiletracker](https://www.emobiletracker.com/)
* [Castrick](https://castrickclues.com/)
* [Predicta Search](https://www.predictasearch.com/)

## [↑](#-table-of-contents) Wifi

* [3Wifi](https://3wifi.stascorp.com/) - free base of access points

## [↑](#-table-of-contents) Cloud

Tools for searching, gathering information from cloud.

* [Cloud_sherlock](https://github.com/Group-IB/cloud_sherlock)

## [↑](#-table-of-contents) Information gathering tools

* [Gasmask](https://github.com/twelvesec/gasmask)
* [Th3inspector](https://github.com/Moham3dRiahi/Th3inspector)
* [Cylect.io](https://cylect.io/)

## [↑](-table-of-contents) Usefull links

Links to guide, methodologies and any information that would be useful.

* [WhereToGo](https://github.com/valeriyshevchenko90/WhereToGo) - list of popular services that might be used in organizations. By having an account of the user - you can try to find entry points to the organization data. #semiosint
* [Cloud OSINT](https://github.com/7WaySecurity/cloud_osint) - Repository with information related to Cloud Osint
* [Information Disclosure Write-Ups And PoCs](https://github.com/soxoj/information-disclosure-writeups-and-pocs)

## Todo

* Add mobile number analysis tools (put into a category)
* Make a mindmap

## Warning

Some of the sites included might require registration or offer more data for $$$, but you should be able to get at least a portion of the available information for no cost.

----------------------------------------------------------
*Inspired by https://github.com/jivoi/awesome-osint*
