---
statblock: inline
source: SRD 5.2.1
cr: '5'
xp: 1800
type: Humanoid
initiative_text: +5 (15)
tags:
- srd521/monster
- srd521/type/humanoid
---

```statblock
layout: Basic 5e Layout
name: Gladiator
source: SRD 5.2.1
type_line: Medium or Small Humanoid, Neutral
initiative_line: +5 (15)
modifier: 5
ability_mods:
- 4
- 2
- 3
- 0
- 1
- 2
ability_saves:
- 7
- 5
- 6
- 0
- 4
- 2
skills_text: Athletics +10, Performance +5
cr_line: 5 (XP 1,800; PB +3)
xp: 1800
size: Medium or Small
type: Humanoid
alignment: Neutral
ac: 16
hp: 112
hit_dice: 15d8 + 45
speed: 30 ft.
stats:
- 18
- 15
- 16
- 10
- 12
- 15
saves:
- strength: 7
- dexterity: 5
- constitution: 6
- wisdom: 4
skillsaves:
- athletics: 10
- performance: 5
gear: Shield, Spears (3), Studded Leather Armor
senses: Passive Perception 11
languages: Common
cr: '5'
dice: false
actions:
- name: Multiattack
  desc: The gladiator makes three Spear attacks. It can replace one attack with a use of Shield Bash.
- name: Spear
  desc: _Melee or Ranged Attack Roll:_ +7, reach 5 ft. or range 20/60 ft. _Hit:_ 11 (2d6 + 4) Piercing damage.
- name: Shield Bash
  desc: _Strength Saving Throw:_ DC 15, one creature within 5 feet that the gladiator can see. _Failure:_ 9 (2d4 + 4) Bludgeoning damage. If the target is a Medium or smaller creature, it has the Prone condition.
reactions:
- name: Parry
  desc: _Trigger:_ The gladiator is hit by a melee attack roll while holding a weapon. _Response:_ The gladiator adds 3 to its AC against that attack, possibly causing it to miss.
```
