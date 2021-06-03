# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210603 | BFSLabs 对 Windows Hyper-V vmswitch.sys CVE-2021-28476 漏洞的简要分析 | https://labs.bluefrostsecurity.de/advisories/bfs-sa-2021-001/| 
| 20210603 | An Introduction to Manual Active Directory Querying with Dsquery and Ldapsearch | https://posts.specterops.io/an-introduction-to-manual-active-directory-querying-with-dsquery-and-ldapsearch-84943c13d7eb?gi=6f0b84b5f8eb| 
| 20210603 | 有研究员公开了他收集的各个版本的苹果 SEP 处理器 BootROM | http://securerom.fun| 
| 20210603 | 恶意软件分析与溯源过程中如何收集家族样本的技术分析，来自 SSTIC 会议 | https://www.sstic.org/2021/presentation/Taking_Advantage_of_PE_Metadata_or_How_To_Complete_your_Favorite_Threat_Actor_Sample_Collection/| 
| 20210603 | SSTIC 会议上 Google 研究员关于近期他们开源的 Hyper-V Fuzzer - Hyntrospect 的演讲 | https://www.sstic.org/2021/presentation/hyntrospect_a_fuzzer_for_hyper-v_devices/| 
| 20210603 | James Forshaw 对 SeRelabelPrivilege 的介绍 | https://www.tiraniddo.dev/2021/06/the-much-misunderstood.html| 
| 20210603 | Microsoft SharePoint Server CVE-2021-31181 RCE 漏洞的分析 | https://www.thezdi.com/blog/2021/6/1/cve-2021-31181-microsoft-sharepoint-webpart-interpretation-conflict-remote-code-execution-vulnerability| 
| 20210603 | Apple Safari JSC 脚本引擎 WebAssembly CVE-2021-30734 RCE 漏洞的分析 | https://blog.ret2.io/2021/06/02/pwn2own-2021-jsc-exploit/| 
| 20210603 | 微软关于 Edge 浏览器 UI 安全的设计与安全对抗实践 | https://microsoftedge.github.io/edgevr/posts/ui-security-thinking-outside-the-viewport/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210603T12:45:57Z | CVE-2021-27965 | CVE-2021-27965 win x64 local privilege escalation exploit to nt authority/system by spawning system cmd | https://github.com/mathisvickie/CVE-2021-27965 | The MsIo64.sys driver before 1.1.19.1016 in MSI Dragon Center before 2.0.98.0 has a buffer overflow that allows privilege escalation via a crafted 0x80102040, 0x80102044, 0x80102050, or 0x80102054 IOCTL request.| 
| 20210603T12:28:37Z | cve-2021-21985 | cve-2021-21985 exploit | https://github.com/xnianq/cve-2021-21985_exp | | 
| 20210603T11:37:30Z | CVE-2020-7471 | PoC for the SQL injection vulnerability in PostgreSQL with Django, found in Django 1.11 before 1.11.28, 2.2 before 2.2.10, and 3.0 before 3.0.3 | https://github.com/huzaifakhan771/CVE-2020-7471-Django | Django 1.11 before 1.11.28, 2.2 before 2.2.10, and 3.0 before 3.0.3 allows SQL Injection if untrusted data is used as a StringAgg delimiter (e.g., in Django applications that offer downloads of data as a series of rows with a user-specified column delimiter). By passing a suitably crafted delimiter to a contrib.postgres.aggregates.StringAgg instance, it was possible to break escaping and inject malicious SQL.| 
| 20210603T11:07:56Z | CVE-2021-21985 | CVE-2021-21985 vmware vcenter 远程代码执行 EXP | https://github.com/r0ckysec/CVE-2021-21985 | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210603T10:19:10Z | CVE-2021-21985 | Null | https://github.com/alt3kx/CVE-2021-21985_PoC | The vSphere Client (HTML5) contains a remote code execution vulnerability due to lack of input validation in the Virtual SAN Health Check plug-in which is enabled by default in vCenter Server. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server.| 
| 20210603T09:50:31Z | CVE-2020-24949 | PHPFusion 9.03.50 - Remote Code Execution | https://github.com/r90tpass/CVE-2020-24949 | Privilege escalation in PHP-Fusion 9.03.50 downloads/downloads.php allows an authenticated user (not admin) to send a crafted request to the server and perform remote command execution (RCE).| 
| 20210603T01:16:00Z | CVE-2020-36326 | PoC for exploiting CVE-2020-36326 | https://github.com/JamesGeee/CVE-2020-36326 | | 
| 20210603T00:08:19Z | CVE-2021-29208 | PoC for exploiting CVE-2021-29208 | https://github.com/JamesGeee/CVE-2021-29208 | A remote dom xss, crlf injection vulnerability was discovered in HPE Integrated Lights-Out 4 (iLO 4); HPE SimpliVity 380 Gen9; HPE Integrated Lights-Out 5 (iLO 5) for HPE Gen10 Servers; HPE SimpliVity 380 Gen10; HPE SimpliVity 2600; HPE SimpliVity 380 Gen10 G; HPE SimpliVity 325; HPE SimpliVity 380 Gen10 H version(s): Prior to version 2.78.| 
| 20210603T00:08:14Z | CVE-2020-22023 | PoC for exploiting CVE-2020-22023 | https://github.com/JamesGeee/CVE-2020-22023 | A heap-based Buffer Overflow vulnerabililty exists in FFmpeg 4.2 in filter_frame at libavfilter/vf_bitplanenoise.c, which might lead to memory corruption and other potential consequences.| 
| 20210603T00:08:11Z | CVE-2020-22022 | PoC for exploiting CVE-2020-22022 | https://github.com/JamesGeee/CVE-2020-22022 | A heap-based Buffer Overflow vulnerability exists in FFmpeg 4.2 in filter_frame at libavfilter/vf_fieldorder.c, which might lead to memory corruption and other potential consequences.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T08:24:15Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1709 | 494| 
| 20210603T01:39:42Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 644 | 15| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T12:45:57Z | CVE-2021-27965 win x64 local privilege escalation exploit to nt authority/system by spawning system cmd | https://github.com/mathisvickie/CVE-2021-27965 | 0 | 0| 
| 20210603T12:45:40Z | Simple Exploit | https://github.com/PlinBlin/Simple-Exploit | 1 | 0| 
| 20210603T12:35:14Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9520 | 1541| 
| 20210603T12:28:37Z | cve-2021-21985 exploit | https://github.com/xnianq/cve-2021-21985_exp | 0 | 0| 
| 20210603T12:24:45Z | Null | https://github.com/MoryokaV/Activity-Exploit | 0 | 0| 
| 20210603T12:23:22Z | Null | https://github.com/TheCrazzXz/Exploits-Lab | 0 | 0| 
| 20210603T12:07:44Z | RCE Exploit for Gitlab < 13.9.4 | https://github.com/CsEnox/GitLab-Wiki-RCE | 3 | 1| 
| 20210603T12:02:50Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 24 | 11| 
| 20210603T11:49:14Z | A post exploitation tool based on a web application, focusing on bypassing endpoint protection and application whitelisting | https://github.com/AdrianVollmer/PowerHub | 433 | 76| 
| 20210603T11:39:22Z | A Framework meant for the exploitation of iOS devices. | https://github.com/0x1CA3/iPwn | 11 | 1| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T12:24:29Z | Null | https://github.com/ShannonAI/backdoor_nlg | 0 | 0| 
| 20210603T07:53:27Z | This will remove the hostflow java assist backdoor | https://github.com/abhiram555/JavaAssistBackdoorRemover | 0 | 1| 
| 20210603T07:19:46Z | Null | https://github.com/huynhquynh-dev/backdoor_py | 0 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210603T12:21:58Z | This project is used to demonstrate the use of RxJava with RxAndroid in Android Development. We have demonstrated the use of various operators namely creational, filter, transformation operators | https://github.com/devrath/fuzzy-reactive-kotlin | 0 | 0| 
| 20210603T12:15:13Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 8 | 5| 
| 20210603T12:13:32Z | Null | https://github.com/Devashishdas12345/fuzzy-guide | 0 | 0| 
| 20210603T12:10:13Z | Null | https://github.com/realsarm/my-symbolic-fuzzer | 0 | 0| 
| 20210603T12:03:47Z | Null | https://github.com/AfrizalSY/Fuzzy_Logic2 | 0 | 0| 
| 20210603T11:39:35Z | Null | https://github.com/Koncyeya/fuzzy-meme | 0 | 0| 
| 20210603T11:00:27Z | Null | https://github.com/fky8/fuzzy-octo-sniffle | 0 | 0| 
| 20210603T10:44:49Z | The Official Fuzzy Britches Repository. | https://github.com/ThePapaw/fuzzybritches | 0 | 0| 
| 20210603T10:13:47Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6347 | 1288| 
| 20210603T10:01:57Z | Fuzzinator Random Testing Framework | https://github.com/renatahodovan/fuzzinator | 173 | 38| 



# 日更新程序
