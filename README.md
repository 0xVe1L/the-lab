<p align="center">
  <img src="assets/hero.png" width="560" alt="The Lab — presented by 0xVe1L and Dad's MMO Lab">
</p>

<h3 align="center">Your own World of Warcraft world — installed, managed, and played from the couch.</h3>

<p align="center">
  Run a private WoW 3.3.5a server on your Steam Deck, fill it with hundreds of AI players,
  build a party of bots, and tweak everything from a friendly, clickable app.
  <br>No terminal. No command line. No guesswork.
</p>

<p align="center">
  <a href="https://github.com/0xVe1L/the-lab/releases/latest/download/TheLab.AppImage"><b>⬇&nbsp; Download The Lab</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/0xVe1L/the-lab/releases/latest">Latest release</a>
</p>

---

## What is this?

Setting up a private WoW server is normally a weekend of terminal commands. **The Lab turns it into a few clicks.** It wraps the open-source [AzerothCore](https://www.azerothcore.org/) server and [mod-playerbots](https://github.com/liyunfan1223/mod-playerbots) behind a desktop app built for **people who love games, not developers**.

Install a server, populate your world with AI players, summon a full party of bots, mail yourself any item, teleport anywhere, and fine-tune how it all works — all from Steam Deck Gaming Mode.

> **You bring your own game client.** The Lab only orchestrates open-source server emulators. It never includes, distributes, or links to Blizzard game files — you point it at your own legally-obtained **WoW 3.3.5a (Wrath of the Lich King)** client.

<p align="center"><img src="assets/server-start.png" width="560" alt="Starting the server with a live, readable console"></p>

---

## Features

### 🖥 One-click server
- Install a complete WoW 3.3.5a server (AzerothCore + Playerbots) from a **single button** — Docker, database, modules, and bots are all set up for you.
- **Start / stop / restart** with a live, human-readable console — no scrolling raw logs.
- **Auto-shutdown**: the server quits on its own when you close WoW, so it never drains the Deck in the background.
- Built for **Steam Deck Gaming Mode** — add it to Steam and launch it from the couch. (Also runs on Linux desktops; Windows support is on the roadmap.)

### 🧙 Dashboard & your character
<p align="center"><img src="assets/dashboard.png" width="560" alt="Character dashboard with equipped gear and stats"></p>

- A live **character paper-doll** showing your equipped gear, level, and class.
- **Gear** and **Talents** views in one place, with quick actions.

### 🤖 Bots — the reason we exist
<p align="center"><img src="assets/player-bots.png" width="560" alt="Browsing the player-bot roster"></p>

- **Hundreds of AI players** live in your world — they quest, run dungeons, raid, trade, and chat like real people, so a solo server never feels empty.
- **My Party** — build a 5-man group of bots. For each slot you pick a **role → class → spec → talent build → level**, and The Lab spawns the bot, gears it, applies its talents, and teleports it right to you.

<p align="center">
  <img src="assets/my-party.png" width="276" alt="My Party — five-man party setup">
  <img src="assets/add-party-role.png" width="276" alt="Choose a role: Tank, Healer, or DPS">
</p>
<p align="center">
  <img src="assets/add-party-class.png" width="276" alt="Choose a class">
  <img src="assets/add-party-build.png" width="276" alt="Choose a talent build and bot level">
</p>

- **Party Presets** — save a party composition and re-summon the exact same group any time, or share it with friends. Ships with ready-made example parties.
- **Talent trees** — browse any class's full talent layout, exactly like in-game.

<p align="center"><img src="assets/talents.png" width="560" alt="Full talent-tree view"></p>

- **Global bot settings** — control how many bots populate the world, their level range, what they do (questing, dungeons, battlegrounds), and performance tuning so it stays smooth on a Deck.

### 🎒 Item database & in-game mail
<p align="center"><img src="assets/item-database.png" width="560" alt="Searchable item database with real icons and tooltips"></p>

- Search the **entire item database** with quality and class filters, real icons, and full tooltips.
- **Send any item** straight to your character through in-game mail — whether you're online or offline.

### 🌍 Teleport anywhere
<p align="center"><img src="assets/teleport.png" width="560" alt="Teleport to named locations or exact coordinates"></p>

- Beam your character to any of **thousands of named locations**, or to exact map coordinates. Save your favorites for one-tap travel.

### 🏷 Auction House bot
- A configurable bot keeps your auction house **stocked and active** so the in-game economy feels alive — all tuned from a friendly UI, with no SQL or config-file editing.

### ⚙ Settings & power tools
<p align="center">
  <img src="assets/settings-app.png" width="276" alt="App settings — updates, audio, cursor">
  <img src="assets/settings-modules.png" width="276" alt="Module management and uninstall">
</p>

- **Data enrichment** — pulls icons, tooltips, and talent data from *your own* WoW client so everything shows real names and art.
- **Character backup & restore** — portable backup files. Back up before a rebuild, or move characters between installs, without losing progress.
- **Steam integration** — adds The Lab (and your WoW client) to Steam as non-Steam games, complete with artwork, ready for Gaming Mode.
- **Controller support**, **Warcraft cursor themes**, and audio options.
- **Module management** — enable or disable AzerothCore modules and edit their raw configs, then rebuild — all from inside the app.
- **World settings** — adjust XP, gold, drop rates, and other server knobs.
- **Bring an existing server under management** — already set one up the manual way? The Lab detects it and migrates it in, **keeping all your characters and data**.
- **In-app updates** — new versions install in place; your server, characters, and settings are left untouched.

### 🌐 Play Together — *coming soon*
Open your world so friends can hop in with their own characters and keep their progress.

---

## Requirements
- A **Steam Deck** (SteamOS) is the primary target. Also runs on Linux desktops; **Windows support is planned**.
- Your own **WoW 3.3.5a (Wrath of the Lich King)** game client. The Lab never provides game files.
- Roughly **15 GB** of free space for the server.

## Install
1. **[Download `TheLab.AppImage`](https://github.com/0xVe1L/the-lab/releases/latest/download/TheLab.AppImage)** from the latest release.
2. Make it executable and run it — or let the app add itself to Steam so you can launch it from Gaming Mode.
3. Click **Install server** and follow along on screen. The first Playerbots install compiles from source, so grab a coffee — after that, starting up takes seconds.

## About
The Lab is a labor of love for **dads who love games, not developers** — making it dead-simple to relive WoW in your own private world that's full of life. It orchestrates only **open-source emulators** (AzerothCore, mod-playerbots, and friends) and never includes copyrighted game clients or assets.

<p align="center"><i>Presented by <b>0xVe1L</b> and <b>Dad's MMO Lab</b>.</i></p>
