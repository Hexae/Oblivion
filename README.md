# ⚔️ Myth of Empires — Leaderboard & Community Tracker

This project is a real-time leaderboard and player tracking system designed for *Myth of Empires* private servers. Built with **FastAPI**, **Redis**, and **HTML/CSS/JS**, it powers a custom web dashboard and Discord bot highlighting server activity, guild presence, and individual player profiles.

---

## 🌐 Features

- 🏆 **Leaderboard Pages**: Ranks players based on activity points (daily, weekly, or all-time), filterable by server.
- 👤 **Player Profiles**: Dynamic player pages with guild, rank, avatar, and skill stats.
- 🔍 **Search & Filters**: Easily find players by name or server, with paginated results.
- 🧠 **Redis-Driven**: Uses Redis to store real-time activity, profile, and guild data.
- 🎮 **Guild Integration**: Displays guild names, roles, and ranks (Lord, Advisor, etc.).
- 💬 **Chat Sync (optional)**: Captures in-game [County] chat logs and relays them to Discord.
- 🛡️ **Admin Tools**: Interface to rename or link unknown UIDS to player profiles.

---

## 💻 Tech Stack

- **Backend**: Python 3.10+, FastAPI, Redis
- **Frontend**: HTML5, Jinja2, CSS (OSRS-inspired style)
- **Bot**: Disnake (for Discord integration)
- **Storage**: Redis (standalone 3.2 or 6+), SQLite (optional for guild/role persistence)

---

## 📷 Screenshots

Coming soon...

---

## 📜 License

MIT License. Use freely, modify respectfully.

---

## 🙌 Credits

- Built by Hexae.
- Inspired by the *Myth of Empires* community.
- Styled after classic OSRS leaderboard themes.
