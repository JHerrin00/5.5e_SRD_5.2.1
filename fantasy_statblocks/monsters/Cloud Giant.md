---
statblock: inline
source: SRD 5.2.1
cr: '9'
xp: 5000
type: Giant
initiative_text: +4 (14)
tags:
- srd521/monster
- srd521/type/giant
---

```statblock
layout: Basic 5e Layout
name: Cloud Giant
source: SRD 5.2.1
type_line: Huge Giant, Neutral
initiative_line: +4 (14)
modifier: 4
ability_mods:
- 8
- 0
- 6
- 1
- 3
- 3
ability_saves:
- 8
- 0
- 10
- 1
- 7
- 3
skills_text: Insight +7, Perception +11
cr_line: 9 (XP 5,000; PB +4)
xp: 5000
size: Huge
type: Giant
alignment: Neutral
ac: 14
hp: 200
hit_dice: 16d12 + 96
speed: 40 ft., Fly 20 ft. (hover)
stats:
- 27
- 10
- 22
- 12
- 16
- 16
saves:
- constitution: 10
- wisdom: 7
skillsaves:
- insight: 7
- perception: 11
senses: Passive Perception 21
languages: Common, Giant
cr: '9'
dice: false
actions:
- name: Multiattack
  desc: The giant makes two attacks, using Thunderous Mace or Thundercloud in any combination. It can replace one attack with a use of Spellcasting to cast _Fog Cloud_.
- name: Thunderous Mace
  desc: _Melee Attack Roll:_ +12, reach 10 ft. _Hit:_ 21 (3d8 + 8) Bludgeoning damage plus 7 (2d6) Thunder damage.
- name: Thundercloud
  desc: _Ranged Attack Roll:_ +12, range 240 ft. _Hit:_ 18 (3d6 + 8) Thunder damage, and the target has the Incapacitated condition until the end of its next turn.
- name: Spellcasting
  desc: |-
    The giant casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 15):
    **At Will:** _Detect Magic_, _Fog Cloud_, _Light_
    **1/Day Each:** _Control Weather_, _Gaseous Form_, _Telekinesis_
bonus_actions:
- name: Misty Step
  desc: The giant casts the _Misty Step_ spell, using the same spellcasting ability as Spellcasting.
```
