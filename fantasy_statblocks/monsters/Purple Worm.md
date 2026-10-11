---
statblock: inline
source: SRD 5.2.1
cr: '15'
xp: 13000
type: Monstrosity
initiative_text: +3 (13)
tags:
- srd521/monster
- srd521/type/monstrosity
---

```statblock
layout: Basic 5e Layout
name: Purple Worm
source: SRD 5.2.1
type_line: Gargantuan Monstrosity, Unaligned
initiative_line: +3 (13)
modifier: 3
ability_mods:
- 9
- -2
- 6
- -5
- -1
- -3
ability_saves:
- 9
- -2
- 11
- -5
- 4
- -3
cr_line: 15 (XP 13,000; PB +5)
xp: 13000
size: Gargantuan
type: Monstrosity
alignment: Unaligned
ac: 18
hp: 247
hit_dice: 15d20 + 90
speed: 50 ft., Burrow 50 ft.
stats:
- 28
- 7
- 22
- 1
- 8
- 4
saves:
- constitution: 11
- wisdom: 4
senses: Blindsight 30 ft., Tremorsense 60 ft.; Passive Perception 9
languages: None
cr: '15'
dice: false
traits:
- name: Tunneler
  desc: The worm can burrow through solid rock at half its Burrow Speed and leaves a 10-foot-diameter tunnel in its wake.
actions:
- name: Multiattack
  desc: The worm makes one Bite attack and one Tail Stinger attack.
- name: Bite
  desc: _Melee Attack Roll:_ +14, reach 10 ft. _Hit:_ 22 (3d8 + 9) Piercing damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 19), and it has the Restrained condition until the grapple ends.
- name: Tail Stinger
  desc: _Melee Attack Roll:_ +14, reach 10 ft. _Hit:_ 16 (2d6 + 9) Piercing damage plus 35 (10d6) Poison damage.
bonus_actions:
- name: Swallow
  desc: |-
    _Strength Saving Throw:_ DC 19, one Large or smaller creature Grappled by the worm (it can have up to three creatures swallowed at a time). _Failure:_ The target is swallowed by the worm, and the Grappled condition ends. A swallowed creature has the Blinded and Restrained conditions, has Total Cover against attacks and other effects outside the worm, and takes 17 (5d6) Acid damage at the start of each of the worm's turns.
    If the worm takes 30 damage or more on a single turn from a creature inside it, the worm must succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate all swallowed creatures, each of which falls in a space within 5 feet of the worm and has the Prone condition. If the worm dies, any swallowed creature no longer has the Restrained condition and can escape from the corpse using 20 feet of movement, exiting Prone.
```
