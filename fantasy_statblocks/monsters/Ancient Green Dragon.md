---
statblock: inline
source: SRD 5.2.1
cr: '22'
xp: 41000
type: Dragon
initiative_text: +15 (25)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 50000
---

```statblock
layout: Basic 5e Layout
name: Ancient Green Dragon
source: SRD 5.2.1
type_line: Gargantuan Dragon (Chromatic), Lawful Evil
initiative_line: +15 (25)
modifier: 15
ability_mods:
- 8
- 1
- 7
- 5
- 3
- 6
ability_saves:
- 8
- 8
- 7
- 5
- 10
- 6
skills_text: Deception +13, Perception +17, Persuasion +13, Stealth +8
immunities: Poison; Poisoned
cr_line: 22 (XP 41,000, or 50,000 in lair; PB +7)
xp: 41000
size: Gargantuan
type: Dragon
subtype: Chromatic
alignment: Lawful Evil
ac: 21
hp: 402
hit_dice: 23d20 + 161
speed: 40 ft., Fly 80 ft., Swim 40 ft.
stats:
- 27
- 12
- 25
- 20
- 17
- 22
saves:
- dexterity: 8
- wisdom: 10
skillsaves:
- deception: 13
- perception: 17
- persuasion: 13
- stealth: 8
damage_immunities: Poison
condition_immunities: Poisoned
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 27
languages: Common, Draconic
cr: '22'
dice: false
traits:
- name: Amphibious
  desc: The dragon can breathe air and water.
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast _Mind Spike_ (level 5 version).
- name: Rend
  desc: _Melee Attack Roll:_ +15, reach 15 ft. _Hit:_ 17 (2d8 + 8) Slashing damage plus 10 (3d6) Poison damage.
- name: Poison Breath (Recharge 5–6)
  desc: _Constitution Saving Throw:_ DC 22, each creature in a 90-foot Cone. _Failure:_ 77 (22d6) Poison damage. _Success:_ Half damage.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 21):
    **At Will:** _Detect Magic_, _Mind Spike_ (level 5 version)
    **1/Day Each:** _Geas_, _Modify Memory_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Mind Invasion
  desc: The dragon uses Spellcasting to cast _Mind Spike_ (level 5 version).
- name: Noxious Miasma
  desc: _Constitution Saving Throw:_ DC 21, each creature in a 30-foot-radius Sphere centered on a point the dragon can see within 90 feet. _Failure:_ 17 (5d6) Poison damage, and the target takes a -2 penalty to AC until the end of its next turn. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
```
