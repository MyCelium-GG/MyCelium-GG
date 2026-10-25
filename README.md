# 🍄 MyCelium

Tiny Minecraft mods with big charm, all growing on one shared core.

![Minecraft](https://img.shields.io/badge/Minecraft-26.3-d32f2f)
![Java](https://img.shields.io/badge/Java-25-d32f2f)
![Loaders](https://img.shields.io/badge/Loaders-Fabric_%7C_Forge_%7C_NeoForge-d32f2f)
![License](https://img.shields.io/badge/License-MIT-b71c1c)

🌐 **Home:** [mycelium-gg.org](https://mycelium-gg.org) · 📖 **Wiki:** [wiki.mycelium-gg.org](https://wiki.mycelium-gg.org) · 🧩 **API docs:** [api.mycelium-gg.org](https://api.mycelium-gg.org) · 💬 **Discord:** [join](https://discord.gg/8qgVgy526)

## What we grow

| Mod | What it does | Side | Get it |
|---|---|---|---|
| [InstantXP](https://github.com/MyCelium-GG/Instant-XP) | Nearby XP orbs are picked up every tick through vanilla's own path, so Mending, sounds and stats stay intact. | Server | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/instant-xp-pickup) |
| [AutoBlockRefiller](https://github.com/MyCelium-GG/Auto-Block-Filler) | Refills the hotbar slot you just emptied by placing a block, from the rest of your inventory. | Server | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/auto-block-refiller) |
| [Better Librarians](https://github.com/MyCelium-GG/Better-Librarians) | Look at a librarian, see their books, plus colorful floating villager names with `/vname`. | Client | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/better-librarians) |
| [ItemHighlighter](https://github.com/MyCelium-GG/Item-Highlighter) | Give any item a color and spot it instantly: glowing outline, tinted slots and a colored tooltip line. Set per item with `/hl`. | Client | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/item-highlighter-mod) |
| [Anvil Cost Calculator](https://github.com/MyCelium-GG/Anvil-Cost-Calculator) | Know the XP before you pay: a planner finds the cheapest order to apply your enchantments, with per-step and total costs. | Client | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/anvil-cost-calculator) |
| [Brewing+](https://github.com/MyCelium-GG/Brewing-Plus) | A guide on the brewing stand: every potion's recipe, what you're missing, and the next ingredient right in the stand. | Client | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/brewing-plus) |
| [BedrockPlacing](https://github.com/MyCelium-GG/Bedrock-Placing) | Place blocks Bedrock-style: right-click the air to extend the block you stand on, no precise face click needed. | Server | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/bedrock-placing) |
| [Better Pets](https://github.com/MyCelium-GG/Better-Pets) | List every pet with its location (even in unloaded chunks), find it with a glow and compass, call it, rename it, give it away, and walk it on a lead that never snaps. | Server | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/better-pets) |
| [Better Server List](https://github.com/MyCelium-GG/Better-Server-List) | The multiplayer screen, organized: several lists, folding categories, pinned favorites, search and drag and drop. | Client | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/better-server-list) |
| [More Beacon Colors](https://github.com/MyCelium-GG/More-Beacon-Colors) | Any color for your beacon beam: dye colors, gradients through up to 16 colors, rainbows, color cycles and pulses. | Both | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/more-beacon-colors) |
| [Colored Nether Portals](https://github.com/MyCelium-GG/Colored-Nether-Portals) | Any color for your Nether portals: dyes, smooth gradients, rainbows, color cycles and pulses, with matching particles. | Both | [Docs](https://wiki.mycelium-gg.org/colorednetherportals/) |

## The core: Mycel

[Mycel](https://github.com/MyCelium-GG/MyCel-Lib) is the shared library behind every mod: configs with an in-game
screen and `/mycel` commands, events, networking, scheduling, safe data files, an update checker and support dumps.
One universal jar for Fabric, Forge and NeoForge, documented at [api.mycelium-gg.org](https://api.mycelium-gg.org).
[![Release](https://jitpack.io/v/MyCelium-GG/MyCel-Lib.svg)](https://jitpack.io/#MyCelium-GG/MyCel-Lib) · [CurseForge](https://www.curseforge.com/minecraft/mc-mods/mycel)

## How it works

Small mods stay small because the boring infrastructure lives in Mycel.
One codebase builds for all three loaders, and every Mycel change is started on all three in CI
(a dev server and a client trading packets) before it ships. Server-side mods work with vanilla clients.

Want to help? See the [contributing guide](https://github.com/MyCelium-GG/.github/blob/main/CONTRIBUTING.md).

Not affiliated with Mojang or Microsoft.
