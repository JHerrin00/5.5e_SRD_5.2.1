---
statblock: inline
source: SRD 5.2.1
cr: 1/2
xp: 100
type: Monstrosity
initiative_text: +1 (11)
tags:
- srd521/monster
- srd521/type/monstrosity
---

```statblock
layout: Basic 5e Layout
name: Rust Monster
source: SRD 5.2.1
type_line: Medium Monstrosity, Unaligned
initiative_line: +1 (11)
modifier: 1
ability_mods:
- 1
- 1
- 1
- -4
- 1
- -2
ability_saves:
- 1
- 1
- 1
- -4
- 1
- -2
cr_line: 1/2 (XP 100; PB +2)
xp: 100
size: Medium
type: Monstrosity
alignment: Unaligned
ac: 14
hp: 33
hit_dice: 6d8 + 6
speed: 40 ft.
stats:
- 13
- 12
- 13
- 2
- 13
- 6
senses: Darkvision 60 ft.; Passive Perception 11
languages: None
cr: 1/2
dice: false
traits:
- name: Iron Scent
  desc: The rust monster can pinpoint the location of ferrous metal within 30 feet of itself.
actions:
- name: Multiattack
  desc: The rust monster makes one Bite attack and uses Antennae twice.
- name: Bite
  desc: _Melee Attack Roll:_ +3, reach 5 ft. _Hit:_ 5 (1d8 + 1) Piercing damage.
- name: Antennae
  desc: The rust monster targets one nonmagical metal object—armor or a weapon—worn or carried by a creature within 5 feet of itself. _Dexterity Saving Throw:_ DC 11, the creature with the object. _Failure:_ The object takes a -1 penalty to the AC it offers (armor) or to its attack rolls (weapon). Armor is destroyed if the penalty reduces its AC to 10, and a weapon is destroyed if its penalty reaches -5. The penalty can be removed by casting the _Mending_ spell on the armor or weapon.
- name: Destroy Metal
  desc: The rust monster touches a nonmagical metal object within 5 feet of itself that isn't being worn or carried. The touch destroys a 1-foot Cube of the object.
reactions:
- name: Reflexive Antennae
  desc: _Trigger:_ An attack roll hits the rust monster. _Response:_ The rust monster uses Antennae.
```
