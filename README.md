# Hex Player

<p align="center">
  <img src="https://raw.githubusercontent.com/xlaro/HexPlayer/main/assets/logo.png" alt="Hex Player Logo" width="120" height="120">
</p>

<p align="center">
  <a href="https://github.com/xlaro/HexPlayer/releases/latest"><img src="https://img.shields.io/github/v/release/xlaro/HexPlayer?style=flat-square&color=blue" alt="Latest Version"></a>
  <a href="#platform-support"><img src="https://img.shields.io/badge/platform-Windows-0078D6?style=flat-square&logo=windows" alt="Platform"></a>
  <a href="https://github.com/xlaro/HexPlayer/releases"><img src="https://img.shields.io/github/downloads/xlaro/HexPlayer/total?style=flat-square&color=orange" alt="Total Downloads"></a>
  <a href="https://github.com/xlaro/HexPlayer/blob/main/LICENSE"><img src="https://img.shields.io/github/license/xlaro/HexPlayer?style=flat-square" alt="License"></a>
</p>

---

## 📖 Description

**Hex Player** is a sleek, high-performance desktop media player built exclusively for Windows. Built on top of the Electron framework, it is engineered for fluid local media playback, advanced DRM stream decryption, and dynamic network request routing. Combining a revamped modern dark aesthetic with ultra-low resource consumption, Hex Player delivers a robust playback experience for live streams, IPTV playlists, and protected media content.

---

## 🔥 Key Features

* **Multi-Format Feed Ingestion:** Load, parse, and organize remote IPTV channels formatted in raw M3U files or structured JSON feeds.
* **Automated Background Sync:** Automatically refresh remote M3U feeds on startup or on demand to keep channel lineups current.
* **Live Program Guide (EPG):** View Electronic Program Guide timeline metadata extracted directly from embedded XMLTV sources.
* **DASH & ClearKey Decryption:** Powered by Shaka Player to natively support encrypted MPEG-DASH streams with custom ClearKey pairs.
* **Dynamic Header Injection:** Configure custom User-Agents, Referrers, and HTTP authorization headers for both playlist fetching and stream segments.
* **Adaptive Bitrate Engine:** Integrated with `hls.js` for buffer-free playback, automatic resolution scaling, and full-screen HLS support.
* **Instant Channel Search:** Instant zero-latency fuzzy search across active streams, playlists, and channel categories.
* **Multi-Track Audio Demuxer:** Switch seamlessly between multi-language audio tracks and commentary feeds.
* **Modern Material Dark UI:** A polished, robust interface designed for maximum contrast and eye comfort during continuous night viewing.
* **Single Stream Launcher:** Quick-launch playback mode for testing isolated stream links with custom headers and DRM parameters.

---

## 📊 Live Statistics

| Metric | Details |
| :--- | :--- |
| **Total Downloads** | ![Downloads](https://img.shields.io/github/downloads/xlaro/HexPlayer/total?style=flat-square&label=%20) *(Live GitHub Counter)* |
| **Latest Release** | **v1.1.0** |
| **Target OS** | Windows 10 / 11 (64-bit) |
| **Framework Engine** | Electron + hls.js + Shaka Player |
| **License Type** | MIT License |

---

## 💻 Platform Support

Currently, **Hex Player** is available exclusively for:

* **Windows 10 / 11** (64-bit)

---

## 🖼️ Screenshots

<p align="center">
  <img src="https://raw.githubusercontent.com/xlaro/HexPlayer/main/screenshot/Hex%20Player%20Screenshot%20(1).png" width="45%" alt="Hex Player Main View">
  <img src="https://raw.githubusercontent.com/xlaro/HexPlayer/main/screenshot/Hex%20Player%20Screenshot%20(2).png" width="45%" alt="Playlist">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/xlaro/HexPlayer/main/screenshot/Hex%20Player%20Screenshot%20(3).png" width="45%" alt="Favorite Chennel">
  <img src="https://raw.githubusercontent.com/xlaro/HexPlayer/main/screenshot/Hex%20Player%20Screenshot%20(4).png" width="45%" alt="Setting">
</p>

---

## 📥 Download & Installation

1. Download the latest Windows release build from the [Releases Page](https://github.com/xlaro/HexPlayer/releases/tag/v1.1.0).
2. Extract the archive or launch the setup executable.
3. Run **Hex Player** to launch the player interface.

---

## ⚡ Quick Usage Guide

* **Stream Single URL:** Click the stream icon, input your target media URL along with any required HTTP headers or ClearKey DRM pairs, and hit **Play**.
* **Load Playlist:** Open the Playlist Manager, input your M3U or JSON URL, and let Hex Player parse your channel list automatically.
* **Keyboard Shortcuts:** Use dedicated hotkeys to quickly step through channels, adjust audio tracks, or toggle full-screen view.

---

## 📜 License & Legal

This project is licensed under the terms outlined in the [LICENSE](https://github.com/xlaro/HexPlayer/blob/main/LICENSE) file. 

> **Disclaimer:** Hex Player is a standalone media player tool. It does not provide, host, or index any media channels or copyrighted live streams. Users are solely responsible for providing their own legal stream sources.

---

## ⚖️ Terms of Service

By using Hex Player, you agree to adhere to all applicable local and international copyright regulations. The developers hold no responsibility or liability for unauthorized access, misuse, or streaming policy violations conducted by end users.
