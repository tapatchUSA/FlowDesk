<p align="center"><img src="flowdesk-icon.png" width="112" alt="FlowDesk icon"></p>
<h1 align="center">FlowDesk</h1>
<p align="center"><b>Launch and organize everything, perfectly.</b></p>
<p align="center">App Launcher · Windows 10/11 · x64 · ~5 MB · Free for personal use</p>
<p align="center"><a href="https://github.com/tapatchUSA/FlowDesk/releases/latest"><b>⬇ Download FlowDesk 1.0.2</b></a> &nbsp;·&nbsp; <a href="https://tapatch.com/tools/flowdesk/">tapatch.com/tools/flowdesk</a></p>

<p align="center">
<img src="screenshots/flowdesk.png" alt="FlowDesk">
</p>

> Built because no launcher did everything without compromise. FlowDesk does.

## What it does

FlowDesk is a unified task launcher and scheduler. Pin apps, scripts, folders, and URLs, organise them into categories, and schedule anything to run at a time or interval — with optional UAC elevation. Import and export your setup as JSON. Everything in one tight interface, nothing in the system tray you didn't ask for.

[![Watch on YouTube](https://img.youtube.com/vi/tcTqnHmmaUw/hqdefault.jpg)](https://www.youtube.com/watch?v=tcTqnHmmaUw)

## Features

Built to handle everything you throw at it. Here are the highlights.

**🚀 App launcher**  
Pin apps, scripts, folders, and URLs for one-click launch. Search through everything instantly as your list grows.

**🕐 Scheduler**  
Schedule any item to run at a specific time, on an interval, or at startup. Set it once and forget it.

**🛡️ UAC elevation**  
Run any launcher item as administrator with built-in elevation support.

**📁 Categories**  
Organise launchers into labelled groups. Collapse, reorder, and customise to match how you actually work.

**📦 Import / Export**  
Save your entire launcher setup to a JSON file. Restore it on a new machine or share it with your team.

**🔍 App search**  
Search installed apps directly from FlowDesk without opening the Start menu or typing in Explorer.

## Limitations

- Scheduled tasks only run while FlowDesk is open. For persistent background scheduling, add FlowDesk itself to Windows startup.

## What's new in 1.0.2

- Now in 10 languages: English, Chinese (Simplified), Russian, Spanish, Portuguese, German, Japanese, French, Polish and Korean
- Starts in your Windows language (English if yours isn't one of the 10). The first launch asks which language you want, and you can switch any time inside the app
- The installer comes in the same 10 languages
- The Terms of Service are shown translated for convenience, with the official English (US) text, the only binding version, right below

Release notes for every version are on the [Releases](https://github.com/tapatchUSA/FlowDesk/releases) page.

## Install

1. Download **FlowDesk-Setup-1.0.2.exe** from the [latest release](https://github.com/tapatchUSA/FlowDesk/releases/latest) or from [tapatch.com](https://tapatch.com/tools/flowdesk/).
2. Run it. The installer and the app come in 10 languages.
3. Accept the Terms of Service on first launch.

Windows may show a SmartScreen warning for new downloads. Click **More info → Run anyway**.

Or with [Scoop](https://scoop.sh):

```powershell
scoop bucket add tapatch https://github.com/tapatchUSA/packages
scoop install tapatch/flowdesk
```

## All versions

| Version | Released | Installer | VirusTotal | SHA-256 |
|---|---|---|---|---|
| [1.0.2](https://github.com/tapatchUSA/FlowDesk/releases/tag/v1.0.2) | 2026-10-01 | [FlowDesk-Setup-1.0.2.exe](https://github.com/tapatchUSA/FlowDesk/releases/download/v1.0.2/FlowDesk-Setup-1.0.2.exe) | [1 / 70](https://www.virustotal.com/gui/file/8a6c6ce4c3ae5798f9e5b59186103498d5664c08be210db9fd7f57b8ed388113/detection) | `8a6c6ce4c3ae5798…` |
| [1.0.1](https://github.com/tapatchUSA/FlowDesk/releases/tag/v1.0.1) | 2026-09-30 | [FlowDesk-Setup-1.0.1.exe](https://github.com/tapatchUSA/FlowDesk/releases/download/v1.0.1/FlowDesk-Setup-1.0.1.exe) | [2 / 69](https://www.virustotal.com/gui/file/85520c658f85537281a053c75b59a6b6250b3f8e627bcc8ecac0ed106abc6528/detection) | `85520c658f855372…` |
| [1.0.0](https://github.com/tapatchUSA/FlowDesk/releases/tag/v1.0.0) | 2026-04-11 | [FlowDesk-Setup-1.0.0.exe](https://github.com/tapatchUSA/FlowDesk/releases/download/v1.0.0/FlowDesk-Setup-1.0.0.exe) | [2 / 71](https://www.virustotal.com/gui/file/658428e92fae27ad736cad9cdb06bcda28692245bcafc79e1a0bb0686d1eef0a/detection) | `658428e92fae27ad…` |

## Security

Every installer is scanned on VirusTotal before release. FlowDesk 1.0.2: **1 / 70** engines flag it · [view report](https://www.virustotal.com/gui/file/8a6c6ce4c3ae5798f9e5b59186103498d5664c08be210db9fd7f57b8ed388113/detection)

**SHA-256**
```
8a6c6ce4c3ae5798f9e5b59186103498d5664c08be210db9fd7f57b8ed388113
```

## Built with

Rust · egui · eframe · serde · rfd

## License

Free for personal use. Business or commercial use requires a paid license (see [tapatch.com/terms](https://tapatch.com/terms/)). Full terms: [tapatch.com/terms/software](https://tapatch.com/terms/software/).

This repository holds the official installers and release notes.

---

**[tapatch.com](https://tapatch.com)**: small tools, serious quality. Built solo, shipped with care.
