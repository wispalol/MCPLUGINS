# ChatFilter


A lightweight and configurable chat filtering plugin for **Minecraft Paper/Spigot 1.21.1**.


## ✨ Features
- Filters inappropriate chat messages
- Censor, block, or warn modes
- Permission-based bypass
- Staff notifications
- Config reload command
- Optimised for performance


## 🧩 Compatibility
- Minecraft: **1.21.1**
- Server: Paper / Spigot
- Java: **21**


## 📦 Installation
1. Download or build the plugin
2. Place `ChatFilter.jar` into `/plugins`
3. Restart the server
4. Edit `config.yml`
5. Run `/chatfilter reload`


## ⚙️ Commands
| Command | Description |
|-------|------------|
| `/chatfilter reload` | Reloads the config |


## 🔐 Permissions
| Permission | Description |
|----------|------------|
| `chatfilter.bypass` | Bypass chat filter |
| `chatfilter.notify` | Receive staff alerts |
| `chatfilter.reload` | Reload config |


## 🛠️ Building
```bash
mvn clean package
