---
statblock: inline
source: SRD 5.2.1
cr: '2'
xp: 450
type: Humanoid
initiative_text: +0 (10)
tags:
- srd521/monster
- srd521/type/humanoid
---

```statblock
layout: Basic 5e Layout
name: Priest
source: SRD 5.2.1
type_line: Medium or Small Humanoid (Cleric), Neutral
initiative_line: +0 (10)
modifier: 0
ability_mods:
- 3
- 0
- 1
- 1
- 3
- 1
ability_saves:
- 3
- 0
- 1
- 1
- 3
- 1
skills_text: Medicine +7, Perception +5, Religion +5
cr_line: 2 (XP 450; PB +2)
xp: 450
size: Medium or Small
type: Humanoid
subtype: Cleric
alignment: Neutral
ac: 13
hp: 38
hit_dice: 7d8 + 7
speed: 30 ft.
stats:
- 16
- 10
- 12
- 13
- 16
- 13
skillsaves:
- medicine: 7
- perception: 5
- religion: 5
gear: Chain Shirt, Holy Symbol, Mace
senses: Passive Perception 15
languages: Common plus one other language
cr: '2'
dice: false
actions:
- name: Multiattack
  desc: The priest makes two attacks, using Mace or Radiant Flame in any combination.
- name: Mace
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 6 (1d6 + 3) Bludgeoning damage plus 5 (2d4) Radiant damage.
- name: Radiant Flame
  desc: _Ranged Attack Roll:_ +5, range 60 ft. _Hit:_ 11 (2d10) Radiant damage.
- name: Spellcasting
  desc: |-
    The priest casts one of the following spells, using Wisdom as the spellcasting ability (spell save DC 13):
    **At Will:** _Light_, _Thaumaturgy_
    **1/Day:** _Spirit Guardians_
bonus_actions:
- name: Divine Aid (3/Day)
  desc: The priest casts _Bless_, _Dispel Magic_, _Healing Word_, or _Lesser Restoration_, using the same spellcasting ability as Spellcasting.
```
