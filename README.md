<p>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
  <img alt="Tarun Raveesh — software engineer working below the Windows API surface" src="./assets/header-light.svg" width="100%">
</picture>
</p>

<br>

I build the Windows agent behind **ManageEngine Endpoint Central** at Zoho: the code that scans, inventories, and manages software across enterprise fleets. Most of my time goes into Win32, WMI/CIM, Windows Installer, and the registry, with kernel mode when user mode is not enough.

<br>

<p>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/workflow-dark.svg">
  <img alt="How I ship: issue, root cause, plan, build, review, ship. Root cause, plan, and review need my sign-off." src="./assets/workflow-light.svg" width="100%">
</picture>
</p>

AI agents write many of my first drafts. The judgment stays mine: nothing passes root cause, plan, or review without my sign-off, and long sessions survive context compaction through an automatic handoff doc.

### Now

- Inventory scanning and software asset management for the ManageEngine agent
- Agent skills and hooks that keep long Claude Code sessions coherent
- A portable, AI-agnostic notebook of every lesson worth keeping

### Stack

`C` `C++` `PowerShell` `Python` `Win32` `WMI / CIM` `COM` `Windows Installer` `Registry` `Kernel mode` `Claude Code` `MCP`

<details>
<summary><b>Rabbit holes</b></summary>
<br>

- Why Add/Remove Programs is a display layer, not the source of truth
- Packed GUIDs, and how Windows Installer maps UpgradeCodes in the registry
- `Win32_SystemUsers` vs `Win32_UserAccount`, and which one an agent should trust
- Headless per-user uninstalls: `LogonUser` → `LoadUserProfile` → `CreateProcessAsUser`
- A Git Bash `fork()` failure, traced to Mandatory ASLR

</details>

<br>

[LinkedIn](https://linkedin.com/in/tarun-raveesh) &nbsp;·&nbsp; [X](https://x.com/TranceX07) &nbsp;·&nbsp; [Email](mailto:tarunraveesh07@gmail.com)

<sub>Off the keyboard: chess (~1800 blitz and rapid) and singing.</sub>
