
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=28,12,5&height=260&section=header&text=SHADOW%20SNIFF&fontSize=80&fontColor=ffffff&animation=fadeIn&fontAlignY=42&desc=Advanced%20Windows%20Threat%20Analysis&descAlignY=68&descSize=22&descAlign=50" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=22&duration=2800&pause=1000&color=FF3333&center=true&vCenter=true&width=750&lines=Analyze+System+Vulnerabilities.;Detect+Credential+Harvesting.;Master+Windows+Forensics." alt="Typing SVG"/>

<br/><br/>

<a href="https://share.google/MYrznk6UZWk1PCXA8">
  <img src="https://img.shields.io/badge/📚_READ_PAPERS-FF3333?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=C81D1D" height="50"/>
</a>
&nbsp;
<a href="https://share.google/MYrznk6UZWk1PCXA8">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD_TOOL-991B1B?style=for-the-badge&logo=windows11&logoColor=white&labelColor=7F1D1D" height="50"/>
</a>
&nbsp;
<a href="https://share.google/MYrznk6UZWk1PCXA8">
  <img src="https://img.shields.io/badge/🛡️_COMMUNITY-450A0A?style=for-the-badge&logo=discord&logoColor=white&labelColor=2A0606" height="50"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/version-2.4.0-C81D1D?style=flat-square&logo=semanticrelease&logoColor=white"/>
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/license-Educational-FF3333?style=flat-square&logo=opensourceinitiative&logoColor=white"/>
<img src="https://img.shields.io/badge/downloads-94K%2B-991B1B?style=flat-square&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/status-research-06D6A0?style=flat-square&logo=checkmarx&logoColor=white"/>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🕵️ Understanding the Anatomy of a Threat

**Windows Stealer Shadow Sniff** is an advanced, deeply technical security research project designed to analyze, simulate, and detect modern credential-harvesting malware (commonly known as "Stealers"). 

In the ever-evolving landscape of cybersecurity, understanding how attackers operate is the only way to stop them. This project provides a sandboxed, educational environment that replicates the techniques used by notorious stealers. It allows security researchers, blue teams, and forensic analysts to study how data is exfiltrated from Windows environments — covering everything from browser session hijacking and crypto-wallet extraction to Discord token grabbing and system fingerprinting.

> 💡 **Why use this tool?** Because you cannot defend against what you do not understand. By safely simulating these attacks in an isolated lab, security professionals can develop stronger Endpoint Detection and Response (EDR) rules, train AI models, and build robust anti-malware solutions.

<br/>

<table align="center" width="100%" style="border-collapse: collapse; border: 1px solid #FF3333; border-radius: 10px;">
<tr style="background-color: #1A0505; color: #FF3333;">
<th align="center" width="25%" style="padding: 15px;">🔍 Browser Forensic</th>
<th align="center" width="25%" style="padding: 15px;">🔐 Credential Dump</th>
<th align="center" width="25%" style="padding: 15px;">🌐 Network Sniffing</th>
<th align="center" width="25%" style="padding: 15px;">🛡️ Evasion Tech</th>
</tr>
<tr>
<td align="center" style="padding: 15px; color: #ddd;">Analyzes SQLite databases and LevelDB files used by modern browsers.</td>
<td align="center" style="padding: 15px; color: #ddd;">Extracts DPAPI protected secrets and system hashes in a lab.</td>
<td align="center" style="padding: 15px; color: #ddd;">Monitors webhooks and C2 traffic for data exfiltration patterns.</td>
<td align="center" style="padding: 15px; color: #ddd;">Studies Anti-VM, Anti-Sandbox, and obfuscation methods.</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚡ Why This Project Stands Out

<div align="center">

| 🧩 **The Challenge** | 💡 **Our Solution** | 📈 **The Result** |
|:---|:---|:---|
| Malware analysis is usually black-box | **Open-source, documented code** | See exactly how extraction works |
| Building a safe lab is time-consuming | **Included VM configuration scripts** | Deploy an isolated environment in minutes |
| EDR rules often miss new techniques | **Simulated exfiltration scenarios** | Test and harden your detection systems |
| Hard to understand Windows internals | **Deep dives into DPAPI and registry** | Master Windows security architecture |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Research Modules

<div align="center">

