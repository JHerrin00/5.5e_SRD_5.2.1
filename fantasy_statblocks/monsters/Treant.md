---
statblock: inline
source: SRD 5.2.1
cr: '9'
xp: 5000
type: Plant
initiative_text: +3 (13)
tags:
- srd521/monster
- srd521/type/plant
---

```statblock
layout: Basic 5e Layout
name: Treant
source: SRD 5.2.1
type_line: Huge Plant, Chaotic Good
initiative_line: +3 (13)
modifier: 3
ability_mods:
- 6
- -1
- 5
- 1
- 3
- 1
ability_saves:
- 6
- -1
- 5
- 1
- 3
- 1
vulnerabilities: Fire
resistances: Bludgeoning, Piercing
cr_line: 9 (XP 5,000; PB +4)
xp: 5000
size: Huge
type: Plant
alignment: Chaotic Good
ac: 16
hp: 138
hit_dice: 12d12 + 60
speed: 30 ft.
stats:
- 23
- 8
- 21
- 12
- 16
- 12
damage_vulnerabilities: Fire
damage_resistances: Bludgeoning, Piercing
senses: Passive Perception 13
languages: Common, Druidic, Elvish, Sylvan
cr: '9'
dice: false
traits:
- name: Siege Monster
  desc: The treant deals double damage to objects and structures.
actions:
- name: Multiattack
  desc: The treant makes two Slam attacks.
- name: Slam
  desc: _Melee Attack Roll:_ +10, reach 5 ft. _Hit:_ 16 (3d6 + 6) Bludgeoning damage.
- name: Hail of Bark
  desc: _Ranged Attack Roll:_ +10, range 180 ft. _Hit:_ 28 (4d10 + 6) Piercing damage.
- name: Animate Trees (1/Day)
  desc: The treant magically animates up to two trees it can see within 60 feet of itself. Each tree uses the **Treant** stat block, except it has Intelligence and Charisma scores of 1, it can't speak, and it lacks this action. The tree takes its turn immediately after the treant on the same Initiative count, and it obeys the treant. A tree remains animate for 1 day or until it dies, the treant dies, or it is more than 120 feet from the treant. The tree then takes root if possible.
```
