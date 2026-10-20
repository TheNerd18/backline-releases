# Backline releases

Installers and auto-update files for the **Backline** desktop app (macOS and Windows).

This repository holds **release binaries only, no source code**. Each [release](https://github.com/TheNerd18/backline-releases/releases) is published automatically by the app's build pipeline and contains:

- macOS: `Backline_<version>_universal.dmg` (installer) and `Backline.app.tar.gz` + `.sig` (update bundle and its signature)
- Windows: `Backline_<version>_x64-setup.exe` / `.msi` (installers) and their `.sig` files
- `latest.json`: update manifest

The app checks for updates through the Backline website, which reads these releases. Every update is signed; the app refuses anything not signed with Backline's update key.

Download Backline from the website's Download page. Licensing and support are on the website.
