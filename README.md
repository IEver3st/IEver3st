<div align="center">

# Ever3st

**I build practical software that removes friction from repetitive work.**

[![GitHub followers](https://img.shields.io/github/followers/IEver3st?style=flat-square\&logo=github\&label=followers\&color=238636)](https://github.com/IEver3st?tab=followers)
[![Profile views](https://komarev.com/ghpvc/?username=IEver3st\&style=flat-square\&color=1F6FEB\&label=profile+views)](https://github.com/IEver3st)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono\&size=14\&duration=2600\&pause=900\&color=58A6FF\&center=true\&vCenter=true\&width=720\&lines=desktop+software+%E2%80%A2+local-first+tools+%E2%80%A2+open-source+utilities;building+systems+that+save+people+time)](https://git.io/typing-svg)

</div>

---

## About

I am a software engineering student and the developer behind **[Cortex Software](https://cortexsoftware.net)**. My work spans privacy-first desktop applications, static analysis, real-time 3D tooling, safe file operations, remote infrastructure, and game-development utilities.

Most of my projects begin with a nuisance I encounter personally and end as a tool other people can use.

> **Engineering principle:** inspect first, modify safely, and leave the user a reliable way back.

---

## Featured work

|    #   | Project                                                              | What it does                                                                                                                                                                                                                                                          | Core stack                                             |
| :----: | -------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| **01** | **[Cortex Studio](https://github.com/IEver3st/cortex-labs)**         | Real-time 3D livery development environment for GTA V and FiveM. Supports native YFT/YDD models, live texture reloads, PSD variant workflows, template generation, and custom DDS/BC7 decoding.                                                                       | `React` `Three.js` `Tauri v2` `Rust` `C#`              |
| **02** | **[Cortex Toolbox](https://github.com/IEver3st/Cortex-Toolbox)**     | Local-first desktop workbench for building, auditing, repairing, and packaging FiveM resources and GTA V assets. Includes manifest editing, static script analysis, dependency mapping, vehicle metadata repair, siren-pattern design, and release-ready ZIP exports. | `TypeScript` `React` `Electron` `Zustand` `CodeMirror` |
| **03** | **[CompressThing](https://github.com/IEver3st/compressthing)**       | Local image and video compression with bulk processing, format conversion, FFmpeg/WebAssembly fallbacks, and native NVIDIA, AMD, and Intel GPU encoding. Files never need to leave the machine.                                                                       | `TypeScript` `React` `Tauri v2` `Rust` `FFmpeg`        |
| **04** | **[Tailmark](https://github.com/IEver3st/Tailmark)**                 | Safe bulk installer and library manager for War Thunder user skins and sound mods. Inspects archives before installation, detects conflicts, creates backups, and rolls back failed operations.                                                                       | `TypeScript` `React` `Electron` `Zustand`              |
| **05** | **[Sentry](https://github.com/IEver3st/Sentry)**                     | Feature-complete automatic backup utility with configurable jobs, a native desktop interface, and optional Google Drive integration.                                                                                                                                  | `TypeScript` `React` `Tauri` `Rust`                    |
| **06** | **[Project Kiwi](https://github.com/IEver3st/Project-Kiwi)**         | Authenticated remote game-server management over SSH, with live logs, health monitoring, scheduled backups, and multi-user isolation.                                                                                                                                 | `Next.js` `TypeScript` `SQLite` `Socket.io` `SSH`      |
| **07** | **[Tesla HW4 Finder](https://github.com/IEver3st/Tesla-HW4-Finder)** | Chrome extension that reads Tesla VINs on vehicle listings and identifies likely HW3 or HW4 vehicles using known production thresholds.                                                                                                                               | `JavaScript` `Chrome Extensions`                       |

---

## What I tend to build

```text
local-first desktop software   ── privacy, performance, native file access
workflow tools                 ── fewer repetitive steps and safer automation
developer workbenches          ── analysis, validation, repair, and packaging
real-time interfaces           ── live previews, logs, status, and feedback
specialised utilities          ── software for problems broad tools overlook
```

---

## Working stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge\&logo=rust\&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge\&logo=lua\&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge\&logo=threedotjs\&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=for-the-badge\&logo=tauri\&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-2B2E3A?style=for-the-badge\&logo=electron\&logoColor=9FEAF9)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge\&logo=nextdotjs\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge\&logo=sqlite\&logoColor=white)

</div>

---

## FiveM / GTA V ecosystem

Cortex Studio and Cortex Toolbox are featured above because they have grown into complete desktop development environments. The supporting FiveM ecosystem remains public and modular:

| Repository                                                       | Role                                                                                                                                 | Stack              |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------ |
| **[cortex-metagen](https://github.com/IEver3st/cortex-metagen)** | Vehicle metadata studio and editor for the final stages of GTA V and FiveM vehicle development.                                      | `TypeScript`       |
| **[polcam](https://github.com/IEver3st/polcam)**                 | Open-source helicopter camera system with target tracking, vision modes, spotlight controls, exports, and QBX or standalone support. | `Lua` `HTML` `CSS` |
| **[es_lib](https://github.com/IEver3st/es_lib)**                 | Shared UI components and reusable Lua functions used across the script ecosystem.                                                    | `Lua`              |
| **[es_hud](https://github.com/IEver3st/es_hud)**                 | Customisable HUD designed to integrate cleanly with the wider ecosystem.                                                             | `Lua`              |
| **[es_chat](https://github.com/IEver3st/es_chat)**               | Lightweight FiveM chat skin for consistent presentation across resources.                                                            | `JavaScript`       |
| **[GSDAudio](https://github.com/IEver3st/GSDAudio)**             | Supporting audio package for GSD vehicle resources.                                                                                  | `Lua`              |

---

<div align="center">

<sub>Built under <a href="https://cortexsoftware.net">Cortex Software</a> · practical tools, careful engineering, fewer wasted steps.</sub>

</div>
