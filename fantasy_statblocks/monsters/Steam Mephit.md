---
statblock: inline
source: SRD 5.2.1
cr: 1/4
xp: 50
type: Elemental
initiative_text: +0 (10)
tags:
- srd521/monster
- srd521/type/elemental
---

```statblock
layout: Basic 5e Layout
name: Steam Mephit
source: SRD 5.2.1
type_line: Small Elemental, Neutral Evil
initiative_line: +0 (10)
modifier: 0
ability_mods:
- -3
- 0
- 0
- 0
- 0
- 1
ability_saves:
- -3
- 0
- 0
- 0
- 0
- 1
skills_text: Stealth +2
immunities: Fire, Poison; Exhaustion, Poisoned
cr_line: 1/4 (XP 50; PB +2)
xp: 50
size: Small
type: Elemental
alignment: Neutral Evil
ac: 10
hp: 17
hit_dice: 5d6
speed: 30 ft., Fly 30 ft.
stats:
- 5
- 11
- 10
- 11
- 10
- 12
skillsaves:
- stealth: 2
damage_immunities: Fire, Poison
condition_immunities: Exhaustion, Poisoned
senses: Darkvision 60 ft.; Passive Perception 10
languages: Primordial (Aquan, Ignan)
cr: 1/4
dice: false
traits:
- name: Blurred Form
  desc: Attack rolls against the mephit are made with Disadvantage unless the mephit has the Incapacitated condition.
- name: Death Burst
  desc: The mephit explodes when it dies. _Dexterity Saving Throw:_ DC 10, each creature in a 5-foot Emanation originating from the mephit. _Failure:_ 5 (2d4) Fire damage. _Success:_ Half damage.
actions:
- name: Claw
  desc: _Melee Attack Roll:_ +2, reach 5 ft. _Hit:_ 2 (1d4) Slashing damage plus 2 (1d4) Fire damage.
- name: Steam Breath (Recharge 6)
  desc: _Constitution Saving Throw:_ DC 10, each creature in a 15-foot Cone. _Failure:_ 5 (2d4) Fire damage, and the target's Speed decreases by 10 feet until the end of the mephit's next turn. _Success:_ Half damage only. _Failure or Success:_ Being underwater doesn't grant Resistance to this Fire damage.
```
