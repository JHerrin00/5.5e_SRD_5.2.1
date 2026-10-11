---
statblock: inline
source: SRD 5.2.1
cr: '2'
xp: 450
type: Undead
initiative_text: +9 (19)
tags:
- srd521/monster
- srd521/type/undead
---

```statblock
layout: Basic 5e Layout
name: Will-o'-Wisp
source: SRD 5.2.1
type_line: Tiny Undead, Chaotic Evil
initiative_line: +9 (19)
modifier: 9
ability_mods:
- -5
- 9
- 0
- 1
- 2
- 0
ability_saves:
- -5
- 9
- 0
- 1
- 2
- 0
resistances: Acid, Bludgeoning, Cold, Fire, Necrotic, Piercing, Slashing
immunities: Lightning, Poison; Exhaustion, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained, Unconscious
cr_line: 2 (XP 450; PB +2)
xp: 450
size: Tiny
type: Undead
alignment: Chaotic Evil
ac: 19
hp: 27
hit_dice: 11d4
speed: 5 ft., Fly 50 ft. (hover)
stats:
- 1
- 28
- 10
- 13
- 14
- 11
damage_resistances: Acid, Bludgeoning, Cold, Fire, Necrotic, Piercing, Slashing
damage_immunities: Lightning, Poison
condition_immunities: Exhaustion, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained, Unconscious
senses: Darkvision 120 ft.; Passive Perception 12
languages: Common plus one other language
cr: '2'
dice: false
traits:
- name: Ephemeral
  desc: The wisp can't wear or carry anything.
- name: Illumination
  desc: The wisp sheds Bright Light in a 20-foot radius and Dim Light for an additional 20 feet.
- name: Incorporeal Movement
  desc: The wisp can move through other creatures and objects as if they were Difficult Terrain. It takes 5 (1d10) Force damage if it ends its turn inside an object.
actions:
- name: Shock
  desc: _Melee Attack Roll:_ +4, reach 5 ft. _Hit:_ 11 (2d8 + 2) Lightning damage.
bonus_actions:
- name: Consume Life
  desc: _Constitution Saving Throw:_ DC 10, one living creature the wisp can see within 5 feet that has 0 Hit Points. _Failure:_ The target dies, and the wisp regains 10 (3d6) Hit Points.
- name: Vanish
  desc: The wisp and its light have the Invisible condition until the wisp's Concentration ends on this effect, which ends early immediately after the wisp makes an attack roll or uses Consume Life.
```
