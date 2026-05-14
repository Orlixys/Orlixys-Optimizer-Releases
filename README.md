<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:1a1a1a&height=180&section=header&animation=fadeIn" width="100%" alt="banner"/>

<br/>

<img src="assets/orlixys-logo.svg" width="130" alt="Orlixys Optimizer"/>

# Orlixys Optimizer

<i>Windows optimization &amp; maintenance — clean, fast, private.</i>

<br/>

<a href="https://github.com/Orlixys/Orlixys-Optimizer-Releases/releases/latest">
  <img src="https://img.shields.io/github/v/release/Orlixys/Orlixys-Optimizer-Releases?label=LATEST&style=for-the-badge&color=22C55E&labelColor=000000" alt="latest"/>
</a>
<a href="https://github.com/Orlixys/Orlixys-Optimizer-Releases/releases">
  <img src="https://img.shields.io/github/downloads/Orlixys/Orlixys-Optimizer-Releases/total?label=DOWNLOADS&style=for-the-badge&color=22C55E&labelColor=000000" alt="downloads"/>
</a>
<a href="#-requirements">
  <img src="https://img.shields.io/badge/WINDOWS-10_%7C_11-0078D6?style=for-the-badge&logo=windows&logoColor=white&labelColor=000000" alt="windows"/>
</a>
<a href="https://github.com/Orlixys/Orlixys-Optimizer-Source/blob/main/LICENSE">
  <img src="https://img.shields.io/badge/LICENSE-MIT-22C55E?style=for-the-badge&logo=opensourceinitiative&logoColor=white&labelColor=000000" alt="mit"/>
</a>

<br/><br/>

<a href="https://github.com/Orlixys/Orlixys-Optimizer-Releases/releases/latest/download/OrlixysOptimizer-win-Setup.exe">
  <img src="https://img.shields.io/badge/⬇_DOWNLOAD_FOR_WINDOWS-22C55E?style=for-the-badge&labelColor=000000&color=22C55E" height="48" alt="download"/>
</a>

<br/><br/>

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=14&duration=3800&pause=1000&color=A0A0A0&center=true&vCenter=true&width=720&lines=Native+.NET+9+%2B+WPF+%2B+WebView2.;Zero+telemetry%2C+zero+ads%2C+anonymous+hardware+ID+only.;Single-file+binary.+Auto-update+via+Velopack.;Free%2C+open-source%2C+MIT-licensed." alt="typing"/>

</div>

<br/>

---

<div align="center">

## ◆ &nbsp; WHAT IT IS

</div>

A native Windows application built for **performance, security and clarity**. It cleans, optimises and maintains your system the way it should be maintained — without installing dozens of heavy background processes, without telemetry, without ads, without selling you anything.

It does what tools like CCleaner used to do before they got loud, plus modern features for developers (cache cleanup for `node_modules`, `__pycache__`, build folders), and modern hardening for Windows 10 and 11.

<br/>

---

<div align="center">

## ◆ &nbsp; FEATURES

</div>

<table width="100%">
<tr>
<td width="50%" valign="top">

### 📊 &nbsp; Real-time Dashboard
Per-second snapshots of CPU, GPU, memory, network and storage. Visual, readable, no nonsense.

### ⚡ &nbsp; One-click Optimisation
Smart cleanup with automatic restore point. Cache, temp files, log files and standby memory — gone in seconds.

### 🎯 &nbsp; Focus Mode
Silences notifications and background processes while you work or game. Toggle on, toggle off.

### 🚀 &nbsp; Startup Manager
Shows everything `msconfig` hides. Disable noisy boot entries without breaking anything.

### 🛡️ &nbsp; Security Hardening
Disables telemetry and SMBv1, enables built-in Windows protections, configures sane defaults.

</td>
<td width="50%" valign="top">

### 🎨 &nbsp; Live GPU Colour
Adjust saturation, brightness and contrast on the fly. No driver restart, no GeForce Experience required.

### 🧹 &nbsp; Dev Folder Sweeper
Recursively cleans `node_modules`, `__pycache__`, `bin/`, `obj/`, `target/`, `.next/`, build artefacts. 47+ patterns.

### 🌐 &nbsp; Network Tuning
DNS, TCP, Winsock reset. Restore proper defaults when things break.

### 🤖 &nbsp; Automation
Scheduled tasks that run quietly in the background. Set once, forget about it.

### 🔄 &nbsp; Auto-update
Silent background updates via Velopack. New version on next launch.

</td>
</tr>
</table>

<br/>

---

<div align="center">

## ◆ &nbsp; INSTALL

</div>

<table width="100%">
<tr>
<td width="50%" valign="top" align="center">

### Installer (recommended)

<br/>

<a href="https://github.com/Orlixys/Orlixys-Optimizer-Releases/releases/latest/download/OrlixysOptimizer-win-Setup.exe">
  <img src="https://img.shields.io/badge/OrlixysOptimizer--win--Setup.exe-22C55E?style=for-the-badge&logo=windows&logoColor=white&labelColor=000000" alt="installer"/>
</a>

<br/>

Installs in seconds. Opens automatically.<br/>
**Auto-update on every launch.**<br/>
Per-user, no admin required to install.

</td>
<td width="50%" valign="top" align="center">

### Portable

<br/>

<a href="https://github.com/Orlixys/Orlixys-Optimizer-Releases/releases/latest">
  <img src="https://img.shields.io/badge/OrlixysOptimizer--win--Portable.zip-FFFFFF?style=for-the-badge&logo=windows&logoColor=black&labelColor=000000" alt="portable"/>
</a>

<br/>

Extract anywhere. Run the `.exe`.<br/>
**No auto-update in this mode.**<br/>
Good for USB drives, sandboxes, audits.

