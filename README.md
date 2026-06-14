<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Rijwan%20Maulana&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=CyberSeurity%20Entusiath%20%7C%20Bug%20Bounty%20Hunter%20%7C%20Vibe%20Coding&descAlignY=60&descSize=18&descColor=a78bfa" width="100%" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=8B5CF6&center=true&vCenter=true&multiline=false&width=700&lines=Offensive+Security+%7C+Web+Exploitation;Bug+Bounty+Hunter+%7CPentester;Information+Systems+%40+UNPAM;Building+Secure%2C+Scalable+Software)](https://git.io/typing-svg)


![University](https://img.shields.io/badge/Universitas%20Pamulang-Information%20Systems%20S1-7C3AED?style=for-the-badge&logo=academia&logoColor=white)

[![Portfolio](https://img.shields.io/badge/Portfolio-siiwannn.dev-8B5CF6?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://github.com/Siiwannn)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-Hire%20Me-5B21B6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:xxrzwnm@gmail.com)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Siiwannn&color=7c3aed&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/Siiwannn?color=8B5CF6&style=for-the-badge&logo=github&label=FOLLOWERS)
![Stars](https://img.shields.io/github/stars/Siiwannn?color=5B21B6&style=for-the-badge&logo=github&label=TOTAL+STARS)

</div>

---

<div align="center">

## ◈ About Me

</div>

```yaml
profile:
  name: "Rijwan Maulana (Iwan)"
  role: "Security Engineer & Full Stack Developer"
  focus: "Offensive Security · Web Exploitation · Bug Bounty"
  mindset: "Hacker-first. Build secure. Ship fast."
```

I am an Information Systems student and working professional building deep expertise at the intersection of **offensive security** and **full-stack software engineering**. My technical work spans web vulnerability research, automated reconnaissance tooling, and production-grade application development — with a deliberate focus on understanding systems deeply enough to break and rebuild them.

My bug bounty practice on **YesWeHack** focuses on real-world targets including GoFood/GoTo Financial and Mokapos, where I research OTP endpoint abuse, JWT manipulation, GraphQL parameter tampering, access control flaws, and business logic errors. I approach each target with an adversarial engineering mindset: enumerate the attack surface, map trust boundaries, and identify where assumptions break down.

On the engineering side, I build full-stack web applications using modern JavaScript frameworks, design systems from scratch, and write security automation tooling in Python. I am equally comfortable in a terminal hunting CVEs and in a code editor architecting a production deployment.

**Open To:** Bug Bounty Collaboration · Security Research · Junior Security Engineer Roles · Freelance Web Development · Open Source Contribution

---

<div align="center">

## ◈ Tech Stack

</div>

<div align="center">

**Languages**

[![My Skills](https://skillicons.dev/icons?i=python,js,bash,html,css,java,php&theme=dark&perline=8)](https://skillicons.dev)


**Cloud, DevOps & Tooling**

[![My Skills](https://skillicons.dev/icons?i=docker,linux,git,github,vscode,kali&theme=dark&perline=8)](https://skillicons.dev)

</div>

---


<div align="center">

## ◈ Featured Projects

</div>

<details>
<summary><b>⬡ XSS-Scanner-DualMode</b> — Automated Cross-Site Scripting Detection Engine</summary>

<br/>

An advanced Python-based XSS scanning tool engineered to operate in both reflected and DOM-based detection modes. Built to integrate into a bug bounty workflow, the scanner supports custom payload injection, response heuristics analysis, and output reporting in formats compatible with PoC submission standards.

<div align="center">

| Attribute | Details |
|:---|:---|
| **Stack** | Python 3, Requests, BeautifulSoup4, Argparse, Colorama |
| **Scale** | Single-target and bulk URL list support |
| **Performance** | Concurrent threading — configurable worker pool |
| **Detection** | Reflected XSS, DOM XSS, polyglot payloads, context-aware injection |
| **Security** | Passive-safe mode; no destructive payloads by default |
| **Impact** | Used in live bug bounty recon pipeline |
| **Repository** | [![GitHub](https://img.shields.io/badge/View%20Source-Siiwannn-8B5CF6?style=flat-square&logo=github)](https://github.com/Siiwannn) |

</div>

This tool was developed to close the gap between manual XSS testing and scalable automation. The dual-mode architecture separates reflected detection (server-response analysis) from DOM-based detection (in-browser execution context), allowing precise triage without false positive noise. Built on Parrot OS; compatible with any Linux environment.

<br/>

</details>


<details>
<summary><b>⬡ Secure Docker Deployment — SysAdmin/DevOps Architecture</b></summary>

<br/>

A 12-slide technical presentation and architecture reference covering production-grade Docker security practices: non-root container execution, multi-stage builds, network isolation policies, Secrets management, and a reference WordPress/MariaDB stack built to enterprise security standards.

<div align="center">

| Attribute | Details |
|:---|:---|
| **Stack** | Docker, Docker Compose, MariaDB, WordPress, GitHub Actions |
| **Scale** | Multi-container orchestration with defined network segments |
| **Security** | Non-root UID, read-only filesystems, secret injection via env |
| **DevOps** | CI/CD pipeline integration — container image scanning |
| **Audience** | Scholarship panel — IDN Academy Cybersecurity 2026 |
| **Impact** | Scholarship application technical deliverable |
| **Repository** | [![GitHub](https://img.shields.io/badge/View%20Source-Siiwannn-8B5CF6?style=flat-square&logo=github)](https://github.com/Siiwannn) |

</div>

This project emerged from a scholarship application requirement and became a reference architecture for secure container deployment. Every security control documented in the slides is implemented in the accompanying Compose file — this is a working stack, not a theoretical overview.

<br/>

</details>

---

<div align="center">

## ◈ Experience

</div>

**Independent Bug Bounty Researcher**
`YesWeHack Platform` · `2024 – Present`

Conducting independent vulnerability research against private and public bug bounty programs with a focus on web application security. Primary targets include fintech and super-app infrastructure in the Indonesian market.

- Researched OTP rate limiting, endpoint enumeration, and token replay vulnerabilities on GoFood/GoTo Financial
- Tested GraphQL APIs for introspection exposure, parameter-level IDOR, and unauthorized object access
- Investigated JWT implementation flaws including algorithm confusion and claim injection
- Performed access control testing across authenticated and unauthenticated API surfaces on Mokapos
- Documented a valid vulnerability disclosure recognized by Universitas Pamulang IT Bureau
- Navigating program scope, responsible disclosure timelines, and PoC documentation standards

![Python](https://img.shields.io/badge/Python-7C3AED?style=flat-square&logo=python&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-5B21B6?style=flat-square&logo=portswigger&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-8B5CF6?style=flat-square&logo=graphql&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-4C1D95?style=flat-square&logo=owasp&logoColor=white)
![Linux](https://img.shields.io/badge/Parrot%20OS-6D28D9?style=flat-square&logo=linux&logoColor=white)

---



## ◈ Achievements

| Recognition | Details |
|:---:|:---:|
| 🏴 Valid Bug Disclosure | Vulnerability recognized by Universitas Pamulang IT Bureau ||
| 🧪 PortSwigger Labs | Web Security Academy — active lab practitioner |
| 🐍 Published OSS Tooling | XSS-Scanner-DualMode on GitHub |

</div>

---

<div align="center">

## ◈ Certifications


**TryHackme**

[![OWASP](https://img.shields.io/badge/OWASP-Top%2010%20Practitioner-6D28D9?style=for-the-badge&logo=owasp&logoColor=white)](https://owasp.org)

**Academic**

[![UNPAM](https://img.shields.io/badge/UNPAM-Information%20Systems-4C1D95?style=for-the-badge&logo=academia&logoColor=white)](https://unpam.ac.id)

</div>

---

<div align="center">

## ◈ Coding Profiles


[![TryHackMe](https://img.shields.io/badge/TryHackMe-Active%20Learner-8B5CF6?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-Practitioner-6D28D9?style=for-the-badge&logo=hackthebox&logoColor=white)](https://hackthebox.com)

</div>

---

<div align="center">

## ◈ GitHub Analytics

<img src="https://github-readme-stats.vercel.app/api?username=Siiwannn&show_icons=true&theme=tokyonight&bg_color=0d0d1a&border_color=7c3aed&icon_color=8b5cf6&title_color=a78bfa&text_color=c4b5fd&hide_border=false&count_private=true&include_all_commits=true" height="170" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Siiwannn&layout=compact&theme=tokyonight&bg_color=0d0d1a&border_color=7c3aed&title_color=a78bfa&text_color=c4b5fd&hide_border=false&langs_count=8" height="170" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=Siiwannn&theme=tokyonight&background=0d0d1a&border=7c3aed&ring=8b5cf6&fire=a78bfa&currStreakLabel=c4b5fd&sideLabels=c4b5fd&currStreakNum=ffffff&sideNums=ffffff&dates=6d28d9" width="600" />

</div>

---

<div align="center">

## ◈ GitHub Trophies

<img src="https://github-profile-trophy.vercel.app/?username=Siiwannn&theme=darkhub&no-frame=false&no-bg=true&margin-w=6&column=7&title=Stars,Followers,Commits,Repositories,PullRequest,Issues,Reviews" width="100%" />

</div>

---

<div align="center">

## ◈ Contribution Activity

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Siiwannn&bg_color=0d0d1a&color=a78bfa&line=7c3aed&point=8b5cf6&area=true&area_color=4c1d95&hide_border=false&border_color=7c3aed&radius=6" width="100%" />

</div>

---

<div align="center">

## ◈ Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Siiwannn/Siiwannn/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Siiwannn/Siiwannn/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Siiwannn/Siiwannn/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

<div align="center">

## ◈ Connect

<br/>

[![Gmail](https://img.shields.io/badge/Gmail-rijwan%40example.com-7C3AED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:xxrzwnm@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rijwan%20Maulana-5B21B6?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-Siiwannn-8B5CF6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Siiwannn)
[![Portfolio](https://img.shields.io/badge/Portfolio-siiwannn.dev-6D28D9?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://github.com/Siiwannn)
</div>

---

<div align="center">

*"Security is not a product. It is a process of thinking like the adversary before they do."*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer&animation=fadeIn" width="100%" />

</div>
