# Pokémon Grape — extracted graphics

Graphics from **Pokémon Grape** by 80C-Games, a Game Boy Color (Gen I-style engine) fan game, organised as plain image files for reference, study and fan projects.

## Contents

| Folder | What | Count |
|---|---|---|
| `pokemon/` | Pokémon battle sprites | 248 |
| `trainers/` | trainer pictures | 49 |
| `ui/` | interface graphics | 1 |

Each folder has a contact sheet (`_contact_*.png`) for browsing, and `manifest.json` lists every asset with notes.

## Format

- `pokemon/<name>/` — `front.png` (vertical strip of animation frames, colours applied, transparent background), `front_gray.png` (same in four grey levels), `back.png` / `back_gray.png`, `normal.pal` / `shiny.pal` (two 5-bit RGB lines: light and dark body colour), `anim.asm` (Crystal animation script) where the sprite is animated, and `preview.gif`.
- Other folders hold PNG sheets; tilesets are tile sheets 16 tiles wide.

## What is (and isn't) here

Only art that belongs to this game is included. Sprites, backs, interface pieces and icons that are identical to the official Pokémon Crystal graphics were left out, as were anything that could not be decoded reliably.

Per-species colours could not be located in the game data, so Pokémon are shown in the game's default palette.

## Credits

- Pokémon Grape: 80C-Games.
- Pokémon and all related characters and designs: © Nintendo, Creatures Inc. and GAME FREAK inc.

## Disclaimer

This is an unofficial fan archive. It contains no ROMs and no game code, only extracted images and palettes. All art remains the property of its creators; credit them if you use anything from here. Not affiliated with Nintendo, The Pokémon Company or the original fan-game authors. If you are an author and want something removed, open an issue.
