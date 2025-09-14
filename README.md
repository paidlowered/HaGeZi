![GitHub last commit](https://img.shields.io/github/last-commit/hagezi/dns-blocklists)![GitHub issues](https://img.shields.io/github/issues/hagezi/dns-blocklists)![GitHub closed issues](https://img.shields.io/github/issues-closed/hagezi/dns-blocklists)![GitHub repo size](https://img.shields.io/github/repo-size/hagezi/dns-blocklists)[![shields.io Stars](https://img.shields.io/github/stars/hagezi/dns-blocklists)](https://github.com/hagezi/dns-blocklists/stargazers)

## :zap: DNS Blocklists - For a better internet!

<p align="left"><img width="25%" alt="HaGeZi DNS Blocklists" src="images/HaGeZi.svg" /></p>

### Made with :heartbeat: for a safer and cleaner internet! It always seems impossible until it’s done.

Privacy is not a crime, protect yourself. Privacy matters. Privacy is what allows us to determine who we are and who we want to be :bangbang:

If you like the project and you can benefit from it, leave a :star: (top right) and become a [stargazer](https://github.com/hagezi/dns-blocklists/stargazers)! Thanks for your support!

---

### :bookmark_tabs: Table of Contents

1. [Overview](#overview)
2. [Multi light](#light) - Hand brush: Light protection
3. [Multi normal](#normal) - Broom: All-round protection
4. [Multi pro](#pro) - Big broom: Extended protection (Recommended) : [Full](#pro) - [Mini](#promini)
5. [Multi pro++](#proplus) - Sweeper: Maximum protection (more aggressive) : [Full](#proplus) - [Mini](#proplusmini)
6. [Multi ultimate](#ultimate) - Ultimate Sweeper: Aggressive protection : [Full](#ultimate) - [Mini](#ultimatemini)
7. [Fake](#fake) - Protects against internet scams, traps & fakes!
8. [Pop-Up Ads](#popupads) - Protects against annoying and malicious pop-up ads!
9. [Threat Intelligence Feeds](#tif) - Increases security significantly! (Recommended) : [Full](#tif) - [Medium](#tifmedium) - [Mini](#tifmini) - [IPs](#tifips)
10. [Newly Registered Domains - NRD](#nrd) - Favoured by threat actors to launch malicious campaigns!
11. [DoH/VPN/TOR/Proxy Bypass](#bypass) - Prevent methods to bypass your DNS! : [Full](#bypass_all) - [DoH only](#bypass_dns) - [DoH IPs](#bypass_ips)
12. [Safesearch not supported](#safesearch) - Prevent the use of search engines that do not support Safesearch!
13. [Dynamic DNS](#dyndns) - Protects against the malicious use of dynamic DNS services!
14. [Badware Hoster](#hoster) - Protects against the malicious use of host services!
15. [URL Shortener](#urlshortener) - Blocks link/URL shortener!
16. [Most Abused TLDs](#tlds) - Protects against known malicious Top Level Domains!
17. [Anti Piracy](#piracy) - Protects against piracy!
18. [Gambling](#gambling) - Protects against gambling content! : [Full](#gambling) - [Medium](#gamblingmedium) - [Mini](#gamblingmini)
19. [NSFW](#nsfw) - Protects against adult content!
20. [Native Tracker](#native) - Broadband tracker of devices, services and operating systems
21. [Supporter](https://github.com/hagezi/dns-blocklists/stargazers) - Leave a star (top right)!
22. [Recommendation](#recommendation) - [Which version of the lists should I use?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#whatshouldiuse)
23. [Online DNS Services](#dnsservices)
24. [About](#about) : [Repository](#repository) - [Referral Domains](#referral) - [Support Me](#support)
25. [FAQ](https://github.com/hagezi/dns-blocklists/wiki/FAQ) - Frequently Asked Questions
26. [Sources](sources.md)
27. [Contact](#contact)

### :books: **Multi - Cleans the Internet and protects your privacy!** <a name="overview"></a>

An all-in-one DNS blocklist in **various versions (light, normal, pro, pro++ and ultimate)**. It can be used as a standalone blocklist. For every region. Blocks ads, affiliate, tracking, metrics, telemetry, fake, phishing, malware, scam, cryptojacking and other "crap". Based on [various blocklists](sources.md). No, they are not just block lists cobbled together from different sources. They have been optimized and extended to efficiently "clean the Internet" in all areas.             

See also: [Which sources are used for the lists and how are the lists compiled on the basis of these sources?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#sources)

#### **Blocklist version and size overview:**

| Version | Entries | Pro++ | Pro | Nor<br>mal | Light | [Fake](#fake) | [TIF](#tif) | [Nat<br>ive](#native) | [PopUp<br>Ads](#popupads) | Bug<br>Tracker |
|:--------|---:|:------:|:-----:|:----:|:----:|:---:|:------:|:----------:|:----:|:----:|
| :green_book:[Light](#light)             | 88878<br>48719     |  |   |   | :green_circle:  |  | |  :yellow_square: | | |
| :blue_book:[Normal](#normal)       | 332948<br>158302     |  |   | :green_circle: | :green_circle: |  | :yellow_square: | :yellow_square: | :yellow_square: | |
| :ledger:[Pro](#pro)              | 445977<br>209142         |  | :green_circle: | :green_circle: | :green_circle: | | :yellow_square: | :yellow_square: | :yellow_square: | :green_circle: |
| :orange_book:[Pro++](#proplus)    | 605433<br>303874 | :green_circle: | :green_circle: | :green_circle: | :green_circle: | |:yellow_square: | :yellow_square: | :green_circle: | :green_circle: |
| :closed_book:[Ultimate](#ultimate)    | 722369<br>384269 | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :yellow_square: | :green_circle: | :green_circle: | :green_circle: |

:green_circle: contains the list named in the column caption
:yellow_square: partially contains the list named in the column caption

#### **Blocking level:**

| Version | Blocking<br>level | Blocking<br>type |
|:--------|:---------------|:--------------|
| :green_book:[Light](#light)        | :green_book::green_book:                                                                    | Relaxed             |
| :blue_book:[Normal](#normal)       | :blue_book::blue_book::blue_book:                                                           | Relaxed/Balanced    |
| :ledger:[Pro](#pro)                | :ledger::ledger::ledger::ledger:                                                            | Balanced            |
| :orange_book:[Pro++](#proplus)     | :orange_book::orange_book::orange_book::orange_book::orange_book::orange_book:              | Balanced/Aggressive |
| :closed_book:[Ultimate](#ultimate) | :closed_book::closed_book::closed_book::closed_book::closed_book::closed_book::closed_book: | Aggressive |

> [!TIP]
> :information_desk_person: [Which version of the lists should I use?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#whatshouldiuse)

---

### :green_book: **Multi LIGHT** - **Basic protection** <a name="light"></a>

Hand brush - Cleans the Internet and protects your privacy! Blocks Ads, Tracking, Metrics and some Badware. A size-optimized version of the Multi NORMAL.

> [!NOTE]
> **Blocking type:** Relaxed              
> This list version should not lead to any restrictions. It is particularly suitable for environments in which there is no admin nearby who can unblock something and if you have to pay attention to the size of the list, because the AdBlocker does not support large lists.

> [!IMPORTANT]
> Does not block error trackers such as Bugsnag, Crashlytics, Firebase, Instabug, Sentry, ... and other app-specific crash trackers. These are only blocked from the Pro version onwards.

**Entries:** 88878 domains/hosts - 9876 compressed hosts - 48719 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/light.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/light.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/light.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/light.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/light.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/light.txt) | AdAway, uMatrix, DNS66, NetGuard |
| Hosts<br>Compressed | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/light-compressed.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/light-compressed.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/light-compressed.txt) | Hostfile, Linux |
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/light.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/light.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/light.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/light.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/light.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/light.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/light.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/light.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/light.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/light-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/light-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/light-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/light.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/light.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/light.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
| PAC | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/pac/light.pac) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/pac/light.pac) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/pac/light.pac) | Proxy Auto Configuration |

### :blue_book: **Multi NORMAL** - **All-round protection** <a name="normal"></a>

Broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Cryptojacking and other "Crap".

> [!NOTE]
> **Blocking type:** Relaxed/Balanced              
> This list version should not lead to any restrictions for the most part. It is particularly suitable for environments in which there is no admin nearby who can unblock something.

> [!IMPORTANT]
> Does not block error trackers such as Bugsnag, Crashlytics, Firebase, Instabug, Sentry, ... and other app-specific crash trackers. These are only blocked from the Pro version onwards.

**Entries:** 332948 domains/hosts - 36995 compressed hosts - 158302 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/multi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/multi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/multi.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/multi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/multi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/multi.txt) | AdAway, uMatrix, DNS66, NetGuard |
| Hosts<br>Compressed | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/multi-compressed.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/multi-compressed.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/multi-compressed.txt) | Hostfile, Linux |
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/multi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/multi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/multi.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/multi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/multi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/multi.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/multi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/multi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/multi.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/multi-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/multi-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/multi-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/multi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/multi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/multi.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### :ledger: **Multi PRO** - **Extended protection (Recommended)** <a name="pro"></a>

Big broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Cryptojacking and other "Crap".

> [!NOTE]
> **Blocking type:** Balanced            
> This list version should only very rarely lead to restrictions. It is suitable for environments where there is an admin nearby who can unblock something. My personal recommendation for mostly problem-free adblocking with good privacy protection.

**Entries:** 445977 domains/hosts - 49553 compressed hosts - 209142 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/pro.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/pro.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/pro.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/pro.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/pro.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/pro.txt) | AdAway, uMatrix, DNS66, NetGuard |
| Hosts<br>Compressed | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/pro-compressed.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/pro-compressed.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/pro-compressed.txt) | Hostfile, Linux |
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/pro.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/pro.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/pro.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/pro.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/pro.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/pro.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/pro.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/pro-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/pro-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/pro.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/pro.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/pro.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :ledger: **Multi PRO mini (Recommended for browser/mobile adblockers)** <a name="promini"></a>

Size-optimised version for DNS/Browser adblockers, e.g. for devices with less RAM. This list only contains domains from the Pro full that have been found on Top 1/10M lists (Umbrella, Cloudflare, Tranco, Chrome, BuiltWith, Majestic, DomCop).

**Entries:** 66951 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/pro.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/pro.mini.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/pro.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/pro.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/pro.mini.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/pro.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/pro.mini.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/pro.mini-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.mini-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/pro.mini-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/pro.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/pro.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/pro.mini.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### :orange_book: **Multi PRO++** - **Maximum protection** <a name="proplus"></a>

Sweeper - Aggressive cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Cryptojacking and other "Crap".

> [!NOTE]
> **Blocking type:** Balanced/Aggressive              
> More aggressive version of the Multi PRO blocklist. It may contain a few false positive domains that limit functionality. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains.

> [!WARNING]
> **Referral domains (affiliate and tracking links):**           
> A few referral domains that also function as normal trackers are blocked. For further details see: [Referral domains](https://github.com/hagezi/dns-blocklists/wiki/FAQ#referral)

**Entries:** 605433 domains/hosts - 67271 compressed hosts - 303874 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/pro.plus.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/pro.plus.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/pro.plus.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/pro.plus.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/pro.plus.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/pro.plus.txt) | AdAway, uMatrix, DNS66, NetGuard |
| Hosts<br>Compressed | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/pro.plus-compressed.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/pro.plus-compressed.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/pro.plus-compressed.txt) | Hostfile, Linux |
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.plus.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/pro.plus.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/pro.plus.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/pro.plus.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/pro.plus.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/pro.plus.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/pro.plus.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.plus.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/pro.plus.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/pro.plus-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.plus-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/pro.plus-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/pro.plus.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/pro.plus.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/pro.plus.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :orange_book: **Multi PRO++ mini** <a name="proplusmini"></a>

Size-optimised version for DNS/Browser adblockers, e.g. for devices with less RAM. This list only contains domains from the Pro++ full that have been found on Top 1/10M lists (Umbrella, Cloudflare, Tranco, Chrome, BuiltWith, Majestic, DomCop).

**Entries:** 81257 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/pro.plus.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/pro.plus.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/pro.plus.mini.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/pro.plus.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/pro.plus.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/pro.plus.mini.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/pro.plus.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.plus.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/pro.plus.mini.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/pro.plus.mini-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/pro.plus.mini-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/pro.plus.mini-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/pro.plus.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/pro.plus.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/pro.plus.mini.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

### :closed_book: **Multi ULTIMATE** - **Aggressive protection** <a name="ultimate"></a>

Ultimate Sweeper - Strictly cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Free Hoster, Fake, Cryptojacking and other "Crap".

> [!NOTE]
> **Blocking type:** Aggressive              
> Stricter version of the Multi PRO++ blocklist. It contains domains that limit functionality in apps and on websites - some popular trackers, that lead to restrictions, are blocked in this list. Therefore it should only be used by experienced users. Furthermore, an admin should be available to unblock incorrectly blocked domains.       

> [!WARNING]
> **Referral domains (affiliate and tracking links):**           
> A few referral domains that also function as normal trackers are blocked. For further details see: [Referral domains](https://github.com/hagezi/dns-blocklists/wiki/FAQ#referral)
>                   
> **Facebook:**          
> Some META trackers are blocked in Ultimate. This restricts the use of Facebook and Facebook Messenger apps. Furthermore, the Whatsapp graph trackers are blocked, which leads to restrictions when creating avatars, using the in-app helpcenter and using video effects. Otherwise, blocking has no effect on Whatsapp functionalities. To use META apps with Ultimate, unblock the following domains if necessary: [META Tracker](share/facebook.txt)
>           
> **Windows/XBox:**          
> Some Microsoft trackers are blocked in Ultimate, which lead to restrictions, e.g. Windows Spotlight, XBox Live Achievements Activity History and others. For details and which domains must be unblocked for which function, see: [Microsoft Tracker](share/microsoft.txt).
>                   
> **Location and IP trackers:**                           
> Certain location and IP trackers used by websites to identify or monitor your IP address and geographic location are blocked. This enhances privacy but may lead to issues such as incorrect regional settings, additional CAPTCHAs, or reduced website functionality. These trackers are commonly employed for hidden analytics and targeted advertising.
>                    
>**Miscellaneous:**          
> Details on other known issues can be found [here](share/ultimate-known-issues.txt).  
                   
**Entries:** 722369 domains/hosts - 80264 compressed hosts - 384269 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/ultimate.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/ultimate.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/ultimate.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/ultimate.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/ultimate.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/ultimate.txt) | AdAway, uMatrix, DNS66, NetGuard |
| Hosts<br>Compressed | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/ultimate-compressed.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/ultimate-compressed.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/ultimate-compressed.txt) | Hostfile, Linux |
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/ultimate.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/ultimate.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/ultimate.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/ultimate.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/ultimate.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/ultimate.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/ultimate.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/ultimate.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/ultimate.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/ultimate-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/ultimate-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/ultimate-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/ultimate.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/ultimate.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/ultimate.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :closed_book: **Multi ULTIMATE mini** <a name="ultimatemini"></a>

Size-optimised version for DNS/Browser adblockers, e.g. for devices with less RAM. This list only contains domains from the Ultimate full that have been found on Top 1/10M lists (Umbrella, Cloudflare, Tranco, Chrome, BuiltWith, Majestic, DomCop).

**Entries:** 90678 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/ultimate.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/ultimate.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/ultimate.mini.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/ultimate.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/ultimate.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/ultimate.mini.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/ultimate.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/ultimate.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/ultimate.mini.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/ultimate.mini-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/ultimate.mini-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/ultimate.mini-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/ultimate.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/ultimate.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/ultimate.mini.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :trollface: **Fake - Protects against internet scams, traps & fakes!** <a name="fake"></a>

A blocklist for blocking fake stores, -streaming, rip-offs, cost traps and co.

|             | Light | Normal          | Pro            | Pro++          | Ultimate       | TIF<br>TIF medium |
|:-----------:|:-----:|:---------------:|:--------------:|:--------------:|:--------------:|:--------------:|
| Included in | :x:   | :x: | :x: | :x: | :green_circle: | :green_circle: |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 14056 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/fake.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/fake.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/fake.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/fake.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/fake.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/fake.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/fake.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/fake.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/fake.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/fake-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/fake-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/fake-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/fake.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/fake.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/fake.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :tada: **Pop-Up Ads - Protects against annoying and malicious pop-up ads!** <a name="popupads"></a>

A blocklist for annoying and malicious pop-up ads.

|             | Light          | Normal         | Pro            | Pro++          | Ultimate       | TIF      |
|:-----------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------:|
| Included in | :x: | :yellow_square: | :yellow_square: | :green_circle: | :green_circle: | :yellow_square: |

:green_circle: yes :yellow_square: partially :x: no

> [!NOTE]
> Fully included in Pro++ and Ultimate. Partially in Pro. In the combination of the Pro and additionally the Threat Intelligence Feeds (TIF) Medium or Full, all domains from the Pop-Up Ads list are included. This means that if you use the Pro and also the TIF medium or full, you no longer need to add this list separately.

**Entries:** 108209 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/popupads.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/popupads.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/popupads.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/popupads.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/popupads.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/popupads.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/popupads.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/popupads.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/popupads.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/popupads-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/popupads-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/popupads-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/popupads.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/popupads.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/popupads.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :closed_lock_with_key: **Threat Intelligence Feeds - Increases security significantly! (Recommended)** <a name="tif"></a>

A blocklist for blocking Malware, Cryptojacking, Scam, Spam and Phishing. Blocks domains known to spread malware, launch phishing attacks and host command-and-control servers.

|             | Light           | Normal          | Pro             | Pro++           | Ultimate        |
|:-----------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Included in | :x: | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 820138 domains/hosts - 91127 compressed hosts - 689252 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/tif.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/tif.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/tif.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/tif.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/tif.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/tif.txt) | AdAway, uMatrix, DNS66, NetGuard |
| Hosts<br>Compressed | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/tif-compressed.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/tif-compressed.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/tif-compressed.txt) | Hostfile, Linux |
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/tif.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/tif.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/tif.txt) | Pi-hole, ~~AdGuard~~ (too big!), AdGuard Home (only devices with >= 1GB RAM!), eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/tif.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/tif.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/tif.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/tif.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/tif.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/tif-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/tif-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/tif.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/tif.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/tif.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :closed_lock_with_key: **Threat Intelligence Feeds - Medium version (Recommended for browser/mobile adblockers)** <a name="tifmedium"></a>

A medium version of the Threat Intelligence Feeds list. Designed for Adblockers that have problems with the size of the full TIF list. Contains only important feeds.

|             | Light           | Normal          | Pro             | Pro++           | Ultimate        |
|:-----------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Included in | :x: | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 371080 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/tif.medium.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/tif.medium.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/tif.medium.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/tif.medium.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/tif.medium.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/tif.medium.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/tif.medium.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif.medium.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/tif.medium.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/tif.medium-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif.medium-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/tif.medium-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/tif.medium.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/tif.medium.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/tif.medium.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :closed_lock_with_key: **Threat Intelligence Feeds - Mini version** <a name="tifmini"></a>

A size-optimised version of the Threat Intelligence Feeds Medium list. Designed for Adblockers that have problems with the size of the TIF Medium list.

|             | Light           | Normal          | Pro             | Pro++           | Ultimate        |
|:-----------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Included in | :x: | :yellow_square: | :yellow_square: | :yellow_square: | :yellow_square: |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 150935 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/tif.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/tif.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/tif.mini.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/tif.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/tif.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/tif.mini.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/tif.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/tif.mini.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/tif.mini-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/tif.mini-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/tif.mini-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/tif.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/tif.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/tif.mini.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :closed_lock_with_key: **Threat Intelligence Feeds - IPs** <a name="tifips"></a>

IPv4 lists in [plain IP format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/ips/tif.txt) for firewalls and [AdGuard Home format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif-ips.txt) are also available as an extension to the TIF list.

> [!TIP]
> If the IP list is used in AdGuard Home, all domains that would resolve to the blocked IP are blocked. To prevent the blocked domains from being resolved via IPv6, it is necessary to deactivate resolving via IPv6 in AdGuard Home:                        
> `Settings > DNS settings > DNS server configuration > Disable resolving of IPv6 addresses`

---

### :new: **Newly Registered Domains (NRD)** <a name="nrd"></a>

Newly registered domains (NRDs) are commonly used by threat actors for phishing, malware, and command-and-control infrastructure due to their disposable nature, which helps evade detection. However, relying on NRDs alone risks false positives since legitimate organizations also register new domains for branding or infrastructure.
        
| Time<br>period | Format<br>AdBlock | Format<br>Domains |         
|:--------------:|:-----------------:|:-----------------:|
| 7 days ago to yesterday    | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/nrd7.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/nrd7.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/nrd7.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/nrd7.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/nrd7.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/nrd7.txt) |
| 14 days ago to 8 days ago  | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/nrd14-8.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/nrd14-8.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/nrd14-8.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/nrd14-8.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/nrd14-8.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/nrd14-8.txt) |
| 21 days ago to 15 days ago | | |
| 28 days ago to 22 days ago | | |
| 35 days ago to 29 days ago | | |
             
> [!NOTE]
> To block NRDs from the last 14 days, combine the domain lists from 7 days ago and 14 days ago. For blocking NRDs from the last 21 days, combine lists from 7, 14, and 21 days ago. Etc.

---

### :outbox_tray: **DoH/VPN/TOR/Proxy Bypass - Prevent methods to bypass your DNS!** <a name="bypass"></a>

Prevent methods to bypass your DNS.

> [!NOTE]
> To ensure the bootstrap is your DNS server you must redirect or block standard DNS outbound (TCP/UDP 53) and block all DNS over TLS/QUIC (TCP/UDP 853) outbound.

**The block list exists in two versions:**

#### **Complete Edition - Encrypted DNS Servers, VPN, TOR, Proxies** <a name="bypass_all"></a>

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 4822 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/doh-vpn-proxy-bypass.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/doh-vpn-proxy-bypass.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/doh-vpn-proxy-bypass.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/doh-vpn-proxy-bypass.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/doh-vpn-proxy-bypass.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/doh-vpn-proxy-bypass.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/doh-vpn-proxy-bypass.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh-vpn-proxy-bypass.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/doh-vpn-proxy-bypass.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/doh-vpn-proxy-bypass-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh-vpn-proxy-bypass-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/doh-vpn-proxy-bypass-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/doh-vpn-proxy-bypass.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/doh-vpn-proxy-bypass.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/doh-vpn-proxy-bypass.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :outbox_tray: **Encrypted DNS Servers only** <a name="bypass_dns"></a>

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 1640 domains/hosts - 183 compressed hosts - 1480 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Domains<br>Subdomains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/doh.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/doh.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/doh.txt) | Blocky (older than v0.23), Diversion (older than v5), OpenSnitch, PersonalBlocklist, pfBlockerNG |
| Hosts | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/doh.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/doh.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/doh.txt) | AdAway, uMatrix, DNS66, NetGuard |
| Hosts<br>Compressed | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/doh-compressed.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/doh-compressed.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/doh-compressed.txt) | Hostfile, Linux |
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/doh.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/doh.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/doh.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/doh.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/doh.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/doh.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/doh.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/doh.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/doh-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/doh-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/doh-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/doh.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/doh.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/doh.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :outbox_tray: **Encrypted DNS Servers IPs** <a name="bypass_ips"></a>

IPv4 lists in [plain IP format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/ips/doh.txt) for firewalls and [AdGuard Home format](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-ips.txt) are also available.

> [!TIP]
> If the IP list is used in AdGuard Home, all domains that would resolve to the blocked IP are blocked. To prevent the blocked domains from being resolved via IPv6, it is necessary to deactivate resolving via IPv6 in AdGuard Home:                   
> `Settings > DNS settings > DNS server configuration > Disable resolving of IPv6 addresses`

---

### :mag: **Safesearch not supported - Prevent the use of search engines that do not support Safesearch!** <a name="safesearch"></a>

A blocklist for blocking search engines that do not support Safesearch.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 183 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/nosafesearch.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/nosafesearch.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/nosafesearch.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/nosafesearch.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/nosafesearch.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/nosafesearch.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/nosafesearch.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/nosafesearch.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/nosafesearch.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/nosafesearch-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/nosafesearch-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/nosafesearch-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/nosafesearch.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/nosafesearch.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/nosafesearch.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :lock_with_ink_pen: **Dynamic DNS blocking - Protects against the malicious use of dynamic DNS services!** <a name="dyndns"></a>

A blocklist for blocking dynamic DNS services to protect against malicious use in phishing campaigns and others.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 1474 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/dyndns.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/dyndns.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/dyndns.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/dyndns.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/dyndns.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/dyndns.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/dyndns.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/dyndns.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/dyndns.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/dyndns-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/dyndns-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/dyndns-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/dyndns.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/dyndns.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/dyndns.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :computer: **Badware Hoster blocking - Protects against the malicious use of host services!** <a name="hoster"></a>

A blocklist for blocking known hosters that also host badware via user content to prevent the use of these hosters for malicious purposes.

> [!IMPORTANT]
> This list blocks the root domains of all hosting providers that occasionally appear in threat intelligence feeds due to malicious subdomains. Please be aware that this will also block legitimate sites hosted by these providers. Consider this carefully before using the list.
>                 
> When using this list, users are responsible for unblocking any required subdomains themselves.

|             | Light | Normal | Pro | Pro++ | Ultimate | TIF |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|:---:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      | :x: |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 2135 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/hoster.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/hoster.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/hoster.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/hoster.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/hoster.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/hoster.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/hoster.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/hoster.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/hoster.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/hoster-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/hoster-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/hoster-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/hoster.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/hoster.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/hoster.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |
| ControlD | [CDN](https://github.com/hagezi/dns-blocklists/blob/main/controld/badware-hoster-folder.json)| ControlD folder |

---

### :calling: **URL Shortener - Blocks link shortener!** <a name="urlshortener"></a>

A blocklist for blocking all known URL/link shortener.

> [!WARNING]
> Not suitable for use in standard environments. Blocking all URL shorteners is recommended mainly in highly sensitive environments, as they can hide link destinations and facilitate attacks. In less sensitive settings, monitoring, selective blocking, or user education usually suffice to manage risks.
>                 
> When using this list, users are responsible for unblocking any required domains themselves.

|             | Light | Normal | Pro | Pro++ | Ultimate | TIF |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|:---:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      | :x: |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 6448 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/urlshortener.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/urlshortener.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/urlshortener.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/urlshortener.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/urlshortener.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/urlshortener.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/urlshortener.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/urlshortener.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/urlshortener.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/urlshortener-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/urlshortener-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/urlshortener-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/urlshortener.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/urlshortener.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/urlshortener.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :crystal_ball: **Most Abused TLDs - Protects against known malicious Top Level Domains! (Recommended)** <a name="tlds"></a>

A blocklist for blocking Top Most Abused Top Level Domains, merged from [@Yokoffing](https://github.com/yokoffing), [@DandelionSprout](https://github.com/DandelionSprout/), [@LennyFox](https://github.com/lennyfox) Cloudflare Radar, Netcraft and SpamHaus.

> [!WARNING]
> The Most Abused TLDs list is designed to block entire top-level domains (such as *.top, *.shop, *.gdn) with poor reputations. While this may also block some legitimate sites, it is highly effective at preventing spam, scams, phishing, malware, and other malicious content. Users should be aware of which sites are affected by this list.
>
> Only widely-used, reputable domains, such as those appearing on major top lists (Umbrella, Cloudflare, Tranco, Chrome, DomCop, etc.) or those essential for popular apps and services will be considered for exclusion. Illegal domains, including those related to piracy, will not be unblocked. Domains that do not meet these criteria are reviewed individually; if exclusion is not justified, they remain blocked. Users who need access to such domains should add them to their personal allowlist.
>
> This selective approach is necessary because AdGuard and uBlock Origin have technical limits on rule length when using denyallow/domain modifiers. Attempting to exclude every legitimate domain would eventually break important rules, so exclusions must be limited and carefully chosen.
              
|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| AdGuard | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/spam-tlds.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/spam-tlds.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/spam-tlds.txt) | AdGuard, AdGuard Home |
| uBlock Origin  | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/spam-tlds-ublock.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/spam-tlds-ublock.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/spam-tlds-ublock.txt) | uBlock Origin, Adblock Plus |
| AdBlock  | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/spam-tlds-adblock.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/spam-tlds-adblock.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/spam-tlds-adblock.txt) | Pi-hole, TechnitiumDNS<br>Contains only spam TLDs that do not have any exclusions. |
| AdBlock<br>(Aggressive)<br><br>Allowlist<br><br> | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/spam-tlds-adblock-aggressive.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/spam-tlds-adblock-aggressive.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/spam-tlds-adblock-aggressive.txt)<br><br>[CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/spam-tlds-adblock-allow.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/spam-tlds-adblock-allow.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/spam-tlds-adblock-allow.txt) | Pi-hole, TechnitiumDNS |
| Wildcard<br>Domains<br><br>Allowlist<br><br> | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/spam-tlds-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/spam-tlds-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/spam-tlds-onlydomains.txt)<br><br>[CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/spam-tlds-allow-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/spam-tlds-allow-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/spam-tlds-allow-onlydomains.txt) | DNSCrypt |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/spam-tlds-rpz.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/spam-tlds-rpz.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/spam-tlds-rpz.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound<br>Contains only spam TLDs that do not have any exclusions. |
| RPZ<br>(Aggressive) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/spam-tlds-rpz-aggressive.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/spam-tlds-rpz-aggressive.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/spam-tlds-rpz-aggressive.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound<br>Contains all spam TLDs, corresponds to the AdGuard and uBlock Origin version without exclusions. |
| ControlD | [CDN](https://github.com/hagezi/dns-blocklists/blob/main/controld/spam-tlds-combined-folder.json) | ControlD folder |

---

### :skull: **Anti Piracy - Protects against piracy!** <a name="piracy"></a>

Blocks websites and services that are mainly used for the illegal distribution of copyrighted content.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 11127 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/anti.piracy.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/anti.piracy.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/anti.piracy.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/anti.piracy.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/anti.piracy.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/anti.piracy.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/anti.piracy.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/anti.piracy.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/anti.piracy.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/anti.piracy-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/anti.piracy-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/anti.piracy-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/anti.piracy.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/anti.piracy.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/anti.piracy.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :slot_machine: **Gambling - Protects against gambling content!** <a name="gambling"></a>

Blocks gambling content.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 183956 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/gambling.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/gambling.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/gambling.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/gambling.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/gambling.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/gambling.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/gambling.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/gambling.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/gambling.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/gambling-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/gambling-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/gambling-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/gambling.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/gambling.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/gambling.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :slot_machine: **Gambling - Medium version** <a name="gamblingmedium"></a>

A medium version of the Gambling list. Designed for Adblockers that have problems with the size of the full Gambling list.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 90887 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/gambling.medium.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/gambling.medium.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/gambling.medium.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/gambling.medium.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/gambling.medium.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/gambling.medium.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/gambling.medium.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/gambling.medium.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/gambling.medium.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/gambling.medium-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/gambling.medium-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/gambling.medium-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/gambling.medium.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/gambling.medium.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/gambling.medium.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

#### :slot_machine: **Gambling - Mini version** <a name="gamblingmini"></a>

A size-optimised version of the Gambling Medium list. This list only contains domains that have been found on Top 1/10M lists (Umbrella, Cloudflare, Tranco, Chrome, BuiltWith, Majestic, DomCop).

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 31966 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/gambling.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/gambling.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/gambling.mini.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam, Little Snitch Mini |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/gambling.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/gambling.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/gambling.mini.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/gambling.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/gambling.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/gambling.mini.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/gambling.mini-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/gambling.mini-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/gambling.mini-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/gambling.mini.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/gambling.mini.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/gambling.mini.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :underage: **NSFW - Protects against adult content!** <a name="nsfw"></a>

Blocks adult content.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :x:   | :x:    | :x: | :x:   | :x:      |

:green_circle: yes :yellow_square: partially :x: no

**Entries:** 124119 compressed domains

| Format | Links | Should be used for |
|:-------|:-----|:----------------|
| Adblock | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/nsfw.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/nsfw.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/nsfw.txt) | Pi-hole, AdGuard, AdGuard Home, eBlocker, uBlock Origin, Brave (only in aggressive mode), AdNauseam |
| DNSMasq | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/nsfw.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/nsfw.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/nsfw.txt) | DNSMasq (v2.86 or newer), adblock-lean, Diversion (v5 or newer) |
| Wildcard<br>Asterisk | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/nsfw.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/nsfw.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/nsfw.txt) | Blocky (v0.23 or newer), Nebulo, NetDuma, OPNsense, YogaDNS |
| Wildcard<br>Domains | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/nsfw-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/nsfw-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/nsfw-onlydomains.txt) | DNSCloak, DNSCrypt, TechnitiumDNS, PersonalDNSfilter, InviZible Pro |
| RPZ | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/nsfw.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/nsfw.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/nsfw.txt) | Response Policy Zone, Bind, Knot, PowerDNS, Unbound |

---

### :calling: **Native Tracker - Broadband tracker of devices, services and operating systems** <a name="native"></a>

Blocks native broadband tracker from devices, services and operating systems that track your activity.

|             | Light | Normal | Pro | Pro++ | Ultimate |
|:-----------:|:-----:|:------:|:---:|:-----:|:--------:|
| Included in | :yellow_square:   | :yellow_square:    | :yellow_square: | :yellow_square:  | :green_circle:      |

:green_circle: yes :yellow_square: partially :x: no

> [!IMPORTANT]
> The native tracker lists encompass all trackers used for monitoring user activity, which may also result in certain restrictions. These lists are integrated across the standard tiers—Light, Normal, Pro, Pro++, and Ultimate—each providing different levels of blocking:
>          
> - Light to Pro: These lists only block native trackers that do not interfere with functionality, ensuring a smooth experience.
> - Pro++ (Aggressive): This list blocks additional native trackers that may cause some restrictions or limit certain features.
> - Ultimate: This list provides the most comprehensive blocking, including all native trackers for maximum privacy.
>           
> By choosing a specific list version, you can control how aggressively native trackers are blocked according to your preferences.
>               
> When combining native tracker lists with standard lists, you may need to manually unblock certain native trackers as required.

| Device/Service | Domains | Hosts | Adblock | DNSMasq | Wildcard<br>Asterisk | Wildcard<br>Domains | RPZ |
|:-------|:--------:|:------:|:--------:|:--------:|:---------:|:--------:|:--------:|
| Amazon (Devices, Shopping, Video) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.amazon.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.amazon.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.amazon.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.amazon.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.amazon.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.amazon.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.amazon.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.amazon.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.amazon.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.amazon.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.amazon.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.amazon.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.amazon.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.amazon.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.amazon.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.amazon-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.amazon-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.amazon-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.amazon.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.amazon.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.amazon.txt) |
| Apple (iOS, macOS, tvOS) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.apple.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.apple.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.apple.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.apple.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.apple.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.apple.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.apple.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.apple.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.apple.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.apple.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.apple.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.apple.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.apple.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.apple.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.apple.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.apple-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.apple-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.apple-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.apple.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.apple.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.apple.txt) |
| Huawei (Devices) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.huawei.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.huawei.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.huawei.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.huawei.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.huawei.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.huawei.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.huawei.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.huawei.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.huawei.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.huawei.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.huawei.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.huawei.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.huawei.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.huawei.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.huawei.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.huawei-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.huawei-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.huawei-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.huawei.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.huawei.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.huawei.txt) |
| Microsoft (Windows, Office, MSN) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.winoffice.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.winoffice.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.winoffice.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.winoffice.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.winoffice.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.winoffice.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.winoffice.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.winoffice.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.winoffice.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.winoffice.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.winoffice.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.winoffice.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.winoffice.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.winoffice.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.winoffice.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.winoffice-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.winoffice-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.winoffice-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.winoffice.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.winoffice.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.winoffice.txt) |
| Samsung | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.samsung.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.samsung.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.samsung.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.samsung.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.samsung.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.samsung.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.samsung.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.samsung.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.samsung.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.samsung.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.samsung.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.samsung.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.samsung.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.samsung.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.samsung.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.samsung-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.samsung-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.samsung-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.samsung.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.samsung.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.samsung.txt) |
| TikTok (Fingerprinting) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.tiktok.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.tiktok.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.tiktok.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.tiktok.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.tiktok.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.tiktok.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.tiktok.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.tiktok.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.tiktok.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.tiktok.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.tiktok.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.tiktok.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.tiktok.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.tiktok.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.tiktok.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.tiktok-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.tiktok-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.tiktok-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.tiktok.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.tiktok.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.tiktok.txt) |
| TikTok (Fingerprinting) Aggressive | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.tiktok.extended.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.tiktok.extended.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.tiktok.extended.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.tiktok.extended.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.tiktok.extended.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.tiktok.extended.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.tiktok.extended.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.tiktok.extended.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.tiktok.extended.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.tiktok.extended.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.tiktok.extended.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.tiktok.extended.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.tiktok.extended.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.tiktok.extended.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.tiktok.extended.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.tiktok.extended-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.tiktok.extended-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.tiktok.extended-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.tiktok.extended.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.tiktok.extended.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.tiktok.extended.txt) |
| LG webOS | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.lgwebos.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.lgwebos.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.lgwebos.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.lgwebos.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.lgwebos.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.lgwebos.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.lgwebos.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.lgwebos.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.lgwebos.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.lgwebos.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.lgwebos.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.lgwebos.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.lgwebos.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.lgwebos.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.lgwebos.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.lgwebos-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.lgwebos-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.lgwebos-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.lgwebos.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.lgwebos.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.lgwebos.txt) |
| Roku | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.roku.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.roku.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.roku.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.roku.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.roku.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.roku.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.roku.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.roku.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.roku.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.roku.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.roku.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.roku.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.roku.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.roku.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.roku.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.roku-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.roku-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.roku-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.roku.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.roku.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.roku.txt) |
| Vivo | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.vivo.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.vivo.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.vivo.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.vivo.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.vivo.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.vivo.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.vivo.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.vivo.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.vivo.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.vivo.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.vivo.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.vivo.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.vivo.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.vivo.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.vivo.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.vivo-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.vivo-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.vivo-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.vivo.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.vivo.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.vivo.txt) |
| OPPO/Realme | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.oppo-realme.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.oppo-realme.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.oppo-realme.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.oppo-realme.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.oppo-realme.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.oppo-realme.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.oppo-realme.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.oppo-realme.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.oppo-realme.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.oppo-realme.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.oppo-realme.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.oppo-realme.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.oppo-realme.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.oppo-realme.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.oppo-realme.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.oppo-realme-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.oppo-realme-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.oppo-realme-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.oppo-realme.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.oppo-realme.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.oppo-realme.txt) |
| Xiaomi | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/domains/native.xiaomi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/domains/native.xiaomi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/domains/native.xiaomi.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/hosts/native.xiaomi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/hosts/native.xiaomi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/hosts/native.xiaomi.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/adblock/native.xiaomi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/adblock/native.xiaomi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/adblock/native.xiaomi.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/dnsmasq/native.xiaomi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/dnsmasq/native.xiaomi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/dnsmasq/native.xiaomi.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.xiaomi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.xiaomi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.xiaomi.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/wildcard/native.xiaomi-onlydomains.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/wildcard/native.xiaomi-onlydomains.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/wildcard/native.xiaomi-onlydomains.txt) | [CDN](https://cdn.jsdelivr.net/gh/hagezi/dns-blocklists@latest/rpz/native.xiaomi.txt) [GL](https://gitlab.com/hagezi/mirror/-/raw/main/dns-blocklists/rpz/native.xiaomi.txt) [CB](https://codeberg.org/hagezi/mirror2/raw/branch/main/dns-blocklists/rpz/native.xiaomi.txt) |

---

### :bulb: **Recommendation** <a name="recommendation"></a>

As a network-wide DNS blocker, I recommend using [Adguard Home](https://adguard.com), [Pi-hole](https://pi-hole.net/), [TechnitiumDNS](https://technitium.com/dns/), [Blocky](https://github.com/0xERR0R/blocky) (advanced users), [adblock-lean](https://github.com/lynxthecat/adblock-lean) (OpenWrt) or [eBlocker](https://eblocker.org/).

DNS blockers offer good protection of privacy by blocking tracking, metrics and telemetry. They can be used to block the vast majority of ads, malware, scam, fake and co, but not everything can be blocked at the DNS level!
Therefore, I **additionally** recommend the use of a browser content blocker such as [AdGuard](https://adguard.com), [uBlock Origin](https://ublockorigin.com) or [Ghostery](https://www.ghostery.com/).

Check out Yokoffing's [Recommended Filters for uBlock Origin](https://github.com/yokoffing/filterlists) for content blocker filter lists.

> [!TIP]
> :information_desk_person: [Which version of the lists should I use?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#whatshouldiuse)

---

### :department_store: **Online DNS Services** <a name="dnsservices"></a>

If you don't run your own DNS server on your home network or if you are looking for additional protection for your mobile devices when they are not connected to the home network, then you can use one of the following DNS services.

**Availability of the lists in the respective DNS services:** <a name="availablelists"></a>

| Service | Light | Nor<br>mal | Pro | Pro<br>++ | Ulti<br>mate | TIF | By<br>pass | Dyn<br>DNS | Hoster | TLDs | Anti<br>Piracy | Gam<br>bling | ... |
| :----- | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| AdGuard<br>DNS         | :x:            | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle:   | :green_circle:   | :green_circle: | :green_circle: | :green_circle:   | :green_circle:   | :green_circle: |
| ControlD            | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :yellow_square:  | :yellow_square:  | :notebook:            | :notebook:            | :yellow_square:  | :yellow_square:  | :x: |
| Rethink<br>DNS          | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle:   | :green_circle: | :x:            | :x:              | :x: | :x: |
| DNS<br>warden           | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :green_circle: | :x:              | :x:              | :x:            | :x:            | :x:              | :x:              | :x: |

:yellow_square: Are included in the ControlD native lists of the respective category.                        
:notebook: Available as [ControlD folder](https://github.com/hagezi/dns-blocklists/tree/main/controld).

#### :department_store: **AdGuardDNS - limited free/unlimited trial/paid** <a name="adguarddns"></a>

In [AdGuardDNS](https://adguard-dns.io) you can use my:

- Normal, Pro, Pro++, Ultimate
- Threat-Intelligence-Feeds (TIF), Most Abused TLDs, Badware Hoster, DynDNS, DNS Rebind Protection, URLshortener
- DoH/VPN/TOR/Proxy Bypass
- Gambling
- Anti Piracy
- Native Tracker (Apple, OPPO & Realme, Samsung, Vivo, Windows/Office, Xiaomi)
- Allowlist Referral

#### :department_store: **ControlD - free/paid** <a name="controld"></a>

In [ControlD](https://controld.com) you can use my Light, Normal, Pro, Pro++, Ultimate and TIF lists.

**Free:**

| Blocklists | DNS-over-HTTPS | DNS-over-TLS/QUIC | Legacy DNS | Apple |
|:-----------|:---------------|:-------------|:-------------|:---:|
| Light | `https://freedns.controld.com/x-hagezi-light` | `x-hagezi-light.freedns.controld.com` | 76.76.2.37<br>76.76.10.37<br>2606:1a40::37<br>2606:1a40:1::37 | [Link](https://api.controld.com/mobileconfig/x-hagezi-light?type=free&exclude_common=1) |
| Normal | `https://freedns.controld.com/x-hagezi-normal` | `x-hagezi-normal.freedns.controld.com` | 76.76.2.40<br>76.76.10.40<br>2606:1a40::40<br>2606:1a40:1::40 | [Link](https://api.controld.com/mobileconfig/x-hagezi-normal?type=free&exclude_common=1) |
| Pro | `https://freedns.controld.com/x-hagezi-pro` | `x-hagezi-pro.freedns.controld.com` | 76.76.2.41<br>76.76.10.41<br>2606:1a40::41<br>2606:1a40:1::41 | [Link](https://api.controld.com/mobileconfig/x-hagezi-pro?type=free&exclude_common=1) |
| Pro Plus | `https://freedns.controld.com/x-hagezi-proplus` | `x-hagezi-proplus.freedns.controld.com` | 76.76.2.42<br>76.76.10.42<br>2606:1a40::42<br>2606:1a40:1::42 | [Link](https://api.controld.com/mobileconfig/x-hagezi-proplus?type=free&exclude_common=1) |
| Ultimate | `https://freedns.controld.com/x-hagezi-ultimate` | `x-hagezi-ultimate.freedns.controld.com` | 76.76.2.45<br>76.76.10.45<br>2606:1a40::45<br>2606:1a40:1::45 | [Link](https://api.controld.com/mobileconfig/x-hagezi-ultimate?type=free&exclude_common=1) |
| TIF | `https://freedns.controld.com/x-hagezi-tif` | `x-hagezi-tif.freedns.controld.com` | 76.76.2.46<br>76.76.10.46<br>2606:1a40::46<br>2606:1a40:1::46 | [Link](https://api.controld.com/mobileconfig/x-hagezi-tif?type=free&exclude_common=1) |

**Paid:**

Check out Yokoffing's [ControlD Config Guide](https://github.com/yokoffing/Control-D-Config) for recommended [ControlD](https://controld.com) configuration settings.

#### :department_store: **RethinkDNS - free** <a name="rethinkdns"></a>

In [RethinkDNS](https://rethinkdns.com) you can use my Light, Normal, Pro, Pro++, Ultimate, TIF, DynDNS and Badware Hoster lists.

> [!NOTE]
> The lists in RethinkDNS are only updated once a week.

| Blocklists | DNS-over-HTTPS | DNS-over-TLS/QUIC |
|:-----------|:---------------|:-------------|
| Light + TIF | `https://sky.rethinkdns.com/1:AAkACAQA` | `1-aaeqacaeaa.max.rethinkdns.com` |
| Normal + TIF | `https://sky.rethinkdns.com/1:AAkACAgA` | `1-aaeqacaiaa.max.rethinkdns.com` |
| Pro + TIF  | `https://sky.rethinkdns.com/1:AAoACBAA` | `1-aafaacaqaa.max.rethinkdns.com` |
| Pro plus + TIF | `https://sky.rethinkdns.com/1:AAoACAgA` | `1-aafaacaiaa.max.rethinkdns.com` |
| Ultimate + TIF | `https://sky.rethinkdns.com/1:gAgACABA` | `1-qaeaacaaia.max.rethinkdns.com` |

#### :department_store: **DNSwarden - free** <a name="dnswarden"></a>

In [DNSwarden](https://dnswarden.com/customfilter.html) you can use my Light, Normal, Pro, Pro++, Ultimate and TIF lists.

| Blocklists | DNS-over-HTTPS | DNS-over-TLS/QUIC |
|:-----------|:---------------|:------------------|
| Light + TIF | `https://dns.dnswarden.com/00000000000000000000048` | `00000000000000000000048.dns.dnswarden.com` |
| Normal + TIF | `https://dns.dnswarden.com/00000000000000000000028` | `00000000000000000000028.dns.dnswarden.com` |
| Pro + TIF  | `https://dns.dnswarden.com/00000000000000000000018` | `00000000000000000000018.dns.dnswarden.com` |
| Pro plus + TIF | `https://dns.dnswarden.com/0000000000000000000000o` | `0000000000000000000000o.dns.dnswarden.com` |
| Ultimate + TIF | `https://dns.dnswarden.com/0000000000000000000000804` | `0000000000000000000000804.dns.dnswarden.com` |

#### :department_store: **DNSBUNKER.org (Germany) - free** <a name="dnsbunker"></a>

[DNSBUNKER.org](https://dnsbunker.org/) uses my Pro++ in combination with the TIF blocklist and the allowlist Referral.

| Blocklists | DNS-over-HTTPS/3 | DNS-over-TLS/QUIC |
|:-----------|:---------------|:------------------|
| Pro plus + TIF | `https://dnsbunker.org/dns-query` | `dnsbunker.org ` |

#### :department_store: **OpenBLD.net - free** <a name="openbld"></a>

[OpenBLD.net](https://openbld.net/docs/get-started/third-party-filters/hagezi/) uses my Pro in combination with the TIF blocklist.

| Blocklists | DNS-over-HTTPS | 
|:-----------|:---------------|
| Pro + TIF  | `https://ric.openbld.net/dns-query/hagezi` |

#### :department_store: **RobinGroppe.de (Germany) - free** <a name="robingroppe"></a>

[RobinGroppe.de DNS](https://www.robingroppe.de/serverzeug/dns-server) offers a free German DNS server without logging to block malware, phishing and other threats. It uses my TIF list.

---

### :loudspeaker: **About** <a name="about"></a>

<p align="center"><a href="https://github.com/hagezi/dns-blocklists/graphs/contributors"><img src="https://contrib.rocks/image?repo=hagezi/dns-blocklists&max=1" /></a></p>
<p align="center"><i><b>"If the plan doesn‘t work, change the plan but never the goal."<br>There's no place like 127.0.0.1!</b></i></p>

The blocklists are based on [various sources](sources.md) and my own denylists/extensions. They were designed to avoid false positive domains as much as possible without losing effectiveness and efficiency. Dead hosts are regularly removed from the lists to keep them as small as possible.
Made with :heartbeat: for a safer and cleaner internet.

All lists were tested against 10000 websites from the Cisco Umbrella Top 1 million list. It was checked whether the pages load, the page content is displayed correctly, navigation links work, images load, videos start and much more.

No, they are not just block lists cobbled together from different sources. They have been optimized and extended to efficiently "clean the Internet" in all areas. See also: [Which sources are used for the lists and how are the lists compiled on the basis of these sources?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#sources)

The results of a test against the 10000 [whotracks.me](https://whotracks.me/websites.html) pages. All pages were opened and fully loaded via batch in Edge with privacy features turned off. Cookies were all accepted.

| **List**     | Total queries | Blocked queries | % blocked | % gap to light |
|-------------:|--------------:|----------------:|----------:|---------------:|
| **Ultimate** | 299646        | 131093          | 43.75     | 12.85          |
| **Pro++**    | 299646        | 119681          | 39.94     | 9.05           |
| **Pro**      | 299646        | 97508           | 32.54     | 1.65           |
| **Normal**   | 299646        | 93258           | 31.12     | 0.23           |
| **Light**    | 299646        | 92576           | 30.90     |                |
| **----**     | 299646        | 67888           | 22.66     | -8.24          |

Test them, give feedback and [report blockable or incorrectly blocked](https://github.com/hagezi/dns-blocklists/issues) domains.

#### :octocat: Repository <a name="repository"></a>

The repository is occasionally compressed (reinitialised) to reduce the overall size. Among other things, this invalidates forks and cleans up the commit history.

#### :cyclone: Referral Domains <a name="referral"></a>

[Why are referral domains (affiliate and tracking links) not blocked in the lists?](https://github.com/hagezi/dns-blocklists/wiki/FAQ#referral)

#### :dizzy: Support Me <a name="support"></a>

If you like the project and you can benefit from it, leave a :star: (top right) and become a [stargazer](https://github.com/hagezi/dns-blocklists/stargazers)!

Give feedback, show me your ideas, report domains to be blocked, report false positive domains and help to keep the internet safe and clean.
Help and cooperation of any kind are welcome!

**Thanks for your support!**

---

### :stars: Stargazers <a name="stargazers"></a>

[![Star History Chart](https://api.star-history.com/svg?repos=hagezi/dns-blocklists&type=Date)](https://star-history.com/#hagezi/dns-blocklists&Date)

---

### **Keep the internet clean!**

---

[![https://gafam.info](https://ptrace.gafam.info/unofficial/img/color/lqdn-gafam-poster-en-color-5x1-2560x.png)](https://gafam.info)

---

<div align="center">

[![Mail](https://img.shields.io/badge/Proton%20Mail-6D4AFF.svg?style=for-the-badge&logo=Proton-Mail&logoColor=white)](mailto:hagezi@protonmail.com)
[![Signal](https://img.shields.io/badge/Signal-3B45FD.svg?style=for-the-badge&logo=Signal&logoColor=white)](https://signal.me/#eu/WlBfKuiT1S1GAGwDRpvIJErjM-C3IcjQUQ9HWLzeJKGKTfwlOGhEe7GQRSx05uX0)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4.svg?style=for-the-badge&logo=Telegram&logoColor=white)](https://t.me/hagezi)
[![Discord](https://img.shields.io/badge/Discord-5865F2.svg?style=for-the-badge&logo=Discord&logoColor=white)](https://discord.com/users/hagezi)
[![Mastodon](https://img.shields.io/badge/Mastodon-6364FF.svg?style=for-the-badge&logo=Mastodon&logoColor=white)](https://social.tchncs.de/@hagezi)
[![Bluesky](https://img.shields.io/badge/Bluesky-0285FF.svg?style=for-the-badge&logo=Bluesky&logoColor=white)](https://bsky.app/profile/hagezi.bsky.social)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white)](https://www.reddit.com/user/hagezi)

</div>

---

<a name="contact"></a>
