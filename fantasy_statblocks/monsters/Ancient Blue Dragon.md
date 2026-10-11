---
statblock: inline
source: SRD 5.2.1
cr: '23'
xp: 50000
type: Dragon
initiative_text: +14 (24)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 62000
---

```statblock
layout: Basic 5e Layout
name: Ancient Blue Dragon
source: SRD 5.2.1
type_line: Gargantuan Dragon (Chromatic), Lawful Evil
initiative_line: +14 (24)
modifier: 14
ability_mods:
- 9
- 0
- 8
- 4
- 3
- 7
ability_saves:
- 9
- 7
- 8
- 4
- 10
- 7
skills_text: Perception +17, Stealth +7
immunities: Lightning
cr_line: 23 (XP 50,000, or 62,000 in lair; PB +7)
xp: 50000
size: Gargantuan
type: Dragon
subtype: Chromatic
alignment: Lawful Evil
ac: 22
hp: 481
hit_dice: 26d20 + 208
speed: 40 ft., Burrow 40 ft., Fly 80 ft.
stats:
- 29
- 10
- 27
- 18
- 17
- 25
saves:
- dexterity: 7
- wisdom: 10
skillsaves:
- perception: 17
- stealth: 7
damage_immunities: Lightning
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 27
languages: Common, Draconic
cr: '23'
dice: false
traits:
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast _Shatter_ (level 3 version).
- name: Rend
  desc: _Melee Attack Roll:_ +16, reach 15 ft. _Hit:_ 18 (2d8 + 9) Slashing damage plus 11 (2d10) Lightning damage.
- name: Lightning Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 23, each creature in a 120-foot-long, 10-foot-wide Line. _Failure:_ 88 (16d10) Lightning damage. _Success:_ Half damage.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 22):
    **At Will:** _Detect Magic_, _Invisibility_, _Mage Hand_, _Shatter_ (level 3 version)
    **1/Day Each:** _Scrying_, _Sending_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Cloaked Flight
  desc: The dragon uses Spellcasting to cast _Invisibility_ on itself, and it can fly up to half its Fly Speed. The dragon can't take this action again until the start of its next turn.
- name: Sonic Boom
  desc: The dragon uses Spellcasting to cast _Shatter_ (level 3 version). The dragon can't take this action again until the start of its next turn.
- name: Tail Swipe
  desc: The dragon makes one Rend attack.
```
