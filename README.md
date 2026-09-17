<img width="1513" height="895" alt="Screenshot 2026-09-16 162647" src="https://github.com/user-attachments/assets/e8fc72aa-95a1-48e6-b8be-b0caf15086b1" />
<img width="1493" height="901" alt="Screenshot 2026-09-16 162417" src="https://github.com/user-attachments/assets/8e0cbaa0-b693-47ef-9bfd-952bd4441e4d" />
<img width="1526" height="887" alt="Screenshot 2026-09-16 162350" src="https://github.com/user-attachments/assets/324b51a6-9c92-410c-aae7-56ca7d181153" />
<img width="1473" height="912" alt="Screenshot 2026-09-16 162321" src="https://github.com/user-attachments/assets/18e191db-2d26-441b-ba9b-09a76baaf2cd" />
<img width="1497" height="897" alt="Screenshot 2026-09-16 162252" src="https://github.com/user-attachments/assets/2f8398bf-dc70-497e-b91c-740ffd0614e1" />
<img width="1522" height="862" alt="Screenshot 2026-09-16 162233" src="https://github.com/user-attachments/assets/55fa18f5-0b19-47d0-9170-b27f6b159354" />
<img width="1528" height="910" alt="Screenshot 2026-09-16 162210" src="https://github.com/user-attachments/assets/61dec5ba-29a2-40b7-bcd5-7ea19d3b3b24" />
# SS+ Ark Server Manager

A free Windows desktop app for installing and managing your own ARK: Survival Ascended dedicated server — no more hand-editing config files or juggling command-line flags.

## Features

- **Install & Setup** — installs SteamCMD and the ASA dedicated server for you, with live progress
- **Dashboard** — start / stop / restart your server, live CPU & memory graphs, uptime tracking
- **Server Control** — name, map, ports, passwords, crossplay, and cluster settings
- **Configuration** — a full visual editor for `GameUserSettings.ini` and `Game.ini` (rates, stats, structures, breeding, PvP, and much more), plus a raw editor for anything not covered
- **Mod Manager** — add mods by CurseForge project ID (with optional API key for auto name/author lookup), reorder, enable/disable, mark mods passive
- **Console & RCON** — live server log, send RCON commands, quick actions (save world, dino wipe, broadcast)
- **Backup Manager** — create/restore backups, automatic retention cleanup
- **Scheduler** — recurring tasks (backups, restarts with a player warning broadcast, dino wipes, custom RCON commands, updates)
- **Integrations** — Discord webhook notifications, whitelist & ban list management
- **Multiple servers** — manage several server profiles, each with its own settings, mods, and config

## Requirements

- Windows 10 or 11
- ~40 GB free disk space for the ARK server files

## Installation

1. Go to the [Releases](../../releases) page
2. Download the latest `.exe`
3. Run it and follow the installer

**Note:** Windows may show a SmartScreen warning since this isn't code-signed. Click **"More info"** → **"Run anyway"** to continue.

## Getting Started

1. Open the app and create a new server profile
2. Go to **Install & Setup** to download SteamCMD and the ARK server files
3. Configure your server in **Server Control** and **Configuration**
4. Hit **Start Server** from the Dashboard

## Important Notes

- ARK only reads its configuration files when the server starts, and overwrites them with its own state on shutdown — always make config changes while the server is **stopped**.
- RCON authentication uses your server's **Admin Password** — ARK doesn't have a separate RCON password.
- If you can't join your own server ("connection timeout"), check that **Exclusive Join** isn't enabled without your account added to the whitelist.
  ## Bug Reports & Support

Found a bug or need help? Join the Discord: https://discord.gg/6vCZu4Bzyx 

## Disclaimer

This is an independent, unofficial project. It is not affiliated with Studio Wildcard, Snail Games, Valve, or CurseForge.
