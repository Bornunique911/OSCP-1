```bash
████████╗██╗  ██╗███████╗     ██╗  ██╗   ██╗███╗   ██╗██╗  ██╗    ████████╗███████╗ █████╗ ███╗   ███╗
╚══██╔══╝██║  ██║██╔════╝     ██║  ╚██╗ ██╔╝████╗  ██║╚██╗██╔╝    ╚══██╔══╝██╔════╝██╔══██╗████╗ ████║
   ██║   ███████║█████╗       ██║   ╚████╔╝ ██╔██╗ ██║ ╚███╔╝        ██║   █████╗  ███████║██╔████╔██║
   ██║   ██╔══██║██╔══╝       ██║    ╚██╔╝  ██║╚██╗██║ ██╔██╗        ██║   ██╔══╝  ██╔══██║██║╚██╔╝██║
   ██║   ██║  ██║███████╗     ███████╗██║   ██║ ╚████║██╔╝ ██╗       ██║   ███████╗██║  ██║██║ ╚═╝ ██║
   ╚═╝   ╚═╝  ╚═╝╚══════╝     ╚══════╝╚═╝   ╚═╝  ╚═══╝╚═╝  ╚═╝       ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝  
			       ---- lynxes just wanna have fun ----
```
# OSCP
This repo is curated by us with the objective to gather all the info that we'd found useful and interesting for the OSCP. The material inside this repo is also collected from other resources (websites, courses, blogs, git repos, etc).

