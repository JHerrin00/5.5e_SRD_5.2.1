# 5.5e SRD 5.2.1

A Markdown and JSON version of the System Reference Document 5.2.1, with one file per spell, monster, item and so on.

## Contents

| Folder | Entries |
|---|---|
| `animals/` | 95 |
| `backgrounds/` | 4 |
| `classes/` | 12 |
| `core_rules/` | 10 |
| `fantasy_statblocks/` | 330 Obsidian notes (235 monsters, 95 animals) |
| `feats/` | 17 |
| `magic_items/` | 258 |
| `monsters/` | 235 |
| `species/` | 9 |
| `spells/` | 339 |
| `subclasses/` | 12 |

`core_rules/` has the rules text of each chapter as listed in the SRD.  Sections that have their own folder are not repeated. For example, `core_rules/Spells.md` covers gaining and casting spells, and the spells themselves are in `spells/`.

`.build/03_json/` contains one JSON file per category, written from the PDF along with the Markdown. Each class record holds its subclass. Spells, magic items and monster records keep the printed text next to the parsed values, such as a monster's `cr` and its full `cr_text`, because some SRD entries use formulas in place of numbers (a summoned creature's HP is "5 + 10 per spell level").

I checked my outputs against [downfallx/dnd-5e-srd-markdown](https://github.com/downfallx/dnd-5e-srd-markdown). None of its files are used here.

## Fantasy Statblocks

`fantasy_statblocks/` holds every monster and animal as an Obsidian note for the [Fantasy Statblocks](https://github.com/Obsidian-TTRPG-Community/fantasy-statblocks) plugin. The notes use the plugin's built-in Basic 5e Layout.

- Copy the folder into your vault. Each note should render its own stat block.
- Each note sets `modifier` to the creature's Initiative, so the Initiative Tracker plugin rolls with that and not the Dexterity modifier.
- `srd-5.2.1-layout.json` is an optional layout closer to the 2024 stat block. Import it under Layouts in the plugin's settings if you want to use it. The plugin will warn that it contains JavaScript, which only draws the Score, Mod and Save table.
- The Basic 5e Layout in Fantasy Statblocks adds a sign to every save, so it shows the Young White Dragon's Intelligence save as +2. The optional layout shows it as printed.

## Changes from the SRD text

The Markdown follows the PDF. The only changes are to format, listed below.

- Each class file has the class, and its subclass is in `subclasses/` under the PDF's heading, such as "Barbarian Subclass: Path of the Berserker".
- Sidebars are block quotes with the sidebar title in bold.
- Tables the PDF splits into side-by-side halves, or continues in the next column, are one table.
- Two-column tables the PDF prints without a header row are bulleted lists.
- Curly quotes and apostrophes are straight, and minus signs and the en dash in the Jackal's "1d4 – 1" are hyphen-minus.
- Words broken across lines in the PDF are joined back together.


## License & Legal

This work includes material from the System Reference Document 5.2.1 ("SRD 5.2.1") by Wizards of the Coast LLC, available at <https://www.dndbeyond.com/srd>. The SRD 5.2.1 is licensed under the Creative Commons Attribution 4.0 International License, available at <https://creativecommons.org/licenses/by/4.0/legalcode>.

This repository modifies the SRD. It converts the text to Markdown, JSON and Fantasy Statblocks notes and moves each subclass into its own file. There are no previous modifications by others.

This repository is released under the same license. This project is unofficial. It is compatible with fifth edition.

The SRD 5.2.1 and this repository are provided as is, with no warranty. See Section 5 of CC-BY-4.0.