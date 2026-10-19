# 🍄 MyCelium

Tiny Minecraft mods with big charm, all growing on one shared core.

![Minecraft](https://img.shields.io/badge/Minecraft-26.3-d32f2f)
![Java](https://img.shields.io/badge/Java-25-d32f2f)
![Loaders](https://img.shields.io/badge/Loaders-Fabric_%7C_Forge_%7C_NeoForge-d32f2f)
![License](https://img.shields.io/badge/License-MIT-b71c1c)

📖 **Wiki:** [wiki.mycelium-gg.org](https://wiki.mycelium-gg.org) · guides, configs, commands and changelogs for every mod.

## What we grow

| Mod | What it does | Side | Get it |
|---|---|---|---|
| [Better Pets](https://github.com/MyCelium-GG/Better-Pets) | List every pet with its location (even in unloaded chunks), find it with a glow and compass, call it, rename it, give it away, and walk it on a lead that never snaps. | Server | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/better-pets) |
| [Anvil Cost Calculator](https://github.com/MyCelium-GG/Anvil-Cost-Calculator) | Know the XP before you pay: a planner finds the cheapest order to apply your enchantments, with per-step and total costs. | Client | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/anvil-cost-calculator) |
| [Item Highlighter](https://github.com/MyCelium-GG/Item-Highlighter) | Give any item a color and spot it instantly: glowing outline, tinted slots and a colored tooltip line. Set per item with `/hl`. | Client | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/item-highlighter-mod) |
| [Better Librarians](https://github.com/MyCelium-GG/Better-Librarians) | Look at a librarian, see their books, plus colorful floating villager names with `/vname`. | Client | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/better-librarians) |
| [Instant XP](https://github.com/MyCelium-GG/Instant-XP) | Nearby XP orbs are picked up every tick through vanilla's own path, so Mending, sounds and stats stay intact. | Server | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/instant-xp-pickup) |
| [AutoBlockRefiller](https://github.com/MyCelium-GG/Auto-Block-Filler) | Refills the hotbar slot you just emptied by placing a block, from the rest of your inventory. | Both | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/auto-block-refiller) |
| [Bedrock Placing](https://github.com/MyCelium-GG/Bedrock-Placing) | Place blocks Bedrock-style: right-click the air to extend the block you stand on, no precise face click needed. | Both | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/bedrock-placing) |
| [Trader Alert](https://github.com/MyCelium-GG/Trader-Alert) | Never miss the Wandering Trader: arrival alerts, location, leave warnings and `/trader find`. In development. | Server | Soon |

## The core: Mycel

[Mycel](https://github.com/MyCelium-GG/MyCel-Lib) is the shared library behind every mod: config with an in-game screen,
utilities, events, networking, translations, scheduling and an update checker. One universal jar for
Fabric, Forge and NeoForge. [![Release](https://jitpack.io/v/MyCelium-GG/MyCel-Lib.svg)](https://jitpack.io/#MyCelium-GG/MyCel-Lib) · [CurseForge](https://www.curseforge.com/minecraft/mc-mods/mycel)

## How it works

Small mods stay small because the boring infrastructure lives in Mycel.
One codebase builds for all three loaders, and every release is playtested
on dedicated servers before it ships. Server-side mods work with vanilla clients.

Not affiliated with Mojang or Microsoft.
