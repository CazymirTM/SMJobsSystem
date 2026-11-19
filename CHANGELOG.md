# Changelog

## 1.1

- Multiplayer now runs on SMLoader's built-in **SMNetworking**: the co-op
  check, host settings and menu requests. Requires **SMLoader 1.1.0+**.
- Players with a different SMJobsSystem version are now detected and named,
  and jobs pause until everyone matches.
- Host settings (pause state, XP multiplier) reach players who join late right
  away.
- SMJobsSystem no longer wraps the game's own tick function, so it can't clash
  with other mods that hook the same function.
- Your saved jobs and XP carry over unchanged.

## 1.0 — first public release

- Six jobs: Miner, Engineer, Farmer, Warrior, Mechanic and Merchant.
  Levels 1–50, with scaling bonuses and milestone perks.
- One job at a time; XP is kept per job.
- Jobs menu on J. XP bar under the compass, with +XP pop-ups and a level-up
  banner.
- Host-only XP multiplier (1–10×), saved with the world.
- Co-op handshake: jobs pause for everyone if a player in the world doesn't
  have the mod.
- Progress is saved per player inside the world save.
- Survival only.
