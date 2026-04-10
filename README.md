<div align="center">

# ⚡ WinOptimiser

**A lightweight PowerShell script to clean, tune, and take back control of your Windows PC.**

[![Version](https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge)](https://github.com/yourusername/WinOptimiser/releases)
[![PowerShell](https://img.shields.io/badge/PowerShell-5.1%2B-5391FE?style=for-the-badge&logo=powershell&logoColor=white)](https://microsoft.com/powershell)
[![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://microsoft.com)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](LICENSE)
[![Stars](https://img.shields.io/github/stars/yourusername/WinOptimiser?style=for-the-badge&color=yellow)](https://github.com/yourusername/WinOptimiser/stargazers)
[![Forks](https://img.shields.io/github/forks/yourusername/WinOptimiser?style=for-the-badge)](https://github.com/yourusername/WinOptimiser/network/members)
[![Issues](https://img.shields.io/github/issues/yourusername/WinOptimiser?style=for-the-badge&color=red)](https://github.com/yourusername/WinOptimiser/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)](https://github.com/yourusername/WinOptimiser/pulls)
[![Maintained](https://img.shields.io/badge/maintained-yes-success?style=for-the-badge)](https://github.com/yourusername/WinOptimiser)
[![Made with Love](https://img.shields.io/badge/made%20with-%E2%9D%A4-red?style=for-the-badge)](https://github.com/yourusername/WinOptimiser)

---

> *"Why pay for bloatware when a PowerShell script does it better?"*

[🚀 Get Started](#installation) · [📖 Documentation](#usage) · [🐛 Report a Bug](https://github.com/yourusername/WinOptimiser/issues) · [💡 Request a Feature](https://github.com/yourusername/WinOptimiser/issues)

</div>

---

## 📊 Stats

<div align="center">

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/WinOptimiser?style=flat-square)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/yourusername/WinOptimiser?style=flat-square)
![GitHub code size](https://img.shields.io/github/languages/code-size/yourusername/WinOptimiser?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/WinOptimiser?style=flat-square)
![GitHub contributors](https://img.shields.io/github/contributors/yourusername/WinOptimiser?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/yourusername/WinOptimiser?style=flat-square&color=5391FE)

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🗑️ Junk File Cleaner
Removes temporary files, browser cache, Windows update leftovers, and system clutter. Reclaim gigabytes in seconds.

</td>
<td width="50%">

### 🚀 Performance Booster
Flushes RAM, clears standby memory, and trims background process overhead for a noticeably snappier experience.

</td>
</tr>
<tr>
<td width="50%">

### 🔧 Startup Manager
Audits and disables unnecessary startup programs and services that silently drag down your boot time.

</td>
<td width="50%">

### 📋 Action Logger
Every change is logged to a timestamped file so you always have a full record of what was modified.

</td>
</tr>
</table>

---

## 📦 What It Does

| Module | What It Cleans | Typical Space Saved |
|---|---|---|
| 🗑️ Junk Cleaner | Temp files, browser cache, Windows update cache | 1–10 GB |
| 🧠 RAM Optimiser | Standby memory, background process bloat | Varies |
| ⚡ Startup Manager | Startup entries, delayed launch services | Faster boot |
| 📋 Logger | — | Full audit trail |

---

## 🖥️ Requirements

| Requirement | Details |
|---|---|
| OS | Windows 10 or Windows 11 |
| PowerShell | 5.1 or later |
| Privileges | Administrator |
| Dependencies | None — fully standalone |

---

## 🛠️ Installation

**Option 1 — Clone with Git**
```powershell
git clone https://github.com/yourusername/WinOptimiser.git
cd WinOptimiser
```

**Option 2 — Download ZIP**

Click the green **Code** button above → **Download ZIP** → Extract → Run.

**Option 3 — One-liner (coming soon)**
```powershell
irm https://raw.githubusercontent.com/yourusername/WinOptimiser/main/install.ps1 | iex
```

---

## 🚀 Usage

Right-click `WinOptimiser.ps1` and select **Run with PowerShell**, or from an elevated terminal:

```powershell
# Bypass execution policy for this session only
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

# Run the script
.\WinOptimiser.ps1
```

You'll be presented with an interactive menu:

```
╔══════════════════════════════╗
║       WinOptimiser v1.0      ║
╠══════════════════════════════╣
║  [1] Clean Junk Files        ║
║  [2] Boost Performance       ║
║  [3] Manage Startup          ║
║  [4] Run All                 ║
║  [5] View Log                ║
║  [0] Exit                    ║
╚══════════════════════════════╝
```

---

## 📁 Project Structure

```
WinOptimiser/
├── WinOptimiser.ps1       # Main entry point
├── modules/
│   ├── JunkCleaner.ps1    # Junk file removal logic
│   ├── RamOptimiser.ps1   # Memory optimisation
│   └── StartupManager.ps1 # Startup program manager
├── logs/                  # Auto-generated logs
├── README.md
└── LICENSE
```

---

## 🗺️ Roadmap

- [x] Junk file cleaner
- [x] RAM optimiser
- [x] Startup manager
- [x] Action logging
- [ ] Scheduled task support
- [ ] GUI wrapper
- [ ] Auto-update checker
- [ ] Registry cleaner module
- [ ] Dark/Light theme for GUI
- [ ] `.exe` packaged release

---

## 🤝 Contributing

Contributions are what make the open-source community great. Any contributions you make are **greatly appreciated**.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 🐛 Reporting Issues

Found a bug? [Open an issue](https://github.com/yourusername/WinOptimiser/issues) and include:

- Your Windows version
- PowerShell version (`$PSVersionTable.PSVersion`)
- Steps to reproduce
- The log file from `/logs/`

---

## ⚠️ Disclaimer

WinOptimiser makes changes to system settings and files. Always review the script before running and ensure you have a system restore point. The author is not responsible for any unintended effects.

---

## 📜 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.

---

## 👤 Author

**yourusername**

[![GitHub](https://img.shields.io/badge/GitHub-yourusername-181717?style=flat-square&logo=github)](https://github.com/yourusername)

---

<div align="center">

If WinOptimiser helped you, consider leaving a ⭐ — it means a lot!

**[⬆ Back to top](#-winoptimiser)**

</div>
