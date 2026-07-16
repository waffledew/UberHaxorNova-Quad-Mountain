# Security

## Reporting a concern

Do not post account tokens, launcher credentials, private crash reports, or other sensitive information in a public issue. Describe the concern without secrets and contact the repository owner privately if disclosure would put users at risk.

## Alpha ZIP verification

The `v1.2.0` MultiMC ZIP was checked before release:

- Microsoft Defender custom scan: no threats found on 2026-07-15.
- No Minecraft account, statistic, screenshot, gameplay log, or development folder was found in the archive.
- The only included save is the intentionally distributed `Quad Island Survival` world, provided as an extracted folder and original RAR.
- Archive structure: 1,290 entries contained within one `UberHaxorNova Quad Mountain` instance folder.
- Published SHA-256: `A72D6F73A7ECA0AF2B6A08AFD94780244C4BD26D6D75EA23466E83B3D6402FCA`

A clean scan is useful evidence but not an absolute guarantee. This project combines historical software from many sources; use the alpha build with appropriate caution and report reproducible concerns.
