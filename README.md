# MC2FA
MC2FA is a **free** two-factor authentication plugin for Bukkit, Spigot & BungeeCord.

## Development Build
[![CircleCI](https://circleci.com/gh/ConnorLinfoot/MC2FA/tree/master.svg?style=svg)](https://api.connorlinfoot.com/v1/ci/artifact/MC2FA/latest/download)

## Features
- Designed to work out of the box. Just copy the plugin into your plugins folder and restart your server.
- Custom messages and prefix.
- In-game QR display using maps.
- Supports flat file, SQLite or MySQL for key storage. (SQLite and MySQL coming soon)
- Ability to force 2FA for players (or just OP)
- Disables tasks such as player movement, block breaking, chat, inventory changes etc.

## Planned
- BungeeCord support
- MySQL support
- Fallback key, allow players to be given a backup key in the case that they lose their 2FA device
- Admin commands, allow staff to view players with 2FA and disable if needed
- Auto-allow if on the same IP within a certain time (option)

## Requirements
- Bukkit/Spigot 1.8+
- Java 8+
