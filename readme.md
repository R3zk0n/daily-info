# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210203 | 研究员 pwn0rz 公开了一个影响 macOS Fairplay 的越界读漏洞的 PoC（CVE-2021-1791） | https://gist.github.com/pwn0rz/e34ab9f6e46956621a9d4f98cf222320| 
| 20210203 | Spoofing and Attacking With Skype | https://blog.thecybersecuritytutor.com/spoofing-and-attacking-with-skype/| 
| 20210203 | 利用开源工具 Falco 实现对 MITRE ATT&CK 的检测 | https://sysdig.com/blog/mitre-defense-evasion-falco/| 
| 20210203 | INFILTRATE20 会议研究员 0xdea 关于 Solaris 操作系统多个漏洞研究的分享 | https://github.com/0xdea/raptor_infiltrate20| 
| 20210203 | Injecting Rogue DNS Records Using DHCP | https://www.trustedsec.com/blog/injecting-rogue-dns-records-using-dhcp/?utm_campaign=Blog%20Posts&utm_content=153064925&utm_medium=social&utm_source=twitter&hss_channel=tw-403811306| 
| 20210203 | ESET 对针对 Linux 系操作系统恶意软件 Kobalos 的分析报告 | https://www.welivesecurity.com/wp-content/uploads/2021/01/ESET_Kobalos.pdf| 
| 20210203 | Project Zero Maddie Stone 对 2020 年野外漏洞利用情况的综述 | https://github.com/maddiestone/ConPresentations/blob/master/Enigma2021.StateOf0day.pdf| 
| 20210203 | NCC Group 2020 年度研究报告，可以看到多个不同方向的研究成果 | https://research.nccgroup.com/2021/01/31/2020-annual-research-report/amp/| 
| 20210203 | 容器与云的碰撞——一次对MinIO的测试 | https://www.leavesongs.com/PENETRATION/the-collision-of-containers-and-the-cloud-pentesting-a-MinIO.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210203T13:24:34Z | CVE-2021-3156 | Null | https://github.com/blasty/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210203T12:53:53Z | CVE-2021-3345 | Null | https://github.com/MLGRadish/CVE-2021-3345 | _gcry_md_block_write in cipher/hash-common.c in Libgcrypt version 1.9.0 has a heap-based buffer overflow when the digest final function sets a large count value. It is recommended to upgrade to 1.9.1 or later.| 
| 20210203T11:27:52Z | CVE-2021-3156 | Null | https://github.com/leterts/CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210203T10:58:41Z | CVE-2021-3156 | CVE-2021-3156 Vagrant Lab | https://github.com/dinhbaouit/CVE-2021-3156 | | 
| 20210203T09:38:18Z | cve-2020-17523 | shiro-cve-2020-17523 漏洞分析 | https://github.com/jweny/shiro-cve-2020-17523 | 未查询到CVE信息| 
| 20210203T09:04:14Z | CVE-2021-3156 | Null | https://github.com/cdeletre/Serpentiel-CVE-2021-3156 | Sudo before 1.9.5p2 has a Heap-based Buffer Overflow, allowing privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210203T09:00:04Z | cve-2021-25646 | Apache Druid 远程代码执行;检测脚本 | https://github.com/yaunsky/cve-2021-25646 | 未查询到CVE信息| 
| 20210203T06:53:27Z | CVE-2021-25646 | Null | https://github.com/lp008/CVE-2021-25646 | | 
| 20210203T06:15:15Z | CVE-2020-27194 | my exp for CVE-2020-27194, tested on linux kernel 5.8.14. | https://github.com/xmzyshypnc/CVE-2020-27194 | | 
| 20210203T06:01:40Z | CVE-2020-1938 | Modified version of auxiliary/admin/http/tomcat_ghostcat, it can  Read any file | https://github.com/YU5Z8X2CvH1fv4ep/CVE-2020-1938-MSF-MODULE | When using the Apache JServ Protocol (AJP), care must be taken when trusting incoming connections to Apache Tomcat. Tomcat treats AJP connections as having higher trust than, for example, a similar HTTP connection. If such connections are available to an attacker, they can be exploited in ways that may be surprising. In Apache Tomcat 9.0.0.M1 to 9.0.0.30, 8.5.0 to 8.5.50 and 7.0.0 to 7.0.99, Tomcat shipped with an AJP Connector enabled by default that listened on all configured IP addresses. It was expected (and recommended in the security guide) that this Connector would be disabled if not required. This vulnerability report identified a mechanism that allowed: - returning arbitrary files from anywhere in the web application - processing any file in the web application as a JSP Further, if the web application allowed file upload and stored those files within the web application (or the attacker was able to control the content of the web application by some other means) then this, along with the ability to process a file as a JSP, made remote code execution possible. It is important to note that mitigation is only required if an AJP port is accessible to untrusted users. Users wishing to take a defence-in-depth approach and block the vector that permits returning arbitrary files and execution as JSP may upgrade to Apache Tomcat 9.0.31, 8.5.51 or 7.0.100 or later. A number of changes were made to the default AJP Connector configuration in 9.0.31 to harden the default configuration. It is likely that users upgrading to 9.0.31, 8.5.51 or 7.0.100 or later will need to make small changes to their configurations.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210203T13:01:59Z | The compiler inputs a PDDL benchmark of the Carpark planning problem and converts it to an equivalent C code which is used for solving the planning problem by program verification tools such as KLEE/TracerX. | https://github.com/daneshvar-amrollahi/Carpark-PDDL2C | 0 | 0| 
| 20210203T11:34:32Z | Null | https://github.com/alsoknownaszac/kleekit | 0 | 0| 
| 20210203T11:08:33Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 212 | 34| 
| 20210203T10:49:07Z | A personnal UI library made as an excuse to have a published UI package | https://github.com/Liinkiing/klee | 4 | 1| 
| 20210203T09:12:07Z | Null | https://github.com/fontworks-fonts/Klee | 349 | 9| 
| 20210203T07:33:42Z | Null | https://github.com/jiseongg/klee_experiment | 0 | 0| 
| 20210203T02:41:02Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1623 | 482| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210203T13:25:04Z | PatrowlHears - Vulnerability Intelligence Center / Exploits | https://github.com/Patrowl/PatrowlHears | 42 | 8| 
| 20210203T13:14:48Z | Null | https://github.com/r4j0x00/exploits | 354 | 88| 
| 20210203T13:10:12Z | Exploiter is a ripoff for metasploit but have all vulnerbility on exploit-db | https://github.com/Parrot12345-HTB/Exploiter | 0 | 0| 
| 20210203T13:02:51Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 7 | 3| 
| 20210203T12:49:57Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 7 | 4| 
| 20210203T12:43:43Z | Launcher base for your gtav mod menu/exploit/cheat/hack. Version 2.0 (Different Layout) | https://github.com/0xFXDE/DemoZeroUIV2 | 0 | 0| 
| 20210203T12:06:23Z | A newly developed minecraft cheat as of 02/2021, tested and made for 2b2t and other anarchy servers, compatible with the most well known servers such as hypixel, signet is a combat and movement based client designed to avoid detection from all anticheats such as watchdogs, GWEN and much more! It also includes a new exploit for boat and ELYTRA fly, as of 02/2021, and will be continuing to be updated regularly on the GitHub repo. | https://github.com/Floppyzee3/SignetMC | 0 | 0| 
| 20210203T11:57:07Z | This bash script will help you to hack remote hosts  | https://github.com/FabioDefilippo/linuxallremote | 4 | 1| 
| 20210203T11:51:54Z | Running this HTML File locally will corrupt the File System and Trigger a Blue Screen after three seconds | https://github.com/websecnl/NTFS-Corruption-and-BSOD-Exploit | 0 | 0| 
| 20210203T11:40:28Z | Experimental CSGO external game exploit. | https://github.com/jamesmoriarty/gohack | 20 | 3| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210203T13:10:07Z | Null | https://github.com/angelo1104/backdoor-client | 0 | 0| 
| 20210203T12:46:18Z | Null | https://github.com/angelo1104/backdoor-server | 0 | 0| 
| 20210203T12:32:04Z | This is a python program backdoor embeded with a game for reverse connection from the victim to understand the use visit our youtube channel STRANGE LEARNINGS  | https://github.com/EnriqueStrange/Advanced-Backdoor | 0 | 0| 
| 20210203T11:12:30Z | Hacking tools pack & backdoors generator. | https://github.com/AdrMXR/KitHack | 336 | 57| 
| 20210203T10:13:02Z | Null | https://github.com/k0rup710n/Python-Backdoor | 0 | 0| 
| 20210203T08:19:25Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 36 | 8| 
| 20210203T03:24:54Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 162 | 23| 
| 20210203T02:06:13Z | Tool to find potential backdoor/security holes in your endpoint | https://github.com/subasgit/backdoorfinder | 1 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210203T13:25:37Z | A curated list on research blending deeplearning and fuzzing | https://github.com/thebabush/awesome-deep-fuzzing | 6 | 1| 
| 20210203T13:02:38Z | final project for CS50 2020 | https://github.com/leztien/fuzzy_matching_project | 0 | 0| 
| 20210203T11:53:35Z | Program berjudul %Pengelompokan Usia pada Sistem Fuzzy% | https://github.com/arizkinewbie/Contoh-Aturan-Fuzzy | 0 | 0| 
| 20210203T11:42:24Z | Null | https://github.com/kinzhong/fuzzer-performance-visualiser | 0 | 0| 
| 20210203T11:32:13Z | Null | https://github.com/kinzhong/fuzzing-automation-tools | 0 | 0| 
| 20210203T11:31:58Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 5837 | 1178| 
| 20210203T10:38:26Z | Null | https://github.com/Tilsonar/Fuzzy-Clustering-Topic-Modeling | 0 | 0| 
| 20210203T09:54:02Z | A curated list of awesome directed fuzzing research papers | https://github.com/strongcourage/awesome-directed-fuzzing | 71 | 14| 
| 20210203T09:39:43Z | A fuzzer for SMT solvers | https://github.com/testsmt/yinyang | 74 | 6| 
| 20210203T09:39:40Z | AI task 2 : creating fuzzy algorithm | https://github.com/dendyandra22/FuzzyAlgorithm | 0 | 0| 



# 日更新程序
