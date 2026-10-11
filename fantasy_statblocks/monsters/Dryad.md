---
statblock: inline
source: SRD 5.2.1
cr: '1'
xp: 200
type: Fey
initiative_text: +1 (11)
tags:
- srd521/monster
- srd521/type/fey
---

```statblock
layout: Basic 5e Layout
name: Dryad
source: SRD 5.2.1
type_line: Medium Fey, Neutral
initiative_line: +1 (11)
modifier: 1
ability_mods:
- 0
- 1
- 0
- 2
- 2
- 4
ability_saves:
- 0
- 1
- 0
- 2
- 2
- 4
skills_text: Perception +4, Stealth +5
cr_line: 1 (XP 200; PB +2)
xp: 200
size: Medium
type: Fey
alignment: Neutral
ac: 16
hp: 22
hit_dice: 5d8
speed: 30 ft.
stats:
- 10
- 12
- 11
- 14
- 15
- 18
skillsaves:
- perception: 4
- stealth: 5
senses: Darkvision 60 ft.; Passive Perception 14
languages: Elvish, Sylvan
cr: '1'
dice: false
traits:
- name: Magic Resistance
  desc: The dryad has Advantage on saving throws against spells and other magical effects.
- name: Speak with Beasts and Plants
  desc: The dryad can communicate with Beasts and Plants as if they shared a language.
actions:
- name: Multiattack
  desc: The dryad makes one Vine Lash or Thorn Burst attack, and it can use Spellcasting to cast _Charm Monster_.
- name: Vine Lash
  desc: _Melee Attack Roll:_ +6, reach 10 ft. _Hit:_ 8 (1d8 + 4) Slashing damage.
- name: Thorn Burst
  desc: _Ranged Attack Roll:_ +6, range 60 ft. _Hit:_ 7 (1d6 + 4) Piercing damage.
- name: Spellcasting
  desc: |-
    The dryad casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 14):
    **At Will:** _Animal Friendship_, _Charm Monster_ (lasts 24 hours; ends early if the dryad casts the spell again), _Druidcraft_
    **1/Day Each:** _Entangle_, _Pass without Trace_
bonus_actions:
- name: Tree Stride
  desc: If within 5 feet of a Large or bigger tree, the dryad teleports to an unoccupied space within 5 feet of a second Large or bigger tree that is within 60 feet of the previous tree.
```
