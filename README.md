# Retired KoL Scripts

Historical home for standalone Kingdom of Loathing / KoLmafia scripts from [donCannoli-burns](https://github.com/donCannoli-burns) whose maintained functionality has been consolidated elsewhere.

> **Status (2026-10-30): preparation only.** This repository is currently a retirement index, **not** a migrated code archive. The three repositories below are planned for consolidation here in approximately 30 days (late November 2026). No code has been moved or original repository archived by this notice. Check the original repositories for their current status.

## Maintained replacements

**For new installs and ongoing maintenance, use:**

- **[don_custom_functions](https://github.com/donCannoli-burns/don_custom_functions)** — maintained, runnable KoLmafia ASH commands and relay scripts.
- **[don-ash-lib](https://github.com/donCannoli-burns/don-ash-lib)** — reusable, import-safe ASH modules and supporting helpers.

## Planned retirement queue

| Original repository | Maintained home | Historical purpose |
| --- | --- | --- |
| [boneFarm](https://github.com/donCannoli-burns/boneFarm) | `don_custom_functions/scripts/boneFarm.ash` and `don-ash-lib` bone helpers | Skeleton of Crimbo Past knucklebone farming |
| [boneTrack.ash](https://github.com/donCannoli-burns/boneTrack.ash) | `don_custom_functions/scripts/boneTrack.ash`, `relay/relay_BoneTrack.ash`, and shared `don-ash-lib` helpers | Knucklebone and daily-special tracking |
| [codMaster](https://github.com/donCannoli-burns/codMaster) | `don_custom_functions/scripts/codMaster.ash` and `don-ash-lib/don-master-ash-lib/scripts/don_codmaster_lib.ash` | Eternity Codpiece gem presets, saving and equipping |

The original repos remain available as historical references while the transition is underway. Any eventual code import should preserve provenance, notices, and historical documentation. This index does not assert that the files have already been copied here.

## Migration notes

1. In KoLmafia, run `git list` to find any legacy checkouts.
2. Back up locally edited scripts and player-specific data **before** changing installed sources.
3. Install/update [don-ash-lib](https://github.com/donCannoli-burns/don-ash-lib) and [don_custom_functions](https://github.com/donCannoli-burns/don_custom_functions), then run the `verify` and smoke-test commands documented in the maintained READMEs.
4. **Only after verification**, remove redundant old checkouts that install the same `.ash` filename. Two Git checkouts owning the same KoLmafia path can conflict.

Keep `data/boneTrack/` and `data/cod_master/saves/` (including `spell.txt`); they contain player-specific history or saved configurations and are **not** disposable legacy scripts. The maintained CodMaster keeps the `data/cod_master/saves/<name>.txt` format.

## Archival policy

This project is an archive destination, **not** the supported installation source. Planned timing is approximate and subject to checking preservation and migration. Historical material will remain credited to its original authors. The active libraries above are the authoritative destinations for continuing improvements.
