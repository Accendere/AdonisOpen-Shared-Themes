# AdonisOpen-Shared-Themes

Shared theme resources (colors, SVG icons, texts, and localizations) for **Adonis Open**.

> **Note on Fork & Upstream**:  
> This repository is a fork of [linhome-shared-themes](https://gitlab.linphone.org/BC/public/linhome-shared-themes) developed by [Belledonne Communications SARL](https://www.belledonne-communications.com/).  
> Added as a git submodule to [AdonisOpen-Android](https://github.com/Accendere/AdonisOpen-Android) and related apps, and used at build time to package application themes.

---

## License & Attribution

Copyright © 2010–2025 Belledonne Communications SARL  
Modifications Copyright © 2026 Adonis Open Contributors

This project is licensed under the **GNU General Public License v3 (GPLv3)**. Please see the [LICENSE](LICENSE) and [NOTICE](NOTICE) files for full details.

- **GNU General Public License v3**: https://www.gnu.org/licenses/gpl-3.0.html
- **Upstream Project**: https://gitlab.linphone.org/BC/public/linhome-shared-themes

*Linhome and Linphone are registered trademarks of Belledonne Communications SARL. Adonis Open is an independent open-source project and is not affiliated with, endorsed by, or sponsored by Belledonne Communications.*

---

## Deploying to Android

From the `AdonisOpen-Android/` repository:
```bash
git submodule update --remote AdonisOpen-Shared-Themes
# Rebuild the project
./gradlew zipTheme assembleDebug
```
