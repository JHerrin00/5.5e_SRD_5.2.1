---
statblock: inline
source: SRD 5.2.1
cr: '5'
xp: 1800
type: Aberration
initiative_text: +5 (15)
tags:
- srd521/monster
- srd521/type/aberration
---

```statblock
layout: Basic 5e Layout
name: Roper
source: SRD 5.2.1
type_line: Large Aberration, Neutral Evil
initiative_line: +5 (15)
modifier: 5
ability_mods:
- 4
- -1
- 3
- -2
- 3
- -2
ability_saves:
- 4
- -1
- 3
- -2
- 3
- -2
skills_text: Perception +6, Stealth +5
cr_line: 5 (XP 1,800; PB +3)
xp: 1800
size: Large
type: Aberration
alignment: Neutral Evil
ac: 20
hp: 93
hit_dice: 11d10 + 33
speed: 10 ft., Climb 20 ft.
stats:
- 18
- 8
- 17
- 7
- 16
- 6
skillsaves:
- perception: 6
- stealth: 5
senses: Darkvision 60 ft.; Passive Perception 16
languages: None
cr: '5'
dice: false
traits:
- name: Spider Climb
  desc: The roper can climb difficult surfaces, including along ceilings, without needing to make an ability check.
actions:
- name: Multiattack
  desc: The roper makes two Tentacle attacks, uses Reel, and makes two Bite attacks.
- name: Bite
  desc: _Melee Attack Roll:_ +7, reach 5 ft. _Hit:_ 17 (3d8 + 4) Piercing damage.
- name: Tentacle
  desc: |-
    _Melee Attack Roll:_ +7, reach 60 ft. _Hit:_ The target has the Grappled condition (escape DC 14) from one of six tentacles, and the target has the Poisoned condition until the grapple ends.
    The tentacle can be damaged, freeing a creature it has Grappled when destroyed (AC 20, HP 10, Immunity to Poison and Psychic damage). Damaging the tentacle deals no damage to the roper, and a destroyed tentacle regrows at the start of the roper's next turn.
- name: Reel
  desc: The roper pulls each creature Grappled by it up to 30 feet straight toward it.
```
