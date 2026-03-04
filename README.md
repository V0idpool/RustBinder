# RustBinder
![RustForge](https://img.shields.io/badge/version-1.0-red)
![Release](https://img.shields.io/badge/Release-3%2F3%2F2026-orange)

<img width="1024" height="683" alt="RfSplash" src="https://raw.githubusercontent.com/V0idpool/RustBinder/refs/heads/main/images/rustbinderbanner.png" />

RustBinder is an advanced console variable (ConVar) and keybind manager for Rust. Easily build, manage, and share custom command packs, and dynamically update your keys.cfg file on the fly without ever needing to open a text editor, with a live reload hotkey to update without ever needing to restart the game. Whether you are a dedicated base builder, an electrician, or a PvP chad, RustBinder lets you swap your entire F1 Console binding settings and control scheme in seconds.

## Support the Project:
RustBinder is a passion project that I hope to get on Steam as a Free-to-play app. If this tool saves you time and enhances your gameplay, consider supporting its ongoing development!

Buy Me A Coffee: [https://buymeacoffee.com/rustforgedev](https://buymeacoffee.com/rustforgedev) 

Join the VoidLabs RustForge Discord for Support & Pack Sharing: [https://discord.gg/tfwf9Qr7rG](https://discord.gg/tfwf9Qr7rG)

## Download & Resources
NexusMods Page: [https://www.nexusmods.com/rust/mods/13](https://www.nexusmods.com/rust/mods/13)

Full Commands & Binds Reference List: [https://github.com/V0idpool/RustBinder/blob/main/Commands/RustCommandList.md](https://github.com/V0idpool/RustBinder/blob/main/Commands/RustCommandList.md)

## The Command Pack System

* Modular Bind Profiles – Group your favorite console commands into custom .ini based Command Packs. Easily switch between **"Base Building Mode"**, **"Helicopter Flight Controls"**, or **"PvP Setup"** without manually typing commands in the F1 console or fiddling with files.
* Custom Command Pack Enable/Disable – Seamlessly toggle command packs on or off. Disabled packs are safely moved to a dedicated folder so they don't clutter your active binds, but remain ready to be reactivated with a single click.
* Export & Share – Built an amazing auto-crafter, crazy good bind setup, or builder bind setup? Export your custom Community Command Packs (including Author tags and descriptions) and share them with your clan or the Rust community.
* Command Pack Reload Integration – Dropped a new pack into your folder while the app was running? The reload system synchronizes your physical files with the app's memory instantly.

## Core Features

* Visual Bindings Manager: A clean, modern user interface to view, edit, and delete your standard Rust keybinds, and advanced binding options. No more digging through messy .cfg files.
* Native Modifier Freedom: RustBinder fully unlocks the modern Rust console engine. Apply **Toggle (~)**, **While Held (+)**, or **On Release (-)** modifiers to almost [i]any[/i] command or Cvar. Create complex multi-action macros, batched command executions, FOV aim-downs, or cycling "Dad Joke" chat binds with zero artificial restrictions.
* Auto-Backup System: Never lose your settings. This setting is on by default, RustBinder can automatically create timestamped backups of your keys.cfg file before applying any new saves & changes. (Useful if a mistake was made, and you need to recover from a prior file.)
* Binding Import/Export & Backup System: Easily import, export, save a backup, or load a backup of your entire keys.cfg to custom directories, it's easy to restore a previous backup if you accidentally mess up your game settings.
* Unsaved Changes Protection: Smart UI tracking prevents you from accidentally closing the Command Manager or the Main App while you have unsaved progress on your custom command packs. Never lose progress on accident!

## Advanced Settings & Customization
RustBinder gives you full control over how and where your data is managed:

* Custom Config Paths: Define exactly where your Community Command Packs and Backups are stored via the settings panel.
* Auto-Backup Toggle: Enable or disable the automatic .cfg backup feature to suit your preferences. (Enabled by default for safety)
* In-Game Reload Hotkey: Bind a custom hotkey **(Default: F9)** that you can press while actively playing Rust to instantly force the game to re-read your modified keys.cfg file without having to restart the game.

## How to Use
1. Launch the App: RustBinder will automatically attempt to locate your Rust installation via the Windows Registry to find your active keys.cfg.
2. Manage Binds: Use the main window to add, edit, or delete individual binds, or use the GUI to select **"Presets"** and **"Custom Command Pack Presets"**. Select the key, the command, and the bind type (Instant, Toggle, Hold, Release).
3. Build Command Packs: Open the "Command Packs" menu to start building categorized groups of commands. Add descriptions and metadata, then click "Save".
4. Toggle Packs: Use the checkboxes in the Command Pack list to enable or disable specific preset packs.
5. Save & Apply: Click "Save & Apply" on the main menu. RustBinder will generate a backup (if enabled) and inject your new binds directly into your game files.
6. Reload In-Game: If you have Rust open, simply press your designated "Reload CVars" hotkey to refresh your binds without restarting the game!

⌨️ Hotkeys
Reload CVars	F9	Prompts the Rust client to immediately reload the keys.cfg file and apply your new binds while in-game.
