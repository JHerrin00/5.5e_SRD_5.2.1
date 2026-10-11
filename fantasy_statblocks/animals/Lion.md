---
statblock: inline
source: SRD 5.2.1
cr: '1'
xp: 200
type: Beast
initiative_text: +2 (12)
tags:
- srd521/animal
- srd521/type/beast
---

```statblock
layout: Basic 5e Layout
name: Lion
source: SRD 5.2.1
type_line: Large Beast, Unaligned
initiative_line: +2 (12)
modifier: 2
ability_mods:
- 3
- 2
- 0
- -4
- 1
- -1
ability_saves:
- 3
- 2
- 0
- -4
- 1
- -1
skills_text: Perception +3, Stealth +4
cr_line: 1 (XP 200; PB +2)
xp: 200
size: Large
type: Beast
alignment: Unaligned
ac: 12
hp: 22
hit_dice: 4d10
speed: 50 ft.
stats:
- 17
- 15
- 11
- 3
- 12
- 8
skillsaves:
- perception: 3
- stealth: 4
senses: Darkvision 60 ft.; Passive Perception 13
languages: None
cr: '1'
dice: false
traits:
- name: Pack Tactics
  desc: The lion has Advantage on an attack roll against a creature if at least one of the lion's allies is within 5 feet of the creature and the ally doesn't have the Incapacitated condition.
- name: Running Leap
  desc: With a 10-foot running start, the lion can Long Jump up to 25 feet.
actions:
- name: Multiattack
  desc: The lion makes two Rend attacks. It can replace one attack with a use of Roar.
- name: Rend
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 7 (1d8 + 3) Slashing damage.
- name: Roar
  desc: _Wisdom Saving Throw:_ DC 11, one creature within 15 feet. _Failure:_ The target has the Frightened condition until the start of the lion's next turn.
```
