<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:8957e5&height=180&section=header&text=Alvin%20Thomas&fontSize=48&fontColor=ffffff&fontAlignY=36&desc=red%20team%20curiosity%20%C2%B7%20blue%20team%20discipline&descAlignY=58&descSize=18&animation=fadeIn" alt="Alvin Thomas" width="100%" />

<a href="https://github.com/blackdalc7"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1100&color=58A6FF&center=true&vCenter=true&width=620&lines=20+%C2%B7+Kerala%2C+India+%F0%9F%8C%B4+%C2%B7+Cyber+Security+%40+Monash;Breaking+things+since+I+was+12;Red+team+by+curiosity%2C+blue+team+by+choice;If+it+has+logs%2C+I+want+to+read+them;Building+the+SOC+I+want+to+work+in" alt="Typing intro" /></a>

<p>
<img src="https://img.shields.io/badge/Kerala%20%E2%86%92%20Melbourne-0d1117?style=for-the-badge&logo=googlemaps&logoColor=3fb950" alt="Kerala to Melbourne" />
<img src="https://img.shields.io/badge/Hacking%20since-age%2012-0d1117?style=for-the-badge&logo=hackthebox&logoColor=9fef00" alt="Hacking since age 12" />
<img src="https://img.shields.io/badge/Team-Purple-0d1117?style=for-the-badge&logo=letsencrypt&logoColor=d2a8ff" alt="Team purple" />
<img src="https://komarev.com/ghpvc/?username=blackdalc7&color=1f6feb&style=for-the-badge&label=VISITORS" alt="Visitors" />
</p>

<img src="assets/terminal.svg" alt="whoami: Alvin Thomas, 20, Kerala India, Cyber Security at Monash, hacking since 12" width="760" />

</div>

---

## 👋 Hey, I'm Alvin

I'm a 20-year-old cyber security student from **Kerala, India**, now studying at **Monash University**. I got hooked on computers as a kid and started poking at security when I was **12**: taking apart how things work, breaking them in my own lab, and then figuring out how someone would have caught me.

That's still how I learn. I think like an attacker so I can build like a defender, and most of what's on this profile is me doing exactly that: attacking my own lab, writing the detections that should have fired, and automating the response.

> *"Every alert I write starts with an attack I ran first."*

---

## 🎮 Pick a side

Click to open each one.

<details>
<summary><b>🔴 Red team: how I break things</b></summary>
<br/>

- 🧨 Adversary emulation with **Atomic Red Team**, mapped to **MITRE ATT&CK**, only ever inside my isolated lab
- 🕸️ Attack-path thinking: which single fix cuts off the most of the network? (see my blast-radius scanner)
- 🔎 Recon and enumeration with **Nmap**, then turning raw scan data into a ranked list of what actually matters
- 🧪 Scoring my own attacks: detected, prevented, telemetry only, or missed

</details>

<details>
<summary><b>🔵 Blue team: how I catch things</b></summary>
<br/>

- 📡 Real-time SIEM pipelines: syslog in, ECS / OCSF out, streaming detections for brute force and password spraying
- 📜 **Sigma** rules compiled to SQL and run over a Parquet + DuckDB data lake
- 🖥️ Windows EDR from kernel **ETW**: live process trees, Office-spawns-shell, canary files as ransomware tripwires
- 🤝 SOAR with a human in the loop: no host gets isolated until an analyst clicks *Approve*
- 🧾 DFIR: Velociraptor + Hayabusa into one hashed evidence timeline

</details>

<details>
<summary><b>🟣 Purple team: where the two meet</b></summary>
<br/>

```mermaid
flowchart LR
    A[🔴 Emulate an attack] --> B[📡 Detect it]
    B --> C[🧩 Correlate + triage]
    C --> D{🙋 Analyst approves?}
    D -- yes --> E[🛑 Contain]
    E --> F[🧾 Collect evidence]
    F --> G[📊 Score what we missed]
    G --> A
```