</td>
</tr>
</table>

<br/>

---

<div align="center">

## ◆ &nbsp; REQUIREMENTS

</div>

| | |
|---|---|
| **System** | Windows 10 (build 1809+) or Windows 11, 64-bit |
| **WebView2 Runtime** | Bundled with Windows 11. On Windows 10, [install the Evergreen bootstrap](https://developer.microsoft.com/microsoft-edge/webview2/) (free, ~120 KB) |
| **Admin rights** | Not required to install. Specific actions (services, hardening, restore points) request elevation through UAC only when used |
| **.NET runtime** | Not required separately — bundled inside the single-file binary |

<br/>

---

<div align="center">

## ◆ &nbsp; FAQ

</div>

<details>
<summary><b>Windows Defender or SmartScreen blocked the installer.</b></summary>

The warning shows up because the installer isn't yet signed with an Extended Validation certificate (EV certs cost roughly US$ 300/year and that's not a priority for a free project). It's a standard warning for new distributions, not an indicator that the software is dangerous.

To proceed:

1. Click **More info** in the SmartScreen warning
2. Click **Run anyway**

As more users install the app, the binary's reputation rises and the warning eventually goes away on its own.

</details>

<details>
<summary><b>Do I need to be admin to install?</b></summary>

No. The installer performs a per-user install in `%LocalAppData%\OrlixysOptimizer\` — no UAC prompt, no system-level changes. Specific app functions that require admin (services, restore points, hardening) request elevation on demand, only when you use them.

</details>

<details>
<summary><b>How do I uninstall?</b></summary>

**Settings → Apps → Installed apps → Orlixys Optimizer → Uninstall.** Everything is removed, including local configuration in `%LocalAppData%`.

</details>

<details>
<summary><b>Does the app collect my data?</b></summary>

No. No telemetry, no analytics, no calls to remote servers other than GitHub Releases (only to check for updates). All configuration stays in `%LocalAppData%\OrlixysOptimizer\` on your machine. The only identifier the app generates is an anonymous SHA-256 hardware fingerprint, kept locally — never transmitted.

</details>

<details>
<summary><b>Do some options require a reboot?</b></summary>

Yes — hardening changes, Windows scheduling tweaks and boot adjustments only take full effect after a reboot. The app always warns when that's the case.

</details>

<details>
<summary><b>Why is detailed sensor monitoring disabled by default?</b></summary>

Because it depends on a kernel driver (`WinRing0`) with a known vulnerability ([CVE-2020-14979](https://nvd.nist.gov/vuln/detail/CVE-2020-14979)). Windows Defender flags this driver in its protection history. If you need CPU temperatures and GPU clocks, you can enable it manually in **Settings → Advanced** — but it's an informed decision, not a default.

</details>

<details>
<summary><b>Is the source code available?</b></summary>

Yes. Orlixys Optimizer is open source under the MIT licence. Source repository: <a href="https://github.com/Orlixys/Orlixys-Optimizer-Source">github.com/Orlixys/Orlixys-Optimizer-Source</a>.

</details>

<br/>

---

<div align="center">

## ◆ &nbsp; SUPPORT

<br/>

<a href="https://github.com/Orlixys/Orlixys-Optimizer-Releases/issues/new">
  <img src="https://img.shields.io/badge/REPORT_AN_ISSUE-FFFFFF?style=for-the-badge&logo=github&logoColor=black&labelColor=FFFFFF" alt="issue"/>
</a>
<a href="https://github.com/Orlixys/Orlixys-Optimizer-Source">
  <img src="https://img.shields.io/badge/VIEW_SOURCE-000000?style=for-the-badge&logo=github&logoColor=white&labelColor=000000" alt="source"/>
</a>
<a href="mailto:support@orlixys.com">
  <img src="https://img.shields.io/badge/support%40orlixys.com-FFFFFF?style=for-the-badge&logo=maildotru&logoColor=black&labelColor=FFFFFF" alt="email"/>
</a>

<br/><br/>

<sub>When reporting an issue, include:</sub>
<br/>
<sub>Optimizer version (<b>Settings → About</b>) · Windows version (<code>winver</code>) · steps to reproduce · screenshot if relevant</sub>

</div>

<br/>

---

<div align="center">

## ◆ &nbsp; LEGAL

</div>

Orlixys Optimizer is distributed for free under the **[MIT licence](./LICENSE)**. You can read it, modify it, fork it, redistribute it — all of that is permitted by the licence.

A more detailed **[Terms of Use](./TERMS.md)** document supplements the licence with the warranty disclaimer, the limitation of liability, the rules on using the Orlixys brand in forks, and the update-channel policy.

By installing or using the binary you accept both documents. The MIT licence does **not** cover the Orlixys name or logo — those are proprietary marks. If you fork the project, please rebrand.

<sub>A system restore point is always recommended before applying large-scale optimisations (the app creates one automatically when you trigger one-click optimisation).</sub>

<br/>

---

<div align="center">

<br/>

<a href="https://github.com/Orlixys">
  <img src="https://img.shields.io/badge/An_Orlixys_Project-000000?style=for-the-badge&labelColor=000000" alt="orlixys"/>
</a>
<a href="https://github.com/sponsors/snwvlr">
  <img src="https://img.shields.io/badge/Sponsor_Development-E63946?style=for-the-badge&logo=github-sponsors&logoColor=white&labelColor=000000" alt="sponsor"/>
</a>

<br/><br/>

<sub><b>Orlixys</b> © 2026 · Made in stealth mode</sub>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a1a,100:000000&height=100&section=footer&animation=fadeIn" width="100%" alt="footer"/>

</div>
