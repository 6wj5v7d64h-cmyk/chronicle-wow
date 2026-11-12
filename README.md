# Chronicle – Weekly & PvE Tracker

**Your weekly progress. Your characters. Your PvE history. All in one place.**

Chronicle is a free World of Warcraft **Retail (Midnight)** addon by **jonas_gaming**. It helps you manage your Great Vault, weekly goals, alts, Mythic+ runs, and raid progress. The addon is available on [CurseForge](https://www.curseforge.com/wow/addons/chronicle-weekly-pve-tracker).

## Features

- **Great Vault** – nine reward slots for Dungeons, Raids, and World Activities.
- **Weekly goals** – required and optional goals, reusable templates, bonus reward tracking.
- **Characters & groups** – alts, favorites, color groups, and account-wide overview.
- **Mythic+** – season statistics, run history, dungeon/week filters, records.
- **Raids** – boss kills, difficulty filters, lockouts, recorded attempts and boss-health charts.
- **Bilingual** – English and German interface.
- **Data transfer** – manual import/export between WoW licenses.

## Chronicle Companion (optional)

**Chronicle Companion for Windows** adds automatic local synchronization between selected WoW licenses **on the same PC**. It supports a shared main settings profile and optional automatic synchronization, with a separate Diagnostics view.

**Compatibility note:** To ensure all features and reliable synchronization, keep both the Chronicle addon and Chronicle Companion up to date.

- **Local only:** the embedded API listens on `127.0.0.1:8765`.
- **No cloud account:** neither a website nor an external server is required.
- **Your choice:** enable only the WoW licenses you want to include.
- **In-game handover:** transferred data is picked up on login or `/reload`.
- **Windows 10/11 (64-bit):** download the Companion from this repository's **Releases** section *when a verified build has been published*.
- The addon itself works **without** the Companion.

> Companion releases are standalone Windows executables, not CurseForge addon files. An unsigned release may trigger Windows SmartScreen's unknown-publisher warning. Always use the official release page and verify the published SHA-256 checksum.

## Installation

1. Install the addon via [CurseForge](https://www.curseforge.com/wow/addons/chronicle-weekly-pve-tracker).
2. In WoW, open Chronicle using its minimap button or `/wc`.
3. *Optional:* once available, open a verified [Companion release](https://github.com/6wj5v7d64h-cmyk/chronicle-wow/releases), extract its ZIP, launch `ChronicleCompanion.exe`, select the WoW installation and licenses, and follow the setup wizard.
4. After a local sync, log in or run `/reload` to receive the transferred data.

## Important limitations

Historical Mythic+ runs and raid kill totals depend on data supplied by Blizzard. Detailed raid wipes and boss-health charts need encounters recorded while Chronicle is installed. Companion sync is **local to one PC**; synchronization across separate computers is not included.

## Support & community

- [CurseForge project](https://www.curseforge.com/wow/addons/chronicle-weekly-pve-tracker)
- [Discord support](https://discord.gg/RtHcNu3jBe)

## Deutsch

**Dein Wochenfortschritt. Deine Charaktere. Deine PvE-Chronik. Alles an einem Ort.**

Chronicle ist ein kostenloses WoW-Retail-Addon mit Großer Schatzkammer, Pflicht- und optionalen Wochenzielen, Charaktergruppen, Mythic+-Saisonhistorie und Raidstatistiken. Es funktioniert vollständig ohne Companion.

Der **optionale Chronicle Companion** für Windows 10/11 (64 Bit) synchronisiert Daten zwischen ausgewählten WoW-Lizenzen **auf demselben PC**. Die integrierte API arbeitet nur lokal (`127.0.0.1:8765`). Es gibt keine benötigte Website oder Cloud und kein externes Benutzerkonto. Nach dem Sync werden die Daten beim Login oder `/reload` übernommen. Die geprüften Windows-Downloads erscheinen hier unter **Releases**, sobald sie veröffentlicht wurden.

**Kompatibilitätshinweis:** Für den vollen Funktionsumfang und eine zuverlässige Synchronisierung bitte sowohl das Chronicle-Addon als auch den Chronicle Companion aktuell halten.

**Installation:** Addon über CurseForge installieren; anschließend optional die Companion-ZIP aus den GitHub-Releases entpacken, EXE starten, Lizenzen auswählen und die Einrichtung durchführen.

**Hinweis:** Eine nicht signierte EXE kann eine Windows-SmartScreen-Warnung auslösen. Prüfe Downloadquelle und SHA-256-Prüfsumme; deaktiviere Sicherheitseinstellungen nicht global.

## License

Copyright © 2026 jonas_gaming. **All Rights Reserved.**

This repository provides project information and release downloads. No permission to redistribute, repackage, modify, or relicense Chronicle's original code/assets is granted by this page. World of Warcraft and related trademarks are the property of Blizzard Entertainment; Chronicle is unofficial and independent.

See [License and trademarks](LICENSE-NOTICE.md) for details.
