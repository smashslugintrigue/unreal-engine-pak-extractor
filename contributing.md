# 🎮 Unreal Engine Pak Extractor

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,15,28&height=210&section=header&text=Unreal%20Engine%20Pak%20Extractor&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Unpack%2C%20Inspect%20%26%20Rebuild%20Game%20Assets&descAlignY=56&descSize=18" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-3.6.0-0F4C5C?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Platform](https://img.shields.io/badge/Windows%20%7C%20Linux%20%7C%20macOS-5F0F40?style=for-the-badge&logo=unrealengine&logoColor=white)](https://www.unrealengine.com)
[![License](https://img.shields.io/badge/license-MIT-9A031E?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![UE Versions](https://img.shields.io/badge/UE4%20%7C%20UE5-FB8B24?style=for-the-badge&logo=unrealengine&logoColor=white)](https://github.com)

<br/>

### 📦 A fast, reliable tool for extracting and inspecting `.pak` files from Unreal Engine games

*🗂️ Browse Pak Files • 📤 Batch Export • 🔍 Asset Inspector • 🧩 Mod-Ready*

<br/>

<a href="https://share.google/ehEs36akF7xCWKoKJ">
  <img src="https://img.shields.io/badge/📥_DOWNLOAD-0F4C5C?style=for-the-badge&logo=download&logoColor=white&labelColor=0A3541" alt="Download" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/ehEs36akF7xCWKoKJ">
  <img src="https://img.shields.io/badge/🚀_QUICK_START-5F0F40?style=for-the-badge&logo=rocket&logoColor=white&labelColor=400A2B" alt="Quick Start" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/ehEs36akF7xCWKoKJ">
  <img src="https://img.shields.io/badge/📚_DOCS-FB8B24?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=C96F1A" alt="Docs" height="45"/>
</a>

</div>

<img width="1200" height="644" alt="3d660f_7a131eecb1764683aa0e55aa159e5fb0~mv2" src="https://github.com/user-attachments/assets/f62b869c-0656-44cf-a244-fc9f80383e1e" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Unreal Engine Pak Extractor** is a powerful, cross-platform tool that lets you **open, browse, and extract** `.pak` archives used by Unreal Engine games. Whether you're a modder, researcher, or preservationist, this tool gives you full visibility into game assets — textures, meshes, audio, blueprints, and more.

It supports **UE4 and UE5** pak formats, including encrypted and compressed archives, and is designed for **speed and safety** on real, large-scale game files.

> ⚠️ **Disclaimer:** This tool is intended for **legal modding, research, and preservation purposes only**. Always respect the game's End User License Agreement and local laws. Never redistribute extracted copyrighted assets.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| 🗂️ **Browse Pak Files** | 📤 **Batch Export** | 🔍 **Asset Inspector** |
|:---:|:---:|:---:|
| Tree view with<br/>search & filters | Extract one, many,<br/>or all files | Preview textures,<br/>audio & metadata |

| 🔐 **Encrypted Paks** | 🧩 **Mod-Ready** | ⚡ **Blazing Fast** |
|:---:|:---:|:---:|
| Supports AES-encrypted<br/>UE4/UE5 archives | Rebuild paks for<br/>mod distribution | Multi-threaded<br/>parallel extraction |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Tool

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| 🚀 **Multi-Threaded** | Extracts gigabytes of assets in seconds with parallel I/O |
| 🔐 **Encryption Support** | Handles AES-encrypted paks with simple key input |
| 🗂️ **Full UE4 + UE5** | Works with both pak formats, including IoStore (`.utoc`/`.ucas`) |
| 🎨 **Modern GUI** | Clean, intuitive interface plus a powerful CLI for automation |
| 🛡️ **Safe & Non-Destructive** | Never modifies game files — extraction is always read-only |
| 🧩 **Mod Pipeline Ready** | Includes a `repak` module to rebuild paks for your own mods |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Tool Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  📦  Unreal Engine Pak Extractor  v3.6.0         ║
╠══════════════════════════════════════════════════╣
║  Pak: Content/Paks/Game-WindowsNoEditor.pak      ║
║  Size: 4.82 GB   Engine: UE5.3   Encrypted: YES  ║
╠══════════════════════════════════════════════════╣
║  📁 Content/                                     ║
║   ├ 📂 Characters/                               ║
║   │  ├ 🖼️ hero_mesh.uasset      (12.4 MB)        ║
║   │  └ 🖼️ hero_tex.png          (4.8 MB)         ║
║   ├ 📂 Audio/                                    ║
║   │  └ 🎵 theme.ogg             (3.2 MB)         ║
║   └ 📂 Maps/                                     ║
║      └ 🗺️ level_01.umap        (86.1 MB)        ║
║                                                  ║
║  📤 [ Extract Selected ]   🔍 [ Inspect ]        ║
║  ⚡ 1,842 files indexed in 340ms                 ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
📦 unreal-engine-pak-extractor/
├── 🎯 src/
│   ├── pak/                   # Pak format parsers
│   │   ├── reader.py
│   │   ├── writer.py
│   │   └── crypto.py          # AES decryption
│   ├── iostore/               # UE5 .utoc/.ucas support
│   ├── gui/                   # Desktop interface
│   └── cli/                   # Command-line tool
├── 🧩 repak/                  # Rebuild paks for mods
├── 🧪 tests/                  # Sample pak test suite
└── 📖 docs/                   # Usage & legal guide
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Qt](https://img.shields.io/badge/Qt_6-41CD52?style=for-the-badge&logo=qt&logoColor=white)
![AES](https://img.shields.io/badge/AES--256-0F4C5C?style=for-the-badge&logo=letsencrypt&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a pak that won't open? Want to add support for a new engine version?

<div align="center">

<a href="https://share.google/ehEs36akF7xCWKoKJ">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/ehEs36akF7xCWKoKJ">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-0F4C5C?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/ehEs36akF7xCWKoKJ">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-9A031E?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

> **Legal note:** Unreal Engine and Unreal are trademarks of **Epic Games, Inc.** This tool is unofficial and not affiliated with Epic Games. Extracting content from copyrighted games may be restricted by their EULA — use only for legal modding, research, or preservation.

<br/>

<div align="center">

### 📦 Made with 🎮 by the Pak Extractor Team

*If this tool unlocked your modding journey — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,15,28&height=120&section=footer" width="100%"/>

</div>
