# All .txt files were done by Taylor Christian Newsome 
# Browsable Content of `eqgrp-auction-file.tar.xz`

* **Original archive**: [https://mega.nz/#!zEAU1AQL!oWJ63n-D6lCuCQ4AY0Cv_405hX8kn7MEsa1iLH5UjKU](https://mega.nz/#!zEAU1AQL!oWJ63n-D6lCuCQ4AY0Cv_405hX8kn7MEsa1iLH5UjKU)

* **Passphrase**:

  ```
  CrDj"(;Va.*NdlnzB9M?@K2)#>deB7mN
  ```

  (as disclosed by the Shadow Brokers, [source](https://medium.com/@shadowbrokerss/dont-forget-your-base-867d304a94b1))

* **Community summary credits**:
  `jvoisin` (@ dustri.org) and [@x0rz](https://www.twitter.com/x0rz)

- Reverse Engineered Further By Taylor Christian Newsome  [ClumsyLulz / SleepTheGod](https://www.linkedin.com/in/clumsy/)
---

⚠️ **Warning**
Some binaries may be flagged by antivirus software.

---

## Archive Notes

Nested TAR archives have been extracted into the [`archive_files`](/archive_files) directory.

---

# Content Overview

## Unknown

* **JACKLADDER**
* **DAMPCROWD**
* **ELDESTMYDLE**
* **SUAVEEYEFUL**
* **WATCHER**
* **YELLOWSPIRIT**

---

## Miscellaneous

* **DITTLELIGHT (HIDELIGHT)** — unhides **NOPEN** window to run Unix Oracle DB scripts
* **DUL** — shellcode packer
* **egg_timer** — execution delay utility (similar to `at`)
* **ewok** — SNMP enumeration tool (similar to `snmpwalk`)
* **gr** — possible web-based cron manager
* **jackladderhelper** — simple port binder
* **magicjack** — DES implementation in Perl
* **PORKSERVER** — `inetd`-based server for the **PORK** implant
* **ri** — similar to `rpcinfo`
* **uX_local** — minimal X server (likely for remote management)
* **ITIME** — modifies file timestamp metadata on Unix filesystems

---

# Remote Code Execution (RCE)

## Solaris

* **CATFLAP** — Solaris 7/8/9 (SPARC & x86) RCE
* **EASYSTREET / CMSEX** — `rpc.cmsd` remote root exploit
* **EBBISLAND / ELVISCICADA** — `snmpXdmid` overflow (`CVE-2001-0236`)
* **sneer** — Sun `snmpd` (*mibissa*) RCE with DWARF symbols
* **dtspcdx_sparc** — dtspcd exploit (SunOS 5.x)
* **TOOLTALK** — ToolTalk overflow (DEC, IRIX, Solaris ≤2.6)
* **VIOLENTSPIRIT** — CDE `ttsession` RCE (Solaris 2.6–2.9)
* **EBBISLAND** — RPC shellcode injection (Solaris 2.6–2.10)

---

## Netscape Servers

* **xp_ns-httpd** — Netscape HTTP server RCE
* **nsent** — Netscape Enterprise 4.1 RCE (Solaris)
* **eggbasket** — Netscape Enterprise 3.5 RCE (SPARC likely)

---

## FTP Servers

* **EE** — ProFTPD 1.2.8 RCE (possible `CVE-2011-4130`)
* **wuftpd** — likely `CVE-2001-0550`

---

## Web Applications

* **ESMARKCONANT** — phpBB RCE (< 2.0.11, `CVE-2004-1315`)
* **ELIDESKEW** — SquirrelMail vuln (1.4.0–1.4.7)
* **ELITEHAMMER** — RedFlag Webmail exploit (user: `nobody`)
* **ENVISIONCOLLISION** — phpBB derivative RCE
* **EPICHERO** — Avaya Media Server exploit
* **COTTONAXE** — LiteSpeed information disclosure / RCE

---

## Misc RCE

* **calserver** — RPC spooler exploit
* **EARLYSHOVEL** — Sendmail RCE (`CVE-2003-0681`, `CVE-2003-0694`)
* **ECHOWRECKER / sambal** — Samba RCE (`CVE-2003-0201`)
* **ELECTRICSLIDE** — Squid heap overflow
* **EMBERSNOUT** — Red Hat 9 Apache exploit
* **ENGAGENAUGHTY** — Apache mod_ssl (SSLv2) RCE
* **ENTERSEED** — Postfix RCE (2.0.8–2.1.5)
* **ERRGENTLE** — Exim RCE (`CVE-2001-0690`)
* **EXPOSITTRAG** — `pcnfsd` exploit
* **extinctspinash** — Chili!Soft ASP / Cobalt RaQ exploit
* **KWIKEMART** — SSH1 CRC32 exploit
* **prout** — `pcnfs` RPC abuse
* **slugger** — printer exploit (`CVE-1999-0078`)
* **statdx** — `rpc.statd` exploit (RHL 6.x)
* **telex** — telnetd exploit (`CVE-1999-0192`)
* **toffeehammer** — `cgimail` exploit
* **VS-VIOLET** — XDMCP-related Solaris exploit
* **SKIMCOUNTRY** — mobile data exfiltration
* **SLYHERETIC_CHECKS** — target validation tool
* **EMPTYBOWL** — MailCenter Gateway RCE
* **CURSEHAPPY / ORLEANSTRIDE** — CDR (call record) parsers

---

# Anti-Forensics

* **toast** — `wtmp` editor
* **pcleans** — `pacctl` cleaner
* **DIZZYTACHOMETER** — RPM DB tampering
* **DUBMOAT** — utmp manipulation
* **scrubhands** — post-operation cleanup
* **Auditcleaner** — clears `audit.log`

---

# Control / Implants

## HP-UX, Linux, SunOS

* **FUNNELOUT** — database-backed web backdoor (vBulletin)
* **hi** — UNIX bind shell
* **jackpop** — SPARC bind shell
* **NOPEN** — encrypted RAT (RC6)
* **SAMPLEMAN / ROUTER TOUCH** — Cisco targeting tools
* **SECONDDATE** — multi-OS implant
* **SHENTYSDELIGHT** — Linux keylogger
* **SIDETRACK** — implant for **PITCHIMPAIR**
* **SIFT** — multi-platform implant
* **SLYHERETIC** — stealth AIX implant
* **STRIFEWORLD** — TCP session capture + reconstruction
* **SUCTIONCHAR** — kernel-level interception implant
* **STOICSURGEON** — Linux rootkit
* **INCISION** — earlier version of StoicSurgeon

---

## Command & Control (C2)

* **Seconddate_CnC** — C2 for SECONDDATE
* **ELECTRICSIDE** — likely large-scale C2 framework
* **NOCLIENT** — C2 for NOPEN
* **DEWDROP** — unknown C2 component

---

# Privilege Escalation

## Linux

* **h** — kernel LPE (`CVE-2003-0961`)
* **gsh** — simple setuid shell
* **PTRACE / FORKPTY / km3** — kernel exploit (`CVE-2003-0127`)
* **EXACTCHANGE** — NULL deref LPE
* **ghost** — possible `statmon` exploit
* **ESTOPFORBADE** — Cobalt Linux LPE
* **ENVOYTOMATO** — Bluetooth LPE
* **ESTOPMOONLIT** — Linux LPE
* **EPOXYRESIN** — Linux LPE

---

## AIX

* **EXCEEDSALON-AIX** — privilege escalation

---

## Other

* **procsuid** — setuid Perl abuse
* **elatedmonkey** — cPanel LPE (0-day)
* **estesfox** — logwatch exploit
* **evolvingstrategy** — Kaspersky-related privesc
* **eh** — OpenWebMail LPE
* **escrowupgrade** — Solaris cachefsd exploit
* **ENGLANDBOGY** — Xorg exploit
* **endlessdonut** — Apache FastCGI LPE

---

# Interesting Artifacts

* **Default passwords list**:
  [https://github.com/x0rz/EQGRP/blob/33810162273edda807363237ef7e7c5ece3e4100/Linux/etc/.oprc](https://github.com/x0rz/EQGRP/blob/33810162273edda807363237ef7e7c5ece3e4100/Linux/etc/.oprc)

* **Notable domain reference**:
  `.gov.ru` appears in StoicSurgeon control binaries

---

## Notes

* Content originates from the **Shadow Brokers leak**.
* Many tools target legacy systems (Solaris, AIX, early Linux distributions).
* Several exploits map to known CVEs, while others remain undocumented or proprietary.

---

If you want, I can take this further and:

* Add a **table of CVEs → exploit mappings**
* Generate a **searchable index**
* Or convert this into a **DEF CON–level presentation README (with diagrams + attack chains)**
