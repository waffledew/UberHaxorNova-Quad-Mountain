# v0.1.2-alpha — Quad Island Survival world update

This pre-release adds the preserved Quad Island Survival world to the corrected MultiMC import package from v0.1.1-alpha.

## Added

- `.minecraft/saves/Quad Island Survival/` as a ready-to-play Minecraft 1.1 world.
- `.minecraft/saves/Quad Island Survival.rar` as the preserved original world archive.
- Overworld, Nether, and End region data from the archived save.

Minecraft ignores the RAR file and loads the extracted world folder normally. The archive is included for preservation and comparison.

## Installation

Download `UberHaxorNova-Quad-Mountain-MultiMC-v0.1.2-alpha.zip`, then choose **MultiMC → Add Instance → Import from ZIP**. Use Java 8 for the best Minecraft 1.1 compatibility. The world should appear in the Singleplayer menu.

## Verification

- SHA-256: `A72D6F73A7ECA0AF2B6A08AFD94780244C4BD26D6D75EA23466E83B3D6402FCA`
- Microsoft Defender custom scan: no threats found on 2026-07-15.
- Archive inspection: 1,290 entries, all inside one instance folder.
- The only included save is `Quad Island Survival`; no account, statistic, screenshot, gameplay log, or development directory is included.

Security scanning cannot prove that every historical binary is bug-free. Treat this as an alpha preservation build and report reproducible problems through GitHub Issues.
