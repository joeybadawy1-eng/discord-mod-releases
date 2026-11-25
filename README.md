# Discord Mod releases

Installer and signed updates for Discord Mod, a small add-on for the Discord desktop app on Windows, made for a few friends. This repo only holds releases.

## Before you install: the ban risk

Client mods break Discord's terms of service. Discord very rarely bans anyone for mods like this, but the risk is never zero. The mod never sends messages or does anything on your account by itself, and several of its plugins make Discord send *less*.

## Install

1. Download **DiscordMod-Setup.exe** from the [latest release](../../releases/latest).
2. Run it. Windows may say "Windows protected your PC" because the file isn't signed by a company: click **More info**, then **Run anyway**.
3. Pick **1  Install or repair**. It closes Discord if needed and puts the mod in place.
4. In Discord, open Settings and scroll down to **Discord Mod** (or press Ctrl+Alt+D).

When Discord updates itself, the mod comes along automatically.

## Updates

In Discord: Settings → Discord Mod → Plugins → **Check for updates**. Updates are only installed if they're signed with the author's key, so nobody else can push code to you.

## Uninstall or safe mode

Run the installer again (a copy is kept at `%LOCALAPPDATA%\DiscordMod\DiscordMod-Setup.exe`) and pick **2  Uninstall** or **3  Start Discord in safe mode**.
