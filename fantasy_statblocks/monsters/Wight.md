---
statblock: inline
source: SRD 5.2.1
cr: '3'
xp: 700
type: Undead
initiative_text: +4 (14)
tags:
- srd521/monster
- srd521/type/undead
---

```statblock
layout: Basic 5e Layout
name: Wight
source: SRD 5.2.1
type_line: Medium Undead, Neutral Evil
initiative_line: +4 (14)
modifier: 4
ability_mods:
- 2
- 2
- 3
- 0
- 1
- 2
ability_saves:
- 2
- 2
- 3
- 0
- 1
- 2
skills_text: Perception +3, Stealth +4
resistances: Necrotic
immunities: Poison; Exhaustion, Poisoned
cr_line: 3 (XP 700; PB +2)
xp: 700
size: Medium
type: Undead
alignment: Neutral Evil
ac: 14
hp: 82
hit_dice: 11d8 + 33
speed: 30 ft.
stats:
- 15
- 14
- 16
- 10
- 13
- 15
skillsaves:
- perception: 3
- stealth: 4
damage_resistances: Necrotic
damage_immunities: Poison
condition_immunities: Exhaustion, Poisoned
gear: Studded Leather Armor
senses: Darkvision 60 ft.; Passive Perception 13
languages: Common plus one other language
cr: '3'
dice: false
traits:
- name: Sunlight Sensitivity
  desc: While in sunlight, the wight has Disadvantage on ability checks and attack rolls.
actions:
- name: Multiattack
  desc: The wight makes two attacks, using Necrotic Sword or Necrotic Bow in any combination. It can replace one attack with a use of Life Drain.
- name: Necrotic Sword
  desc: _Melee Attack Roll:_ +4, reach 5 ft. _Hit:_ 6 (1d8 + 2) Slashing damage plus 4 (1d8) Necrotic damage.
- name: Necrotic Bow
  desc: _Ranged Attack Roll:_ +4, range 150/600 ft. _Hit:_ 6 (1d8 + 2) Piercing damage plus 4 (1d8) Necrotic damage.
- name: Life Drain
  desc: |-
    _Constitution Saving Throw:_ DC 13, one creature within 5 feet. _Failure:_ 6 (1d8 + 2) Necrotic damage, and the target's Hit Point maximum decreases by an amount equal to the damage taken.
    A Humanoid slain by this attack rises 24 hours later as a **Zombie** under the wight's control, unless the Humanoid is restored to life or its body is destroyed. The wight can have no more than twelve zombies under its control at a time.
```
