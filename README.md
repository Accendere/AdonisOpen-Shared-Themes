# AdonisOpen-Shared-Themes

Shared theme resources (colors, SVG icons, texts, and localizations) for Adonis Open.

> **Note**: This repository is a fork of [linhome-shared-themes](https://gitlab.linphone.org/BC/public/linhome-shared-themes) by Belledonne Communications.

Added as a git submodule to AdonisOpen-Android and related apps. Used at build time to package application themes.

### Deploy Android:
From the `AdonisOpen-Android/` repository:
```bash
git submodule update --remote AdonisOpen-Shared-Themes
# Rebuild the project
./gradlew zipTheme assembleDebug
```
