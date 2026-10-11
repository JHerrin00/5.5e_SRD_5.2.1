---
statblock: inline
source: SRD 5.2.1
cr: '21'
xp: 33000
type: Dragon
initiative_text: +16 (26)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 41000
---

```statblock
layout: Basic 5e Layout
name: Ancient Black Dragon
source: SRD 5.2.1
type_line: Gargantuan Dragon (Chromatic), Chaotic Evil
initiative_line: +16 (26)
modifier: 16
ability_mods:
- 8
- 2
- 7
- 3
- 2
- 6
ability_saves:
- 8
- 9
- 7
- 3
- 9
- 6
skills_text: Perception +16, Stealth +9
immunities: Acid
cr_line: 21 (XP 33,000, or 41,000 in lair; PB +7)
xp: 33000
size: Gargantuan
type: Dragon
subtype: Chromatic
alignment: Chaotic Evil
ac: 22
hp: 367
hit_dice: 21d20 + 147
speed: 40 ft., Fly 80 ft., Swim 40 ft.
stats:
- 27
- 14
- 25
- 16
- 15
- 22
saves:
- dexterity: 9
- wisdom: 9
skillsaves:
- perception: 16
- stealth: 9
damage_immunities: Acid
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 26
languages: Common, Draconic
cr: '21'
dice: false
traits:
- name: Amphibious
  desc: The dragon can breathe air and water.
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast _Acid Arrow_ (level 4 version).
- name: Rend
  desc: _Melee Attack Roll:_ +15, reach 15 ft. _Hit:_ 17 (2d8 + 8) Slashing damage plus 9 (2d8) Acid damage.
- name: Acid Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 22, each creature in a 90-foot-long, 10-foot-wide Line. _Failure:_ 67 (15d8) Acid damage. _Success:_ Half damage.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 21, +13 to hit with spell attacks):
    **At Will:** _Acid Arrow_ (level 4 version), _Detect Magic_, _Fear_
    **1/Day Each:** _Create Undead_, _Speak with Dead_, _Vitriolic Sphere_ (level 5 version)
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Cloud of Insects
  desc: _Dexterity Saving Throw:_ DC 21, one creature the dragon can see within 120 feet. _Failure:_ 33 (6d10) Poison damage, and the target has Disadvantage on saving throws to maintain Concentration until the end of its next turn. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
- name: Frightful Presence
  desc: The dragon uses Spellcasting to cast _Fear_. The dragon can't take this action again until the start of its next turn.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
```
