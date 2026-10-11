---
statblock: inline
source: SRD 5.2.1
cr: '5'
xp: 1800
type: Construct
initiative_text: +0 (10)
tags:
- srd521/monster
- srd521/type/construct
---

```statblock
layout: Basic 5e Layout
name: Gorgon
source: SRD 5.2.1
type_line: Large Construct, Unaligned
initiative_line: +0 (10)
modifier: 0
ability_mods:
- 5
- 0
- 4
- -4
- 1
- -2
ability_saves:
- 5
- 0
- 4
- -4
- 1
- -2
skills_text: Perception +7
immunities: Exhaustion, Petrified
cr_line: 5 (XP 1,800; PB +3)
xp: 1800
size: Large
type: Construct
alignment: Unaligned
ac: 19
hp: 114
hit_dice: 12d10 + 48
speed: 40 ft.
stats:
- 20
- 11
- 18
- 2
- 12
- 7
skillsaves:
- perception: 7
condition_immunities: Exhaustion, Petrified
senses: Darkvision 60 ft.; Passive Perception 17
languages: None
cr: '5'
dice: false
actions:
- name: Gore
  desc: _Melee Attack Roll:_ +8, reach 5 ft. _Hit:_ 18 (2d12 + 5) Piercing damage. If the target is a Large or smaller creature and the gorgon moved 20+ feet straight toward it immediately before the hit, the target has the Prone condition.
- name: Petrifying Breath (Recharge 5–6)
  desc: _Constitution Saving Throw:_ DC 15, each creature in a 30-foot Cone. _First Failure:_ The target has the Restrained condition and repeats the save at the end of its next turn if it is still Restrained, ending the effect on itself on a success. _Second Failure:_ The target has the Petrified condition instead of the Restrained condition.
bonus_actions:
- name: Trample
  desc: _Dexterity Saving Throw:_ DC 16, one creature within 5 feet that has the Prone condition. _Failure:_ 16 (2d10 + 5) Bludgeoning damage. _Success:_ Half damage.
```
