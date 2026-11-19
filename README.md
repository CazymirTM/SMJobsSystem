# SMJobsSystem

Jobs, XP levels and perks for **Scrap Mechanic Survival**, built on
[SMLoader](https://github.com/CazymirTM/SMLoader). Pick a job, level it from
1 to 50, and unlock new perks as you go. It's co-op friendly.

> Requires **SMLoader 1.1.0+** · Scrap Mechanic **1.0.7a** (Steam, Windows x64) ·
> Survival only · **every player in the world needs it**

## How it works

- **One job at a time.** XP is kept for every job, so switching never loses
  progress.
- **Levels 1–50.** Every level makes the job's bonuses stronger, and milestone
  levels unlock new perks.
- **Press J** for the jobs menu. Your **XP bar sits under the compass**, with
  "+XP" pop-ups and a level-up banner.
- **Host XP multiplier (1–10×):** the host of the world can speed up levelling
  for everyone in the *Host* tab. It's saved with the world.
- **Co-op check:** if someone in the world doesn't have SMJobsSystem (or has a
  different version), jobs pause for everyone, and the menu names who it is.
  It uses SMLoader's built-in SMNetworking.
- **Saved in the world.** Each player's job and XP live in the world's save
  file, next to their inventory, so progress is per world.

## Jobs

### ⛏ Miner — *break stone chunks with your sledgehammer*
| Level | Perk |
|---|---|
| 1 | +2% mining damage per level (up to +98%) |
| 1 | +1% chance per level for a bonus stone/metal drop (up to 50%) |
| 10 | **Metal Sense**: bonus drops are metal half the time |
| 25 | **Crushing Blow**: 10% chance to deal triple damage |
| 40 | **Motherlode**: a second bonus drop roll |

### 🛠 Engineer — *collect finished items from a Craftbot or Workbench*
| Level | Perk |
|---|---|
| 1 | +1% chance per level to receive crafted items twice (up to 50%) |
| 10 | **Supply Crate**: claim 3 component kits + 50 metal blocks every 20 min |
| 15 | **Efficient Crafting**: +10% double-craft chance |
| 25 | Bigger crate: 6 kits, 100 metal + 50 wood blocks |
| 30 | **Master Crafter**: +15% double-craft chance |
| 40 | Huge crate: 10 kits, 200 metal + 100 wood blocks |

### 🌱 Farmer — *harvest ripe crops*
| Level | Perk |
|---|---|
| 1 | +2% chance per level for a double harvest (up to 100%) |
| 5 | **Seed Saver**: +1 seed with every harvest |
| 15 | **Green Thumb**: also harvests ripe crops within 1.5 m |
| 30 | Harvest radius 3 m |
| 45 | Harvest radius 5 m |

### 🛡 Warrior — *defeat robots (tougher robots give more XP)*
| Level | Perk |
|---|---|
| 1 | +2% damage to robots per level (up to +98%) |
| 10 | **Thick Skin**: take 10% less damage |
| 20 | **Lifesteal**: heal 5% of the damage you deal |
| 25 | Thick Skin II: take 20% less damage |
| 30 | **Critical Hits**: 10% chance to deal double damage |
| 35 | Lifesteal II: heal 10% of the damage you deal |
| 40 | Thick Skin III: take 30% less damage |

### 🔧 Mechanic — *drive vehicles: hold the controls of a seat that powers an engine*
| Level | Perk |
|---|---|
| 1 | +1% engine power per level while you drive (up to +50%) |
| 1 | +1% gasoline/battery savings per level (up to 50%) |
| 15 | **Spare Parts**: claim 5 gasoline + 2 batteries every 20 min |
| 30 | Bigger kit: 10 gasoline + 5 batteries |
| 45 | Full kit: 20 gasoline, 10 batteries + 2 circuit boards |

### 💰 Merchant — *trade at the Hideout trader and buy from your shop*
| Level | Perk |
|---|---|
| 1 | +1% more items from Hideout trades per level (up to +50%) |
| 1+ | **Merchant Shop**: exclusive items for component kits, unlocking as you level (glowsticks, fertilizer, sunshakes, soil bags, pizza burgers, circuit boards, revival baguettes, keycards, power cores) |

## Install

1. Install [SMLoader](https://github.com/CazymirTM/SMLoader/releases) 1.1.0 or
   newer. Every player in your world needs it.
2. Download `SMJobsSystem-v1.1.zip` from **Releases**.
3. Copy its `SMLoader` folder into your game folder and let it merge.
4. Load a Survival world, press **J** and pick a job.

**Uninstall:** delete `SMLoader\mods\SMJobsSystem.dll` and the
`SMLoader\SMJobsSystem` folder. Job progress stays in your world saves, unused,
and comes back if you reinstall.

## Good to know

- All job logic runs on the **host**, so the host's copy decides the rules.
- Perks build on the game's own code instead of replacing it, and they fail
  safely: if something goes wrong in SMJobsSystem, vanilla gameplay keeps
  working.
- Back up your world before trying any mod.

## Bugs and suggestions

Open an [issue](https://github.com/CazymirTM/SMJobsSystem/issues). Please
include your `SMLoader\SMLoader.log`.

## License

SMJobsSystem is **closed-source freeware**: free to use, but no re-uploads,
modified versions or reverse engineering. See [LICENSE](LICENSE). Please share
the link to this page instead of the zip.

The bundled open-source components (Dear ImGui, Inter, JetBrains Mono and
Font Awesome Free) keep their own licences: see
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

*Not affiliated with or endorsed by Axolot Games.*
