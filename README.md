<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0078D4,100:8B5CF6&height=220&section=header&text=Tarun%20Raveesh&fontSize=64&fontColor=ffffff&fontAlignY=36&desc=Windows%20Internals%20%C2%B7%20Endpoint%20Engineering%20%C2%B7%20AI-Native%20Dev&descSize=18&descAlignY=58&animation=fadeIn" alt="Header" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/TarunRaveesh">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&width=680&lines=Software+Engineer+%40+Zoho+%2F+ManageEngine;Living+in+Win32,+WMI,+MSI+and+the+Registry;Kernel-mode+when+user-mode+is+not+enough;Shipping+with+AI+agents,+human+in+the+loop" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/tarun-raveesh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/TranceX07"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="mailto:tarunraveesh07@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Chennai,%20India-1F2937?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
</p>

---

## ⚡ whoami

```powershell
PS C:\> Get-CimInstance -Namespace root\dev -ClassName Engineer_Profile | Format-List

Name       : Tarun Raveesh
Role       : Software Engineer @ Zoho Corporation (ManageEngine)
Builds     : The Windows agent behind Endpoint Central / UEMS
Focus      : Endpoint management, software asset management, inventory scanning
Internals  : Win32, WMI/CIM, COM/DCOM, Windows Installer, Registry, Kernel mode
Workflow   : Agentic development with Claude Code, human approval at every gate
Off-hours  : Chess (~1800 blitz/rapid), singing
Status     : OK
```

## 🛠️ What I work on

- 🔭 Building the **ManageEngine Windows agent**: inventory scans and software asset management across large enterprise fleets.
- 🧠 Living close to the OS: **Win32, WMI/CIM, Windows Installer, the registry, Group Policy, AppLocker**, and kernel-mode code when user mode is not enough.
- 🤖 Running an **AI-native dev workflow**: custom agent skills, hooks, and hard human gates between RCA, plan, code, and review.
- 📓 Keeping a portable, AI-agnostic engineering notebook of every lesson worth keeping.

## 🕳️ Rabbit holes I've been down

| Topic | The short version |
|---|---|
| 🗂️ Add/Remove Programs | It is a display layer, not the source of truth for what is installed |
| 🔀 Packed ("squished") GUIDs | How Windows Installer stores ProductCodes and UpgradeCodes in the registry |
| 🧱 `Get-WmiObject` vs `Get-CimInstance` | And the CIM → WMI → COM/DCOM stack under both |
| 👥 `Win32_SystemUsers` vs `Win32_UserAccount` | Why two "user" classes disagree, and which one an agent should trust |
| 🔐 Headless per-user uninstalls | `LogonUser` → `LoadUserProfile` → `CreateProcessAsUser` |
| 🛡️ AppLocker / SRP at scale | Rollouts and debugging across enterprise endpoints |
| 🐛 Git Bash `fork()` failures | Root cause: Mandatory ASLR in Windows Exploit Protection |

## 🤖 How I build in the AI era

AI writes a lot of code now. My job is to own the judgment. Every change goes through explicit approval gates, and long sessions survive context compaction through an automatic handoff.

```mermaid
flowchart LR
    I([Issue]) --> R{{RCA}}
    R -->|I approve| P{{Plan}}
    P -->|I approve| C[Implement]
    C --> V{{Code review}}
    V -->|I approve| S([Ship])
    C -. context full .-> H[[Compaction hook]]
    H --> D[Handoff doc built from bookmarks]
    D -. resume .-> C

    classDef gate fill:#1e3a8a,stroke:#58a6ff,color:#ffffff
    classDef auto fill:#3b0764,stroke:#a78bfa,color:#ffffff
    class R,P,V gate
    class H,D auto
```

## 🧰 Toolbox

**Systems & Windows**

<p>
  <img src="https://skillicons.dev/icons?i=c,cpp,powershell,windows,visualstudio,py,java,bash,git,github,vscode&perline=11" alt="Systems skills" />
</p>

<p>
  <img src="https://img.shields.io/badge/Win32%20API-0078D4?style=for-the-badge" alt="Win32 API" />
  <img src="https://img.shields.io/badge/WMI%20%2F%20CIM-0078D4?style=for-the-badge" alt="WMI / CIM" />
  <img src="https://img.shields.io/badge/COM%20%2F%20DCOM-0078D4?style=for-the-badge" alt="COM / DCOM" />
  <img src="https://img.shields.io/badge/Windows%20Installer-0078D4?style=for-the-badge" alt="Windows Installer" />
  <img src="https://img.shields.io/badge/Registry-0078D4?style=for-the-badge" alt="Registry" />
  <img src="https://img.shields.io/badge/Kernel%20Mode-0078D4?style=for-the-badge" alt="Kernel Mode" />
  <img src="https://img.shields.io/badge/Group%20Policy-0078D4?style=for-the-badge" alt="Group Policy" />
  <img src="https://img.shields.io/badge/AppLocker-0078D4?style=for-the-badge" alt="AppLocker" />
</p>

**AI-native workflow**

<p>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/MCP-111827?style=for-the-badge" alt="MCP" />
  <img src="https://img.shields.io/badge/Agent%20Skills%20%26%20Hooks-6D28D9?style=for-the-badge" alt="Agent Skills and Hooks" />
  <img src="https://img.shields.io/badge/Human%20in%20the%20Loop-059669?style=for-the-badge" alt="Human in the loop" />
</p>

**Web & Web3** (where I started)

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nodejs,express,mongodb,mysql,postgres,bootstrap,solidity,latex,ps&perline=14" alt="Web skills" />
</p>

<!--
  Want project cards? Add one line per repo:
  <a href="https://github.com/TarunRaveesh/REPO"><img src="https://github-stats-extended.vercel.app/api/pin/?username=TarunRaveesh&repo=REPO&theme=tokyonight&hide_border=true" /></a>
-->

## 📊 GitHub Stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=TarunRaveesh&show_icons=true&hide_border=true&theme=tokyonight" />
    <img height="170" src="https://github-stats-extended.vercel.app/api?username=TarunRaveesh&show_icons=true&hide_border=true&theme=default" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=TarunRaveesh&layout=compact&hide_border=true&theme=tokyonight" />
    <img height="170" src="https://github-stats-extended.vercel.app/api/top-langs/?username=TarunRaveesh&layout=compact&hide_border=true&theme=default" alt="Top languages" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=TarunRaveesh&theme=dark&hide_border=true" />
    <img src="https://streak-stats.demolab.com?user=TarunRaveesh&theme=default&hide_border=true" alt="GitHub streak" />
  </picture>
</p>

<!-- Needs .github/workflows/snake.yml in this repo (run it once from the Actions tab) -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TarunRaveesh/TarunRaveesh/output/github-contribution-grid-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/TarunRaveesh/TarunRaveesh/output/github-contribution-grid-snake.svg" alt="Contribution snake" />
  </picture>
</p>

---

<p align="center">
  <b>Open to collaborating on Windows tooling, endpoint security, and agentic dev workflows.</b><br/>
  <sub>Say hi: <a href="mailto:tarunraveesh07@gmail.com">tarunraveesh07@gmail.com</a></sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0078D4,100:8B5CF6&height=120&section=footer" alt="Footer" width="100%" />
</p>
