---
statblock: inline
source: SRD 5.2.1
cr: '5'
xp: 1800
type: Elemental
initiative_text: +3 (13)
tags:
- srd521/monster
- srd521/type/elemental
---

```statblock
layout: Basic 5e Layout
name: Fire Elemental
source: SRD 5.2.1
type_line: Large Elemental, Neutral
initiative_line: +3 (13)
modifier: 3
ability_mods:
- 0
- 3
- 3
- -2
- 0
- -2
ability_saves:
- 0
- 3
- 3
- -2
- 0
- -2
resistances: Bludgeoning, Piercing, Slashing
immunities: Fire, Poison; Exhaustion, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained, Unconscious
cr_line: 5 (XP 1,800; PB +3)
xp: 1800
size: Large
type: Elemental
alignment: Neutral
ac: 13
hp: 93
hit_dice: 11d10 + 33
speed: 50 ft.
stats:
- 10
- 17
- 16
- 6
- 10
- 7
damage_resistances: Bludgeoning, Piercing, Slashing
damage_immunities: Fire, Poison
condition_immunities: Exhaustion, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained, Unconscious
senses: Darkvision 60 ft.; Passive Perception 10
languages: Primordial (Ignan)
cr: '5'
dice: false
traits:
- name: Fire Aura
  desc: At the end of each of the elemental's turns, each creature in a 10-foot Emanation originating from the elemental takes 5 (1d10) Fire damage. Creatures and flammable objects in the Emanation start burning.
- name: Fire Form
  desc: The elemental can move through a space as narrow as 1 inch without expending extra movement to do so, and it can enter a creature's space and stop there. The first time it enters a creature's space on a turn, that creature takes 5 (1d10) Fire damage.
- name: Illumination
  desc: The elemental sheds Bright Light in a 30-foot radius and Dim Light for an additional 30 feet.
- name: Water Susceptibility
  desc: The elemental takes 3 (1d6) Cold damage for every 5 feet the elemental moves in water or for every gallon of water splashed on it.
actions:
- name: Multiattack
  desc: The elemental makes two Burn attacks.
- name: Burn
  desc: _Melee Attack Roll:_ +6, reach 5 ft. _Hit:_ 10 (2d6 + 3) Fire damage. If the target is a creature or a flammable object, it starts burning.
```
