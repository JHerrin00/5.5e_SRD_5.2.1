---
statblock: inline
source: SRD 5.2.1
cr: '12'
xp: 8000
type: Humanoid
initiative_text: +7 (17)
tags:
- srd521/monster
- srd521/type/humanoid
---

```statblock
layout: Basic 5e Layout
name: Archmage
source: SRD 5.2.1
type_line: Medium or Small Humanoid (Wizard), Neutral
initiative_line: +7 (17)
modifier: 7
ability_mods:
- 0
- 2
- 1
- 5
- 2
- 3
ability_saves:
- 0
- 2
- 1
- 9
- 6
- 3
skills_text: Arcana +13, History +9, Perception +6
immunities: Psychic; Charmed (with _Mind Blank_)
cr_line: 12 (XP 8,000; PB +4)
xp: 8000
size: Medium or Small
type: Humanoid
subtype: Wizard
alignment: Neutral
ac: 17
hp: 170
hit_dice: 31d8 + 31
speed: 30 ft.
stats:
- 10
- 14
- 12
- 20
- 15
- 16
saves:
- intelligence: 9
- wisdom: 6
skillsaves:
- arcana: 13
- history: 9
- perception: 6
damage_immunities: Psychic
condition_immunities: Charmed (with _Mind Blank_)
gear: Wand
senses: Passive Perception 16
languages: Common plus five other languages
cr: '12'
dice: false
traits:
- name: Magic Resistance
  desc: The archmage has Advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: The archmage makes four Arcane Burst attacks.
- name: Arcane Burst
  desc: _Melee or Ranged Attack Roll:_ +9, reach 5 ft. or range 150 ft. _Hit:_ 27 (4d10 + 5) Force damage.
- name: Spellcasting
  desc: |-
    The archmage casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 17):
    **At Will:** _Detect Magic_, _Detect Thoughts_, _Disguise Self_, _Invisibility_, _Light_, _Mage Armor_ (included in AC), _Mage Hand_, _Prestidigitation_
    **2/Day Each:** _Fly_, _Lightning Bolt_ (level 7 version)
    **1/Day Each:** _Cone of Cold_ (level 9 version), _Mind Blank_ (cast before combat), _Scrying_, _Teleport_
bonus_actions:
- name: Misty Step (3/Day)
  desc: The mage casts _Misty Step_, using the same spellcasting ability as Spellcasting.
reactions:
- name: Protective Magic (3/Day)
  desc: The archmage casts _Counterspell_ or _Shield_ in response to the spell's trigger, using the same spellcasting ability as Spellcasting.
```
