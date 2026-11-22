# IP Unlocker — VPN client for Windows & macOS (Xray / sing-box)

**IP Unlocker** is a simple, fast **VPN and proxy client for Windows 10/11 and macOS** (Apple Silicon and Intel), built on **Xray-core** and **sing-box**. Paste your server link (**VLESS, Reality, VMess, Trojan, Shadowsocks, Hysteria2, TUIC, AnyTLS**) or a **Clash subscription**, press *Connect*: the app picks the fastest node, protects the whole computer with a **TUN** adapter and a **kill switch**, and keeps Chinese sites fast by sending them **direct**.

Available in **English, 中文, Français**.

[![Latest release](https://img.shields.io/github/v/release/Paquereauman/cu-bootstrap?label=latest&color=2ea44f)](https://github.com/Paquereauman/cu-bootstrap/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Paquereauman/cu-bootstrap/total?color=blue)](https://github.com/Paquereauman/cu-bootstrap/releases)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows)
![macOS](https://img.shields.io/badge/macOS-12%2B-000000?logo=apple)

## ⬇ Download

Always the latest version:

| Computer | Download |
|---|---|
| **Windows 10 / 11** | [⬇ IP-Unlocker-Windows.exe](https://github.com/Paquereauman/cu-bootstrap/releases/latest/download/IP-Unlocker-Windows.exe) |
| **Mac M1, M2, M3, M4** (Apple Silicon) | [⬇ IP-Unlocker-Mac-AppleSilicon.zip](https://github.com/Paquereauman/cu-bootstrap/releases/latest/download/IP-Unlocker-Mac-AppleSilicon.zip) |
| **Mac Intel** | [⬇ IP-Unlocker-Mac-Intel.zip](https://github.com/Paquereauman/cu-bootstrap/releases/latest/download/IP-Unlocker-Mac-Intel.zip) |

**Which Mac?**  menu › About This Mac: "Chip Apple M…" = Apple Silicon, "Processor Intel" = Intel.

**Mac (macOS 15):** unzip, open Terminal, type `bash ` (with a space), drag the file *Installer IP Unlocker.command* into the window and press Enter (no password needed).

**Already installed?** Settings › Updates › Check. The app also updates itself automatically.

All versions: [Releases](https://github.com/Paquereauman/cu-bootstrap/releases)

## ✨ Features

- **One-click connect** — paste a `vless://`, `vmess://`, `trojan://`, `ss://`, `hysteria2://`, `tuic://` or `anytls://` link, or import a **Clash / Mihomo YAML subscription**.
- **Fastest node, automatically** — every node is tested in the background; the app switches to a better one at a quiet moment and keeps a **standby node** ready for an instant switch.
- **Whole-computer VPN (TUN mode)** or **system proxy** mode.
- **Kill switch** — if no server answers, foreign traffic is blocked so your real IP never leaks.
- **Chinese sites go direct (split tunneling)** — Bilibili, Douyin, iQiyi, Tencent Video, WeChat, Taobao, Baidu, DeepSeek, Doubao, Kimi… stay fast and keep their full Chinese catalogues.
- **Ad & tracker blocking** in every app and browser.
- **Residential exit proxies** — chain a residential / ISP proxy after the VPN node for a clean exit IP (videos and P2P can skip it to save traffic).
- **Claude account protection** — Claude only goes through the VPN, and is blocked on servers in a region Anthropic does not serve; ChatGPT, Gemini and Google always go through the VPN too.
- **Privacy hardening** — WebRTC leak protection, WebGL / GPU fingerprint hiding, time zone and browser language matched to the exit country, QUIC blocking.
- **Game mode** — games skip the VPN; works alongside UU, Leigod and Xunyou accelerators.
- **Share to phone** — QR code for v2rayNG, Hiddify or Streisand.
- **Automatic updates**, start with the computer, light and native (no Electron).

## 🔌 Supported protocols

VLESS (Reality, Vision, XHTTP, WebSocket, gRPC) · VMess · Trojan · Shadowsocks · Hysteria2 · Hysteria · TUIC · AnyTLS · HTTP / SOCKS exit proxies · Clash subscriptions

Engines: [Xray-core](https://github.com/XTLS/Xray-core) and [sing-box](https://github.com/SagerNet/sing-box).

## ❓ FAQ

**What do I need?** A VPN server link or a Clash subscription (any provider), or the e-mail and password of the account you were given.

**Does it work in China?** Yes — it was made for it: Reality / Hysteria2 / fragmenting help connections through, and Chinese sites stay direct and fast.

**Windows SmartScreen shows a warning.** Click *More info › Run anyway*. The app needs administrator rights to create the TUN adapter.

**Can I use it like v2rayN, Clash Verge or Hiddify?** Yes: it reads the same links and Clash subscriptions, with automatic node selection and a kill switch built in.

---

## 中文

**IP Unlocker** 是一款适用于 **Windows 10/11 和 macOS**（Apple Silicon 与 Intel）的简单快速的 **VPN / 代理客户端**，基于 **Xray** 与 **sing-box**。粘贴服务器链接（**VLESS、Reality、VMess、Trojan、Shadowsocks、Hysteria2、TUIC、AnyTLS**）或 **Clash 订阅**，点击连接即可：自动选择最快节点，**TUN 全局模式**加**断网保护（Kill Switch）**，国内网站（B站、抖音、爱奇艺、腾讯视频、微信、淘宝、百度、DeepSeek、豆包、Kimi…）**直连**不变慢。支持去广告、住宅 IP 出口、Claude / ChatGPT 账号保护、游戏模式（兼容 UU、雷神、迅游加速器）、自动更新。界面支持中文。

下载：见上方表格（Windows / Mac）。

## Français

**IP Unlocker** est un **client VPN / proxy pour Windows 10/11 et macOS** (Apple Silicon et Intel), basé sur **Xray** et **sing-box**. Collez votre lien serveur (**VLESS, Reality, VMess, Trojan, Shadowsocks, Hysteria2, TUIC, AnyTLS**) ou un **abonnement Clash**, cliquez sur *Connecter* : l'appli choisit le nœud le plus rapide, protège tout l'ordinateur (**mode TUN** + **kill switch**) et laisse les sites chinois **en direct** pour qu'ils restent rapides. Blocage des pubs, sortie par **proxy résidentiel**, protection des comptes **Claude / ChatGPT**, mode jeu, mises à jour automatiques. Interface en français.

Téléchargement : voir le tableau ci-dessus.

---

<sub>Keywords: VPN client Windows, VPN Mac, Xray client, sing-box GUI, v2ray client, VLESS Reality client, Hysteria2 client, Clash subscription, TUN mode, kill switch, split tunneling China, bypass GFW, 翻墙, 科学上网, VPN 客户端, 机场订阅, Claude in China, ChatGPT in China.</sub>