That loop is my whole portfolio, built end to end in [Cyber-personal-portfolio](https://github.com/blackdalc7/Cyber-personal-portfolio).

</details>

---

## 🚀 Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🛰️ [Cyber-personal-portfolio](https://github.com/blackdalc7/Cyber-personal-portfolio)

Ten security tools joined into one loop, with **Watchfloor** as the console that ties them together. SIEM, SOAR, EDR, vuln scanning, Sigma coverage, attack emulation, DFIR and an AI analyst.

**[▶ Live replay demo](https://blackdalc7.github.io/Cyber-personal-portfolio/)**

`Python` `PowerShell` `C#` `React` `DuckDB` `Docker`

</td>
<td width="50%" valign="top">

### 🔍 [DriftWatch-Project](https://github.com/blackdalc7/DriftWatch-Project)

Continuous security validation for a Windows lab. A Go agent runs signed, harmless tests, results get scored against Elastic, and configuration drift is flagged before it becomes a gap.

`Go` `Python` `React` `Elastic` `mTLS`

</td>
</tr>
</table>

<!-- SMALL-PROJECTS:START -->
<!-- SMALL-PROJECTS:END -->

---

## 🧰 My toolkit

<div align="center">

<img src="https://skillicons.dev/icons?i=python,go,c,cpp,rust,bash,powershell,js,ts,react&perline=10" alt="Languages" /><br/>
<img src="https://skillicons.dev/icons?i=linux,kali,ubuntu,docker,kubernetes,postgres,sqlite,git,githubactions,vscode&perline=10" alt="Platforms and tools" />

<br/>

![Sigma](https://img.shields.io/badge/Sigma-1f6feb?style=flat-square) ![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-c0392b?style=flat-square) ![Elastic](https://img.shields.io/badge/Elastic-005571?style=flat-square&logo=elastic) ![Velociraptor](https://img.shields.io/badge/Velociraptor-8957e5?style=flat-square) ![Nmap](https://img.shields.io/badge/Nmap-0e4c92?style=flat-square) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) ![OCSF](https://img.shields.io/badge/OCSF-2ea043?style=flat-square) ![Atomic Red Team](https://img.shields.io/badge/Atomic%20Red%20Team-da3633?style=flat-square)

</div>

---

## 🗺️ My journey so far

<details>
<summary><b>Open the timeline</b></summary>
<br/>

| When | What happened |
|---|---|
| 👶 **Kid** | Took apart every computer I was allowed near (and a few I wasn't) |
| 🔐 **Age 12** | First taste of security: how do people get in, and how would you know? |
| 🐧 **Teens** | Linux, scripting, CTF-style puzzles, building and breaking home labs |
| ✈️ **Kerala → Melbourne** | Started Cyber Security at Monash University |
| 🛰️ **Now** | Building a full detection-and-response platform from scratch, one tool at a time |
| 🎯 **Next** | A SOC / threat response role where I get to automate the boring parts |

</details>

---

## 📊 Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=blackdalc7&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=d2a8ff&include_all_commits=true" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=blackdalc7&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=blackdalc7&theme=tokyonight&hide_border=true&background=0d1117&ring=8957e5&fire=ff7b72&currStreakLabel=58a6ff" alt="Streak" />

<img src="https://raw.githubusercontent.com/blackdalc7/blackdalc7/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake" width="100%" />

</div>

---

## 💬 Ask me about

`detection engineering` · `Sigma rules` · `building home labs` · `Windows internals` · `SOAR automation` · `CTFs` · `why logs are beautiful`

<details>
<summary><b>🥚 Easter egg</b></summary>
<br/>

```bash
$ sudo make me-a-sandwich
[sudo] password for alvin: ********
Detection: T1548 (Abuse Elevation Control Mechanism)
Alert raised. Analyst notified. Sandwich quarantined. 🥪🔒
```

</details>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8957e5,50:1f6feb,100:0d1117&height=110&section=footer" alt="" width="100%" />

**Thanks for stopping by. Stay curious, stay patched.** 🛡️

</div>
