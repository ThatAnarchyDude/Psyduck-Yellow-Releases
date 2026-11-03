# Pokémon Psyduck Yellow — Releases

Downloads for **Pokémon Psyduck Yellow**, an unofficial fan project that rebuilds Pokémon Yellow's Kanto campaign inside Pokémon HeartGold (starting Psyduck / Togepi / Eevee, Mega Evolution for the starters, and more).

> ## ⚠️ BETA — FOR TESTING ONLY
> The newest release (**BETA 0.1.61, prototype 0161**) is for testing. **It is NOT a complete game.**
> The **Kanto campaign (Pallet Town to your first Hall of Fame)** is built, and the **first parts of the Johto postgame** are in,
> but **Johto is unfinished and has not been played through.** Expect bugs, including softlocks.

## The game in plain words
Psyduck Yellow retells **Pokémon Yellow's Kanto story inside Pokémon HeartGold**. You start with **Psyduck, Togepi or Eevee**; Psyduck and Eevee can **Mega Evolve**; and Kanto's towns, gyms, Team Rocket plots, Elite Four and Champion Blue follow Yellow's teams and dialogue. The goal of this project is a finished Kanto adventure from Pallet Town to the first Hall of Fame; Johto (HeartGold's own region) is meant to come later as a postgame.

## Where it stands right now (BETA 0.1.61, prototype 0161)
- **Built:** Pallet Town through Vermilion, Pokémon Tower, Celadon and the Rocket Hideout, Routes 8 and 11–18, Fuchsia, Saffron (with Silph Co.), Seafoam and Viridian gyms, Route 22, Victory Road, the Indigo Plateau League and the Hall of Fame.
- **Played by the developer:** New Game through Cerulean on earlier builds. Everything after Cerulean, and all of the Johto postgame, has only had small emulator tests on prepared saves, so expect bugs, including softlocks.
- **New in 0050:** your starter Eevee can evolve into all eight Eeveelutions and the new Stellar-type **Novareon** (use a Sandwich), each with its own Mega Evolution; plus fixes for the starters' evolution screen, summary sprites and Mega colours.
- **New in 0056:** the Pokédex opens on Kanto (1-151) with real National numbers for the starter Pokémon; TM34 is Moonblast and TM58 is Dazzling Gleam.
- **New in 0081:** Novareon's own Pokédex entry and follower, Mega Novareon art, Champion Blue, item balls in Silph Co., the Tower, the Rocket Hideout and Victory Road, Moltres, and fixes for trainer teams, the Game Corner and the Silph exit.
- **New in 0105:** Pokémon Tower, Mt. Moon, Rock Tunnel, Rocket Hideout, Silph Co., the Pokémon Mansion, Viridian Gym, Victory Road and the Safari Zone rebuilt from Yellow's maps with their puzzles; a black-screen fix in Vermilion's Pokémon Center; a Pokédex registration fix.
- **New in 0110:** the VS banners name the Elite Four and Champion Blue, Strength works with Kanto badges, Victory Road has real boulders, visible switches and Yellow's first-switch puzzle on 2F, and Novareon counts on the Trainer Card.
- **New in 0161:** a New Game starts with the Kanto Pokédex (no National switch); Oak upgrades it to the National Pokédex later in the Johto postgame.
- **New in 0160:** replaces 0158 (and 0157): the Town Map and Fly map stay Kanto-only until Elm's call even if the game already set New Bark Town's Fly point, and walking into Pallet Town no longer unlocks it.
- **New in 0158:** replaces 0157, which crashed in battle (a Town Map change had overwritten a battle routine); same features as 0157, fixed.
- **New in 0157:** the redesigned Eevee/Psyduck starter line (nine new Eeveelutions, Stellareon), the Town Map that shows only Kanto until you reach Johto, the first parts of the Johto postgame (S.S. Aqua, Elm, the Mega Ring, Mr. Pokémon), Johto difficulty that scales with your Johto badges, the Johto League and Red, shared Kanto Mart stock, a Rare Candy move-learning fix, ladder and warp art in the caves, and 3DS crash fixes.
- **Not built yet:** elevator floor menus (stairs for now), some stand-in textures, some Game Corner and Department Store extras, and **most of Johto** (only the postgame steps above exist, and they have not been played through).


