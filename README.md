# LoLHub - League of Legends Companion App

LoLHub has two independent parts:

**1. Riot Games API integration** — read-only stats and analytics for your own
tracked accounts (rank, mastery, match history, pre-game lobby lookup). This is
the part covered by our Riot Developer Portal application; all calls go
directly from the desktop app to Riot's official endpoints.

**2. Local League Client (LCU) convenience tools** — quality-of-life features
that talk only to your own local League Client process (127.0.0.1), not to
Riot's API: saved-profile switching, optional ready-check/champion-select
automation, and settings backup. These do not use the Riot Games API and are
outside the scope of our production API key request.

## Features

### 📊 Stats & Analytics (via Riot Games API)
- Rank history, LP trend, and current-form indicator
- Champion mastery and match history breakdown
- Pre-game/in-game lobby lookup (rank, recent form, champion win-rate)

### 🔐 Local Account Tools (League Client only — no Riot API involved)
- Switch between your own saved profiles without retyping credentials each time
- Optional per-profile convenience settings for ready-check and champion select
- Config Sync: back up and restore your keybinds/interface settings across profiles

**Note:** these local tools are provided as convenience features only. If Riot
Games determines that any of them do not comply with their Third-Party
Application policies, they will be modified or removed to stay compliant —
they are independent of, and not required by, the Riot API integration above.

### 🎨 Visual & Inventory
- Champion grid, skin showcase, dynamic account-card backgrounds (DDragon)

### 🔌 Connectivity & Servers
- Support for **Russia (RU)**, **Middle East (ME)**, and **Japan (JP)**
- Export/import your account list to transfer or back it up
- All data is stored locally on your machine

## Technologies
- **Electron**: Cross-platform desktop framework.
- **React + TypeScript**: Modern, type-safe UI development.
- **TailwindCSS**: Beautiful, responsive styling.
- **Riot Games API**: Account-V1, Summoner-V4, League-V4, Champion-Mastery-V4, Match-V5, Spectator-V5.
- **League Client Update (LCU) API**: local-only, powers the convenience tools described above.

## Disclaimer
This project is not endorsed by Riot Games and does not reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
