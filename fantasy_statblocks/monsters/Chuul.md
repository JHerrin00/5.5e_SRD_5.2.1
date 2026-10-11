---
statblock: inline
source: SRD 5.2.1
cr: '4'
xp: 1100
type: Aberration
initiative_text: +0 (10)
tags:
- srd521/monster
- srd521/type/aberration
---

```statblock
layout: Basic 5e Layout
name: Chuul
source: SRD 5.2.1
type_line: Large Aberration, Chaotic Evil
initiative_line: +0 (10)
modifier: 0
ability_mods:
- 4
- 0
- 3
- -3
- 0
- -3
ability_saves:
- 4
- 0
- 3
- -3
- 0
- -3
skills_text: Perception +4
immunities: Poison; Poisoned
cr_line: 4 (XP 1,100; PB +2)
xp: 1100
size: Large
type: Aberration
alignment: Chaotic Evil
ac: 16
hp: 76
hit_dice: 9d10 + 27
speed: 30 ft., Swim 30 ft.
stats:
- 19
- 10
- 16
- 5
- 11
- 5
skillsaves:
- perception: 4
damage_immunities: Poison
condition_immunities: Poisoned
senses: Darkvision 60 ft.; Passive Perception 14
languages: Understands Deep Speech but can't speak
cr: '4'
dice: false
traits:
- name: Amphibious
  desc: The chuul can breathe air and water.
- name: Sense Magic
  desc: The chuul senses magic within 120 feet of itself. This trait otherwise works like the _Detect Magic_ spell but isn't itself magical.
actions:
- name: Multiattack
  desc: The chuul makes two Pincer attacks and uses Paralyzing Tentacles.
- name: Pincer
  desc: _Melee Attack Roll:_ +6, reach 10 ft. _Hit:_ 9 (1d10 + 4) Bludgeoning damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14) from one of two pincers.
- name: Paralyzing Tentacles
  desc: _Constitution Saving Throw:_ DC 13, one creature Grappled by the chuul. _Failure:_ The target has the Poisoned condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically. While Poisoned, the target has the Paralyzed condition.
```