## TOC
- [How to navigate the repo](#how-to-navigate-the-repo)
- [Official Offensive Security references](#official-offensive-security-references)
- [Blog](#blog)
- [Reddit](#reddit)
- [GitHub repos](#github-repos)
- [Webbing](#webbing)
- [Genereal useful resources](genereal-useful-resources)
- [Buffer Overflow](#buffer-overflow)
- [PrivEsc](#privesc)
- [Methodologies](#methodologies)
- [Automation scripts](#automation-scripts)
- [Cheat sheets](#cheat-sheets)
- [HackTheBox](#hackthebox)
- [VulnHub](#vulnhub)
- [Reporting](#reporting)

## How to navigate the repo
The repo is structured by this way:
```bash
|── CTF
│   └── OSPG
│       └── Easy
├── Courses
│   ├── LPE
│   └── PEH
├── Methodologies
├── README.md
└── troubleshooting.md
```
* **CTF**: here you can find for used platform the walkthroughs/notes
* **CTF/OSPG/EASY/HOST_X**: inside each OSPG host directory you can find how we organize our work
* **Course**: here we put some notes from courses we have done
* **Methodologies**: here you can find a .md file for each phase (recon/enum,privesc,postexlpoit,etc).
* **README**: where you can find a list of useful links
* **troubleshooting.md**: is a ledger to record all the tecnhical issues:solution we have found along the way

_Be aware: we use [Obsidian](https://obsidian.md/) as note taking application. This justify the directory structure that we are using at this moment. We think that the graph view provided by Obsidian is a nice way to have a visual view of the data we gather._
## Official Offensive Security References
- [Exam Guide](https://help.offensive-security.com/hc/en-us/articles/360040165632-OSCP-Exam-Guide)
- [Try Harder: From mantra to mindset](https://www.offensive-security.com/offsec/what-it-means-to-try-harder/)

## Blog
- [the-oscp-preperation-guide-2020](https://johnjhacking.com/blog/the-oscp-preperation-guide-2020/)
- Luke’s Ultimate OSCP Guide ([Part 1](https://medium.com/@hakluke/haklukes-ultimate-oscp-guide-part-1-is-oscp-for-you-b57cbcce7440), [Part 2](https://medium.com/@hakluke/haklukes-ultimate-oscp-guide-part-2-workflow-and-documentation-tips-9dd335204a48), [Part 3](https://medium.com/@hakluke/haklukes-ultimate-oscp-guide-part-3-practical-hacking-tips-and-tricks-c38486f5fc97))
- [TJNulls' preparation guide for PWK OSCP](https://www.netsecfocus.com/oscp/2019/03/29/The_Journey_to_Try_Harder-_TJNulls_Preparation_Guide_for_PWK_OSCP.html)
- [Abatchy: How to prepare for PWK/OSCP, a noob-friendly guide](https://www.abatchy.com/2017/03/how-to-prepare-for-pwkoscp-noob)
- [5 Tips for OSCP Prep](https://medium.com/bugbountywriteup/5-tips-for-oscp-prep-76001cdf4f4f)
- [BIG resource list](https://backdoorshell.gitbooks.io/oscp-useful-links/content/chapter1.html)
- [Tip for succes in PWK OSCP](https://www.mjkranch.com/2019/06/tips-for-success-in-pwk-oscp/)
- [My OSCP experience](https://refabr1k.github.io/learning/post-My-OSCP-Experience/)
- [Path to OSCP](https://localhost.exposed/path-to-oscp/)
- [Offensive Security Certified Professional – Lab and Exam Review](https://theslickgeek.com/oscp/)
- [My Fight for the OSCP](https://alphacybersecurity.tech/my-fight-for-the-oscp/)
- [Passing the OSCP while working full time](https://medium.com/@galolbardes/passing-the-oscp-while-working-full-time-29cb22d622e0)
- [Not your standard OSCP guide](https://blog.thehackingnomad.com/)

## Reddit
- [First Attempt ... Discouraged](https://www.reddit.com/r/oscp/comments/l7x5gq/first_attempt_discouraged/)
- [1 attempt 1 fail with 55 points](https://www.reddit.com/r/oscp/comments/l5sett/1_attempt_1_fail_with_55_points/)
- [Failed the OSCP - any tips for the next attempt?](https://www.reddit.com/r/netsecstudents/comments/5fwc1z/failed_the_oscp_any_tips_for_the_next_attempt/danovo5/)
- [Tips for passing the exam](https://www.reddit.com/r/oscp/comments/9j6q7d/tips_for_passing_the_exam/)
- [1st attempt, 80+ points. My experience and some unpopular opinions inside.](https://www.reddit.com/r/oscp/comments/la1kxe/1st_attempt_80_points_my_experience_and_some/)
- [First cert, first try, unconventional approach](https://www.reddit.com/r/oscp/comments/l41dxe/first_cert_first_attempt_an_unconventional/)
- [How Offensive Security Saved My Life - An OSCP Journey](https://www.reddit.com/r/oscp/comments/lc3937/how_offensive_security_saved_my_life_an_oscp/)
- [Unmotivated in ctfs](https://www.reddit.com/r/oscp/comments/l9dm4z/unmotivated_in_ctfs/)
- [Need help to prepare OSCP Checklist](https://www.reddit.com/r/oscp/comments/l95y1z/need_help_to_prepare_oscp_checklist/)
- [Preparing for 4th attempt](https://www.reddit.com/r/oscp/comments/l90f1q/preparing_for_4th_attempt/)
- [Second Attempt Failure](https://www.reddit.com/r/oscp/comments/la0xzk/second_attempt_failure/)
- [Access to machines for report writing?](https://www.reddit.com/r/oscp/comments/lbntjv/access_to_machines_for_report_writing/)

## GitHub repos
- [Awesome OSCP](https://github.com/The-Lynx-Team/awesome-oscp)
- [Enumeration wikis](https://github.com/theonlykernel/enumeration/wiki)
- [PimpMyKali](https://github.com/Dewalt-arch/pimpmykali)

## Webbing
- [Web vulnerabilities to gain access to the system](https://www.exploit-db.com/papers/13017)
- [Basic Shellshock Exploitation](https://blog.knapsy.com/blog/2014/10/07/basic-shellshock-exploitation/)

## Genereal useful resources
- [Explain shell](https://explainshell.com/)
- [Powershell basics](https://www.darkoperator.com/powershellbasics)
- [Pentest Tips and Tricks](https://jivoi.github.io/2015/07/01/pentest-tips-and-tricks/)
- [Big list with tips, tricks and cheat sheets](https://guif.re/)

## Buffer Overflow
- [Do Stack Bufferoverflow Good](https://github.com/justinsteven/dostackbufferoverflowgood)

## PrivEsc
- [Basic Linux Privilege Escalation](https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/)
- [Windows Privilege Escalation Fundamentals](http://www.fuzzysecurity.com/tutorials/16.html)

## Methodologies
- [CTF Series : Vulnerable Machines](https://bitvijays.github.io/LFC-VulnerableMachines.html)

## Automation scripts
- [Autorecon](https://github.com/Tib3rius/AutoRecon)
- [Onetwopunch](https://github.com/superkojiman/onetwopunch)

## Tool 
- [Parser Nmap](https://github.com/shifty0g/ultimate-nmap-parser)

## Cheat sheets
- [Reverse Shell Cheat Sheet](https://highon.coffee/blog/reverse-shell-cheat-sheet/)
- [OSCP-Prep-cheatsheet](https://github.com/evets007/OSCP-Prep-cheatsheet)
- [Immunity Debugger](https://psyl0ckediary.tumblr.com/post/148689728108/4-immunity-debugger-first-steps)

## HackTheBox
- [OSCP-Like HTB boxes](https://twitter.com/TJ_Null/status/1162419643283333120)

## VulnHub
- [OSCP-Like VulnHub boxes](https://www.abatchy.com/2017/02/oscp-like-vulnhub-vms.html) 

## Reporting
- [Reporting * ptestmethod.readthedocs.io](https://ptestmethod.readthedocs.io/en/latest/LFF-IPS-P5-Reporting.html)