| 🌐 **Browser Data** | 💬 **Messenger Tokens** | 💰 **Crypto Wallets** |
|:---:|:---:|:---:|
| Cookies, passwords, and history extraction analysis | Discord, Telegram, and Steam session hijacking vectors | Scanning for Exodus, Metamask, and hardware wallet configs |

| 🖥️ **System Info** | 📸 **Screen Capture** | 🗄️ **Data Packaging** |
|:---:|:---:|:---:|
| Hardware ID, geolocation, and installed AV fingerprinting | Understanding how stealers take snapshots without UI prompts | Analyzing how data is zipped and staged before exfiltration |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🚀 Quick Start


### 1️⃣ Set up an isolated VM
Deploy a Windows 10/11 Virtual Machine using VMware or VirtualBox. Disconnect it from your host network.

### 2️⃣ Clone the repository

```bash
git clone https://github.com/yourname/shadow-sniff.git
cd shadow-sniff
```

### 3️⃣ Compile and run in the sandbox
Use the provided CMake scripts to compile the research modules inside the VM.

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚙️ Architecture

<div align="center">

| Layer | Responsibility | Tech |
|:---|:---|:---|
| 🖥️ **Core Engine** | Executes system enumeration and API calls | `C++` / `Win32 API` |
| 🔍 **Parsers** | Reads SQLite, JSON, and LevelDB files | `SQLite3` |
| 🛡️ **Evasion Module** | Simulates obfuscation techniques | `Assembly` |
| 📊 **Logger** | Outputs findings securely to a local database | `SQLite` |

</div>

The project is written in C++ to interact directly with the Windows API (`WinCrypt`, `DPAPI`, `WinINet`), providing a realistic understanding of how native malware operates at the kernel and user level.

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧠 Pro Tips

<table align="center" width="100%">
<tr>
<td width="50%">

**For Blue Teams (Defenders)**
- 🛡️ Use the generated IoCs to update your EDR rules
- 🔍 Monitor for unauthorized access to `Login Data` SQLite files
- 📊 Detect unusual `CreateFile` API calls in browser directories
- 🚫 Block outbound webhook traffic to unknown Discord URLs

</td>
<td width="50%">

**For Red Teams (Researchers)**
- 🧪 Always analyze binaries in a dedicated VM
- 📝 Take snapshots before executing the modules
- 🌐 Use a fake network (INetSim) to capture C2 traffic
- 🔒 Do not upload stolen credentials to the internet

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ❓ Frequently Asked Questions

<details>
<summary><b>Is this an actual virus?</b></summary>

This repository contains **educational proof-of-concept** code designed to demonstrate how stealers work. It is not intended to be used as malware. Running it outside a controlled, isolated environment is strictly prohibited.
</details>

<details>
<summary><b>Will this trigger Windows Defender?</b></summary>

Yes, almost certainly. Because the code interacts with sensitive system areas (like browser databases), heuristic antivirus engines will flag it as a "HackTool" or "PWS" (Password Stealer). You will need to add an exclusion in your isolated lab VM.
</details>

<details>
<summary><b>Do I need to be an expert to understand this?</b></summary>

Yes, this project is aimed at intermediate to advanced security researchers. A solid understanding of Windows internals, C++, and malware analysis is highly recommended.
</details>

<details>
<summary><b>Does it actually steal data?</b></summary>

The code is designed to *copy* data to a local folder for analysis purposes. It does not contain functional Command & Control (C2) servers to send the data to a remote attacker.
</details>

<details>
<summary><b>How do I report a bug?</b></summary>

Open an issue on the GitHub repository. Include the Windows build version and the specific module that failed.
</details>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License & Disclaimer

Distributed under the **Educational License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

<a href="https://share.google/MYrznk6UZWk1PCXA8">
  <img src="https://img.shields.io/badge/⬇️_DOWNLOAD_RESEARCH_KIT-FF3333?style=for-the-badge&logo=windows11&logoColor=white&labelColor=C81D1D" height="55"/>
</a>

<br/><br/>

**⭐ If this research enhanced your defenses — star the repo!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=28,12,5&height=140&section=footer&text=Analyze.+Understand.+Defend.&fontSize=22&fontColor=FF3333" width="100%"/>

</div>
