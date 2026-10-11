---
statblock: inline
source: SRD 5.2.1
cr: '2'
xp: 450
type: Undead
initiative_text: +3 (13)
tags:
- srd521/monster
- srd521/type/undead
---

```statblock
layout: Basic 5e Layout
name: Ghast
source: SRD 5.2.1
type_line: Medium Undead, Chaotic Evil
initiative_line: +3 (13)
modifier: 3
ability_mods:
- 3
- 3
- 0
- 0
- 0
- -1
ability_saves:
- 3
- 3
- 0
- 0
- 2
- -1
resistances: Necrotic
immunities: Poison; Charmed, Exhaustion, Poisoned
cr_line: 2 (XP 450; PB +2)
xp: 450
size: Medium
type: Undead
alignment: Chaotic Evil
ac: 13
hp: 36
hit_dice: 8d8
speed: 30 ft.
stats:
- 16
- 17
- 10
- 11
- 10
- 8
saves:
- wisdom: 2
damage_resistances: Necrotic
damage_immunities: Poison
condition_immunities: Charmed, Exhaustion, Poisoned
senses: Darkvision 60 ft.; Passive Perception 10
languages: Common
cr: '2'
dice: false
traits:
- name: Stench
  desc: _Constitution Saving Throw:_ DC 10, any creature that starts its turn in a 5-foot Emanation originating from the ghast. _Failure:_ The target has the Poisoned condition until the start of its next turn. _Success:_ The target is immune to this ghast's Stench for 24 hours.
actions:
- name: Bite
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 7 (1d8 + 3) Piercing damage plus 9 (2d8) Necrotic damage.
- name: Claw
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 10 (2d6 + 3) Slashing damage. If the target is a non-Undead creature, it is subjected to the following effect. _Constitution Saving Throw:_ DC 10. _Failure:_ The target has the Paralyzed condition until the end of its next turn.
```
