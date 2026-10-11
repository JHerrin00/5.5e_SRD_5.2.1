---
statblock: inline
source: SRD 5.2.1
cr: '3'
xp: 700
type: Humanoid
initiative_text: +0 (10)
tags:
- srd521/monster
- srd521/type/humanoid
---

```statblock
layout: Basic 5e Layout
name: Knight
source: SRD 5.2.1
type_line: Medium or Small Humanoid, Neutral
initiative_line: +0 (10)
modifier: 0
ability_mods:
- 3
- 0
- 2
- 0
- 0
- 2
ability_saves:
- 3
- 0
- 4
- 0
- 2
- 2
immunities: Frightened
cr_line: 3 (XP 700; PB +2)
xp: 700
size: Medium or Small
type: Humanoid
alignment: Neutral
ac: 18
hp: 52
hit_dice: 8d8 + 16
speed: 30 ft.
stats:
- 16
- 11
- 14
- 11
- 11
- 15
saves:
- constitution: 4
- wisdom: 2
condition_immunities: Frightened
gear: Greatsword, Heavy Crossbow, Plate Armor
senses: Passive Perception 10
languages: Common plus one other language
cr: '3'
dice: false
actions:
- name: Multiattack
  desc: The knight makes two attacks, using Greatsword or Heavy Crossbow in any combination.
- name: Greatsword
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 10 (2d6 + 3) Slashing damage plus 4 (1d8) Radiant damage.
- name: Heavy Crossbow
  desc: _Ranged Attack Roll:_ +2, range 100/400 ft. _Hit:_ 11 (2d10) Piercing damage plus 4 (1d8) Radiant damage.
reactions:
- name: Parry
  desc: _Trigger:_ The knight is hit by a melee attack roll while holding a weapon. _Response:_ The knight adds 2 to its AC against that attack, possibly causing it to miss.
```
