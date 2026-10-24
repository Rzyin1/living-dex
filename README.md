# Pokémon Quetzal — Nuzlocke Runkeeper

A responsive Nuzlocke tracker hosted on GitHub Pages at https://rzyin1.github.io/living-dex/

This project **replaces the old Living Pokédex homepage**. The original website, README, and collection file are backed up in `archive/` and still available in Git history.

## Features

- **Overview:** six active team slots, catch totals, reserve Pokémon, fallen Pokémon, Gym badges and level-cap warning.
- **Pokémon roster:** nickname, species, National Dex number (optional for art), current level, original level, gender, Nature, Ability, location, moves, IVs and notes.
- **Permadeath:** mark a fainted Pokémon as Fallen, optionally record the cause. The site does not let a fallen Pokémon rejoin the team during that run.
- **Encounter log:** one first eligible encounter per route/area by default; outcomes include Caught, Missed and Skipped (dupes).
- **Run history:** start new attempts without deleting previous runs; track Champion, Wiped, Active and Retired statuses.
- **Gym badges and level caps:** mark badges individually and enter the *verified* next Gym name and cap. No assumptions about Quetzal version or difficulty.
- **Save management:** automatic local browser storage and JSON backup/restore.
- **ChatGPT updates:** the site loads records from `nuzlocke-data.json` in GitHub. ChatGPT can update that file through your connected GitHub account when you report a capture, evolution, faint, or badge.

## Initial Quetzal run

Run #1 includes Sprout the Hasty Bulbasaur, level 5, Overgrow. Starting IVs were recorded from the user's Quetzal screenshots.

## Important: where the data lives

Edits performed **on the website** are saved in the current browser only. They **do not automatically write back to GitHub**. If you use the site on another computer/phone or clear browser data, download and import a JSON backup.

Records that ChatGPT publishes to `nuzlocke-data.json` are read when the page loads. The website merges added Pokémon and updated fields with the current browser record; local-only fields are preserved where possible. If the same field changes independently on both sides, a GitHub update may replace the local value. Export a backup before switching devices or restoring older data.

GitHub repository content is public. Do not add personal secrets or private information to Pokémon notes.

## Original Living Pokédex archive

- `archive/living-dex-index.html`: previous Pokédex website
- `archive/living-dex-README.md`: previous instructions
- `archive/living-dex-collection.json`: previous FireRed Pokémon records

No emulator saves, ROMs, or copyrighted game files are included. This is a fan-made tracking site.
