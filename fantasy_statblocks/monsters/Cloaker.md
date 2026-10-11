---
statblock: inline
source: SRD 5.2.1
cr: '8'
xp: 3900
type: Aberration
initiative_text: +5 (15)
tags:
- srd521/monster
- srd521/type/aberration
---

```statblock
layout: Basic 5e Layout
name: Cloaker
source: SRD 5.2.1
type_line: Large Aberration, Chaotic Neutral
initiative_line: +5 (15)
modifier: 5
ability_mods:
- 3
- 2
- 1
- 1
- 2
- -2
ability_saves:
- 3
- 2
- 1
- 1
- 2
- -2
skills_text: Stealth +5
immunities: Frightened
cr_line: 8 (XP 3,900; PB +3)
xp: 3900
size: Large
type: Aberration
alignment: Chaotic Neutral
ac: 14
hp: 91
hit_dice: 14d10 + 14
speed: 10 ft., Fly 40 ft.
stats:
- 17
- 15
- 12
- 13
- 14
- 7
skillsaves:
- stealth: 5
condition_immunities: Frightened
senses: Darkvision 120 ft.; Passive Perception 12
languages: Deep Speech, Undercommon
cr: '8'
dice: false
traits:
- name: Light Sensitivity
  desc: While in Bright Light, the cloaker has Disadvantage on attack rolls.
actions:
- name: Multiattack
  desc: The cloaker makes one Attach attack and two Tail attacks.
- name: Attach
  desc: |-
    _Melee Attack Roll:_ +6, reach 5 ft. _Hit:_ 13 (3d6 + 3) Piercing damage. If the target is a Large or smaller creature, the cloaker attaches to it. While the cloaker is attached, the target has the Blinded condition, and the cloaker can't make Attach attacks against other targets. In addition, the cloaker halves the damage it takes (round down), and the target takes the same amount of damage.
    The cloaker can detach itself by spending 5 feet of movement. The target or a creature within 5 feet of it can take an action to try to detach the cloaker, doing so by succeeding on a DC 14 Strength (Athletics) check.
- name: Tail
  desc: _Melee Attack Roll:_ +6, reach 10 ft. _Hit:_ 8 (1d10 + 3) Slashing damage.
bonus_actions:
- name: Moan
  desc: _Wisdom Saving Throw:_ DC 13, each creature in a 60-foot Emanation originating from the cloaker. _Failure:_ The target has the Frightened condition until the end of the cloaker's next turn. _Success:_ The target is immune to this cloaker's Moan for the next 24 hours.
- name: Phantasms (Recharge after a Short or Long Rest)
  desc: The cloaker casts the _Mirror Image_ spell, requiring no spell components and using Wisdom as the spellcasting ability. The spell ends early if the cloaker starts or ends its turn in Bright Light.
```
