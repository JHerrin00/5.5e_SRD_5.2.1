---
statblock: inline
source: SRD 5.2.1
cr: '5'
xp: 1800
type: Aberration
initiative_text: +0 (10)
tags:
- srd521/monster
- srd521/type/aberration
---

```statblock
layout: Basic 5e Layout
name: Otyugh
source: SRD 5.2.1
type_line: Large Aberration, Neutral
initiative_line: +0 (10)
modifier: 0
ability_mods:
- 3
- 0
- 4
- -2
- 1
- -2
ability_saves:
- 3
- 0
- 7
- -2
- 1
- -2
cr_line: 5 (XP 1,800; PB +3)
xp: 1800
size: Large
type: Aberration
alignment: Neutral
ac: 14
hp: 104
hit_dice: 11d10 + 44
speed: 30 ft.
stats:
- 16
- 11
- 19
- 6
- 13
- 6
saves:
- constitution: 7
senses: Darkvision 120 ft.; Passive Perception 11
languages: Otyugh; telepathy 120 ft. (doesn't allow the receiving creature to respond telepathically)
cr: '5'
dice: false
actions:
- name: Multiattack
  desc: The otyugh makes one Bite attack and two Tentacle attacks.
- name: Bite
  desc: _Melee Attack Roll:_ +6, reach 5 ft. _Hit:_ 12 (2d8 + 3) Piercing damage, and the target has the Poisoned condition. Whenever the Poisoned target finishes a Long Rest, it is subjected to the following effect. _Constitution Saving Throw:_ DC 15. _Failure:_ The target's Hit Point maximum decreases by 5 (1d10) and doesn't return to normal until the Poisoned condition ends on the target. _Success:_ The Poisoned condition ends.
- name: Tentacle
  desc: _Melee Attack Roll:_ +6, reach 10 ft. _Hit:_ 12 (2d8 + 3) Piercing damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 13) from one of two tentacles.
- name: Tentacle Slam
  desc: _Constitution Saving Throw:_ DC 14, each creature Grappled by the otyugh. _Failure:_ 16 (3d8 + 3) Bludgeoning damage, and the target has the Stunned condition until the start of the otyugh's next turn. _Success:_ Half damage only.
```
