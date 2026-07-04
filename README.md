# 📊 SkillStats

> A modern, lightweight, and fully customizable RPG Skills & Stats plugin for Spigot & Paper.

![GitHub](https://img.shields.io/github/license/USERNAME/SkillStats?style=for-the-badge)
![GitHub Stars](https://img.shields.io/github/stars/USERNAME/SkillStats?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-21-orange?style=for-the-badge)
![Minecraft](https://img.shields.io/badge/Minecraft-1.21+-green?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open%20Source-❤-blue?style=for-the-badge)

SkillStats is an open-source RPG progression plugin built for modern Minecraft servers. It provides customizable skills, XP progression, player statistics, leaderboards, and a developer-friendly API while remaining lightweight and highly configurable.

Whether you're creating a Survival, Skyblock, SMP, Prison, or MMO-style server, SkillStats makes player progression rewarding without sacrificing performance.

---

# ✨ Features

* 📈 RPG-style skill progression
* ⭐ Fully configurable XP system
* 🏆 Unlimited custom skills
* 📊 Beautiful statistics GUI
* 🥇 Player leaderboards
* 💾 SQLite & MySQL support
* ⚡ Asynchronous database operations
* 🎨 Modern configurable messages
* 🌍 Multi-language support
* 🔌 PlaceholderAPI integration
* 🧩 Public Developer API
* 🔧 Hot reload support
* 🚀 Built for modern Paper servers
* ❤️ Completely Free & Open Source

---

# 🎮 Default Skills

* ⛏ Mining
* 🌲 Woodcutting
* 🌾 Farming
* 🎣 Fishing
* ⚔ Combat
* 🏹 Archery
* 🪨 Excavation
* 🔨 Crafting

Create your own skills or disable any you don't need.

---

# 📸 Screenshots

> Coming Soon

| Stats Menu               | Skill Progress           | Leaderboards             |
| ------------------------ | ------------------------ | ------------------------ |
| *(Add screenshots here)* | *(Add screenshots here)* | *(Add screenshots here)* |

---

# 📦 Installation

1. Download the latest release.
2. Place `SkillStats.jar` into your server's `plugins` folder.
3. Restart your server.
4. Configure the plugin inside `/plugins/SkillStats/`.
5. Enjoy!

---

# 📜 Commands

| Command                | Description          |
| ---------------------- | -------------------- |
| `/stats`               | View your statistics |
| `/skills`              | View all skills      |
| `/skillstats reload`   | Reload configuration |
| `/skillstats givexp`   | Give experience      |
| `/skillstats setlevel` | Set a player's level |

---

# 🔐 Permissions

| Permission          | Description             |
| ------------------- | ----------------------- |
| `skillstats.stats`  | View stats              |
| `skillstats.skills` | View skills             |
| `skillstats.admin`  | Administrative commands |
| `skillstats.reload` | Reload plugin           |

---

# ⚙ Configuration

SkillStats was designed to be configured without touching the source code.

You can customize:

* XP per action
* Maximum levels
* Skill names
* GUI layouts
* Messages
* Sounds
* Rewards
* Multipliers
* Database settings
* Placeholders

---

# 🔌 Integrations

Supported:

* PlaceholderAPI
* Vault
* LuckPerms
* MySQL
* SQLite

Planned:

* MMOItems
* ItemsAdder
* Oraxen
* EcoSkills
* ModelEngine

---

# 🧩 Developer API

Register custom skills, listen for events, award experience, or create your own progression mechanics.

Example:

```java
SkillAPI.giveXP(player, SkillType.MINING, 50);

SkillAPI.setLevel(player, SkillType.FARMING, 25);

int level = SkillAPI.getLevel(player, SkillType.COMBAT);
```

Documentation will be available on the Wiki.

---

# 🚀 Roadmap

* [x] Skill System
* [x] XP Progression
* [x] Statistics GUI
* [x] Database Support
* [x] PlaceholderAPI

### Planned

* [ ] Skill Trees
* [ ] Prestige System
* [ ] Passive Abilities
* [ ] Custom Rewards
* [ ] Daily Quests
* [ ] Leaderboard GUI
* [ ] REST API
* [ ] Web Dashboard

---

# 🤝 Contributing

Contributions are always welcome!

If you'd like to improve SkillStats:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a Pull Request.

Please follow the project's coding style and include documentation for any new features.

---

# 🐛 Bug Reports

Found a bug?

Please open a GitHub Issue and include:

* Minecraft Version
* Paper/Spigot Version
* Java Version
* Plugin Version
* Console Errors
* Steps to Reproduce

---

# 💡 Feature Requests

Have an idea?

Open an Issue or Discussion. Community feedback helps shape future releases.

---

# 📄 License

SkillStats is licensed under the MIT License.

You are free to use, modify, and distribute this project in accordance with the license.

---

# ❤️ Support

If SkillStats helped your server:

⭐ Star the repository

🍴 Fork the project

🐞 Report bugs

💡 Suggest features

🤝 Contribute code

Every contribution helps make the plugin better for the community.

---

## Made with ❤️ for the Minecraft Community
