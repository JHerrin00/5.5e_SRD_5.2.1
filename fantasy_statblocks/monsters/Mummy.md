---
statblock: inline
source: SRD 5.2.1
cr: '3'
xp: 700
type: Undead
initiative_text: -1 (9)
tags:
- srd521/monster
- srd521/type/undead
---

```statblock
layout: Basic 5e Layout
name: Mummy
source: SRD 5.2.1
type_line: Medium or Small Undead, Lawful Evil
initiative_line: -1 (9)
modifier: -1
ability_mods:
- 3
- -1
- 2
- -2
- 1
- 1
ability_saves:
- 3
- -1
- 2
- -2
- 3
- 1
vulnerabilities: Fire
immunities: Necrotic, Poison; Charmed, Exhaustion, Frightened, Paralyzed, Poisoned
cr_line: 3 (XP 700; PB +2)
xp: 700
size: Medium or Small
type: Undead
alignment: Lawful Evil
ac: 11
hp: 58
hit_dice: 9d8 + 18
speed: 20 ft.
stats:
- 16
- 8
- 15
- 6
- 12
- 12
saves:
- wisdom: 3
damage_vulnerabilities: Fire
damage_immunities: Necrotic, Poison
condition_immunities: Charmed, Exhaustion, Frightened, Paralyzed, Poisoned
senses: Darkvision 60 ft.; Passive Perception 11
languages: Common plus two other languages
cr: '3'
dice: false
actions:
- name: Multiattack
  desc: The mummy makes two Rotting Fist attacks and uses Dreadful Glare.
- name: Rotting Fist
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 8 (1d10 + 3) Bludgeoning damage plus 10 (3d6) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target can't regain Hit Points, its Hit Point maximum doesn't return to normal when finishing a Long Rest, and its Hit Point maximum decreases by 10 (3d6) every 24 hours that elapse. A creature dies and turns to dust if reduced to 0 Hit Points by this attack.
- name: Dreadful Glare
  desc: _Wisdom Saving Throw:_ DC 11, one creature the mummy can see within 60 feet. _Failure:_ The target has the Frightened condition until the end of the mummy's next turn. _Success:_ The target is immune to this mummy's Dreadful Glare for 24 hours.
```
