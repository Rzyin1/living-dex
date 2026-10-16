# The Living Dex

A fan-made, personal National Living Pokédex tracker for GitHub Pages, including:

- 1,025 species in National Dex order (species names from PokéAPI, with Generation 1 available on first launch)
- Generation filters, search, collected/missing filters, and progress metrics
- Individual Pokémon nicknames, game, physical storage location, and notes
- Optional challenge-based encounter unlocks
- GameShark encounter codes for all 151 Generation 1 species in English Pokémon Red/Blue (codes are **not** National Dex numbers)
- Export/import JSON backups, with local browser storage between visits

## Publish to GitHub Pages

1. On GitHub, create a **new public repository**, e.g. `living-dex`.
2. Upload `index.html` and `README.md` to the **root** of the repository and commit.
3. Under your repository **Settings → Pages**, set **Deploy from a branch**, **main**, and **/(root)**, then save.
4. Once publishing completes, visit `https://YOUR-USERNAME.github.io/living-dex/`.

This app uses plain HTML, CSS, and JavaScript. No build tools or GitHub credentials are necessary.

## How the challenge system works

1. Choose a Pokémon species.
2. Check **I want to unlock this Pokémon through a challenge**.
3. Write an original requirement or choose a suggested challenge.
4. Once you've actually completed it in-game, check **Challenge completed**.
5. For Generation 1, the GameShark code is revealed for copying; enable it in a compatible emulator and catch the encounter.
6. Disable the cheat immediately, nickname the Pokémon in-game, and record its nickname and location here.
7. Mark it as collected only if it has a nickname and is present in the game/save collection.

The site does not automatically detect completed challenges or inject cheats into a game. Challenge completion uses the honor system. The site does not transfer Pokémon between games or into Pokémon HOME.

## Save and safety notes

- Make a **backup copy of the game's normal in-game save** before testing an encounter cheat. Some cheats are unstable or game-region-specific.
- The Gen 1 cheat database targets English **Pokémon Red/Blue** GameShark wild encounter modifiers. Other versions and regions can require different codes; don't use these for Yellow without independent verification.
- Website collection progress is stored using browser localStorage. It is **not synced with GitHub automatically** or between browsers/devices. Use the **Export backup** button regularly, and **Import backup** on another device or browser.
- Official-artwork images are requested from the PokéAPI sprites project on GitHub; species metadata is fetched from PokéAPI during the initial visit.
- Pokémon names/characters/artwork are the property of their respective owners. This is a non-commercial fan project and contains no game ROMs.

## Sources

- mGBA official: https://mgba.io/
- PokéAPI: https://pokeapi.co/docs/v2
- Generation 1 GameShark cheat references: https://www.serebii.net/rb/gamesharkrb.shtml ; https://gamefaqs.gamespot.com/gameboy/367023-pokemon-red-version/faqs/6618