## Play it
1. Open the latest page from the [Releases](../../releases) section (or the [hosted BETA 0.1.61 patching page](https://raw.githack.com/Doctor-Pokemon/Psyduck-Yellow-Releases/main/prototype-0161/index.html)).
2. Select your **own, original, unmodified USA HeartGold `.nds`**.
3. Click *Create my playable NDS*, wait for verification, then download it and load it in your DS emulator.
4. Start a **New Game**. Saves from older prototypes are not supported.

Nothing is uploaded: the patching runs in your browser and every stage is hash-checked.

## What is (and isn't) here
- Patches, patching pages and notes only. **No ROMs, saves or game files are distributed.** You must supply your own legally obtained game.
- Releases are experimental prototypes. Each release's notes say what has and has not been played.
- Source for the patches and the development log live in [corvus-workshop](https://github.com/ThatAnarchyDude/corvus-workshop).

## Licence
The text and documentation in this repository are released under **CC BY-NC-SA 4.0** (see `LICENSE`). The game patches modify a Nintendo game and are not covered by that licence; use them only with your own copy of the game, for non-commercial purposes.

This is an unofficial fan project. It is not affiliated with or endorsed by Nintendo, Game Freak, Creatures or The Pokémon Company. Pokémon and related names are trademarks of their owners.

## Credits
- [hg-engine](https://github.com/BluRosie/hg-engine) by BluRosie and contributors
- RomPatcher.js (patch decoder in the patching page) by Marc Robledo, MIT licence
- Pokémon Yellow's data and layout reference from the [pret/pokeyellow](https://github.com/pret/pokeyellow) disassembly

## Release history (newest first)
- **BETA 0.1.61 (prototype 0161) — November 3, 2026 (beta, testing only).** A New Game starts with the Kanto Pokédex instead of the National one (Oak upgrades it in the Johto postgame). Everything else as in 0.1.60. Kanto complete to the first Hall of Fame; Johto unfinished.
- **BETA 0.1.60 (prototype 0160) — November 3, 2026 (beta, testing only).** Replaces 0.1.58 and 0.1.57: the Town Map and Fly map stay Kanto-only until Elm calls in Johto (0.1.58 could still be scrolled into Johto right after getting the Pokégear), and Pallet Town no longer unlocks New Bark Town's Fly point. Everything else as in 0.1.58. Kanto complete to the first Hall of Fame; Johto unfinished.
- **BETA 0.1.58 (prototype 0158) — November 3, 2026 — SUPERSEDED, the Town Map lock can be bypassed; use 0.1.60.** Replaces 0.1.57, which crashed in battle: the first move you used froze the game. Everything from 0.1.57 (Town Map that shows only Kanto until Johto, first parts of the Johto postgame, redesigned Eevee/Psyduck starters, shared Kanto Mart stock) is in this build. Kanto complete to the first Hall of Fame; Johto unfinished.
- **BETA 0.1.57 (prototype 0157) — November 3, 2026 — SUPERSEDED, crashes in battle; use 0.1.58.** Redesigned Eevee/Psyduck starter line, the Town Map that shows only Kanto until Johto, the first parts of the Johto postgame (S.S. Aqua, Elm, Mega Ring), Johto levels that scale with your badges, the Johto League and Red, shared Kanto Mart stock, a Rare Candy fix, cave warp art and 3DS crash fixes. Kanto complete to the first Hall of Fame; Johto unfinished.
- **0110 BETA — October 28, 2026 (pre-release, testing only).** The VS banners name the Elite Four and Champion Blue, Strength works with Kanto badges, Victory Road has real Strength boulders, visible switches and Yellow’s puzzle, and Novareon counts on the Trainer Card. Kanto only; Johto not ready.
- **0105 BETA — October 26, 2026 (pre-release, testing only).** Nine Kanto dungeons and gyms rebuilt from Yellow’s maps (Pokémon Tower, Mt. Moon, Rock Tunnel, Rocket Hideout, Silph Co., Mansion, Viridian Gym, Victory Road, Safari Zone), a Vermilion black-screen fix and a Pokédex fix. Kanto only; Johto not ready.
- **0086 BETA — October 24, 2026 (pre-release, testing only).** Recolored Pokémon Tower, Oak’s Hall of Fame speech, trainer sprite fixes, Sandwich description, Route 25 Camper sight. Kanto only; Johto not ready.
- **0081 BETA — October 24, 2026 (pre-release, testing only).** Novareon Pokédex entry/follower, Mega Novareon art, Champion Blue, dungeon item balls and Moltres, trainer-team/Game Corner/Silph fixes. Kanto only; Johto not ready.
- **0056 BETA — October 23, 2026 (pre-release, testing only).** Pokédex opens on Kanto with real National numbers for the starters; Moonblast and Dazzling Gleam TMs; Fairy-move fixes. Kanto only; Johto not ready.
- **0050 BETA — October 22, 2026 (pre-release, testing only).** The starter Eevee line: all eight Eeveelutions plus the new Stellar-type Novareon (Sandwich), each with its own Mega; new Stellar, Sandwich and Novareon images; fixes for the starters' evolution screen, summary sprites and Mega colours. Kanto only; Johto not ready.
- **0042 BETA — October 22, 2026 (pre-release, testing only).** Silph Co., Victory Road, the second Route 22 rival battle, the Route 22 badge gate, and the way to the League and Hall of Fame. Kanto only; Johto not ready.
- **0041 EXPERIMENTAL — October 22, 2026.** Pokémon Tower, Celadon Gym, Rocket Hideout, Routes 8 and 11–18, the Fuchsia/Saffron/Seafoam/Viridian gyms, the Indigo League, Mega Psyduck and the free Mega Stones.
- Earlier prototypes (0016–0039) built the opening, starters, Pewter/Cerulean and the engine base; see the full dated list in [DEVELOPMENT-LOG.md](DEVELOPMENT-LOG.md).
