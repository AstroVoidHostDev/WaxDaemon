<h1 align="center">✨ Wax Daemon ✨</h1>

<p align="center">
  <strong>⚡ Ultra Advanced Hosting Panel • Inspired by Pterodactyl Eggs</strong><br>
  💻 Fast • Secure • Developer Friendly
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-20.x-green?style=for-the-badge&logo=node.js" alt="Node.js">
  <img src="https://img.shields.io/badge/Build-Stable-success?style=for-the-badge" alt="Build Status">
  <img src="https://img.shields.io/badge/UI-Modern-blueviolet?style=for-the-badge" alt="UI">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Platform-Linux%20%7C%20Docker-orange?style=for-the-badge" alt="Platform">
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-quick-install">Quick Install</a> •
  <a href="#-start-daemon">Start</a> •
  <a href="#-manual-installation">Manual Install</a> •
  <a href="#-production-setup">Production</a> •
  <a href="#-troubleshooting">Troubleshooting</a> •
  <a href="#-features">Features</a> •
  <a href="#-plugin-system">Plugins</a> •
  <a href="#-security">Security</a> •
  <a href="#-contributing">Contributing</a>
</p>

---

## 🧠 Overview

**Wax Daemon** is a powerful node for your AstroWax Panel!

> **Philosophy:** Fast • Secure • Developer Friendly

---

## ⚡ Quick Install

> [!TIP]
> **One-Line Magic**
> Get up and running instantly with this single command. Ideal for testing or rapid deployment.

```bash
cd && sudo apt-get clean && sudo apt update && sudo apt install -y git zip unzip curl && git clone https://github.com/AstroVoidHostDev/WaxDaemon && cd WaxDaemon && unzip waxdaemon.zip && cd daemon && npm install && echo "Paste your config below"
```

---

## 🚀 Start Daemon

> After pasting your config, run the daemon with:

```bash
node .
```

---

## 🏭 Production Setup

* Use **PM2** for process management
* Enable auto-restart
* Use reverse proxy (NGINX)

```bash
npm install -g pm2
pm2 start index.js --name wax-daemon
pm2 save
pm2 startup
```

---

## 🛠️ Troubleshooting

* Make sure Node.js 18+ or 20.x is installed
* Check config.json is valid
* Run with `node .` for errors

---

## ✨ Features

* ⚡ High performance daemon
* 🔒 Secure environment
* 🧩 Plugin system support
* 🖥️ Modern UI ready
* 🐳 Docker compatible

---

## 🔌 Plugin System

Extend functionality using custom plugins.

---

## 🔐 Security

* Sandboxed execution
* Resource limits
* Safe container handling

---

## 🤝 Contributing

Pull requests are welcome!
Feel free to fork and improve 🚀

Made By ❤️ ITZ_YTANSH
