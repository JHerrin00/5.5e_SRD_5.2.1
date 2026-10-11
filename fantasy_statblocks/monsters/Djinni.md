---
statblock: inline
source: SRD 5.2.1
cr: '11'
xp: 7200
type: Elemental
initiative_text: +2 (12)
tags:
- srd521/monster
- srd521/type/elemental
---

```statblock
layout: Basic 5e Layout
name: Djinni
source: SRD 5.2.1
type_line: Large Elemental (Genie), Neutral
initiative_line: +2 (12)
modifier: 2
ability_mods:
- 5
- 2
- 6
- 2
- 3
- 5
ability_saves:
- 5
- 6
- 6
- 2
- 7
- 5
immunities: Lightning, Thunder
cr_line: 11 (XP 7,200; PB +4)
xp: 7200
size: Large
type: Elemental
subtype: Genie
alignment: Neutral
ac: 17
hp: 218
hit_dice: 19d10 + 114
speed: 30 ft., Fly 90 ft. (hover)
stats:
- 21
- 15
- 22
- 15
- 16
- 20
saves:
- dexterity: 6
- wisdom: 7
damage_immunities: Lightning, Thunder
senses: Darkvision 120 ft.; Passive Perception 13
languages: Primordial (Auran)
cr: '11'
dice: false
traits:
- name: Elemental Restoration
  desc: If the djinni dies outside the Elemental Plane of Air, its body dissolves into mist, and it gains a new body in 1d4 days, reviving with all its Hit Points somewhere on the Plane of Air.
- name: Magic Resistance
  desc: The djinni has Advantage on saving throws against spells and other magical effects.
- name: Wishes
  desc: The djinni has a 30 percent chance of knowing the _Wish_ spell. If the djinni knows it, the djinni can cast it only on behalf of a non-genie creature who communicates a wish in a way the djinni can understand. If the djinni casts the spell for the creature, the djinni suffers none of the spell's stress. Once the djinni has cast it three times, the djinni can't do so again for 365 days.
actions:
- name: Multiattack
  desc: The djinni makes three attacks, using Storm Blade or Storm Bolt in any combination.
- name: Storm Blade
  desc: _Melee Attack Roll:_ +9, reach 5 feet. _Hit:_ 12 (2d6 + 5) Slashing damage plus 7 (2d6) Lightning damage.
- name: Storm Bolt
  desc: _Ranged Attack Roll:_ +9, range 120 feet. _Hit:_ 13 (3d8) Thunder damage. If the target is a Large or smaller creature, it has the Prone condition.
- name: Create Whirlwind
  desc: |-
    The djinni conjures a whirlwind at a point it can see within 120 feet. The whirlwind fills a 20-foot-radius, 60-foot-high Cylinder centered on that point. The whirlwind lasts until the djinni's Concentration on it ends. The djinni can move the whirlwind up to 20 feet at the start of each of its turns.
    Whenever the whirlwind enters a creature's space or a creature enters the whirlwind, that creature is subjected to the following effect. _Strength Saving Throw:_ DC 17 (a creature makes this save only once per turn, and the djinni is unaffected). _Failure:_ While in the whirlwind, the target has the Restrained condition and moves with the whirlwind. At the start of each of its turns, the Restrained target takes 21 (6d6) Thunder damage. At the end of each of its turns, the target repeats the save, ending the effect on itself on a success.
- name: Spellcasting
  desc: |-
    The djinni casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 17):
    **At Will:** _Detect Evil and Good_, _Detect Magic_
    **2/Day Each:** _Create Food and Water_ (can create wine instead of water), _Tongues_, _Wind Walk_
    **1/Day Each:** _Creation_, _Gaseous Form_, _Invisibility_, _Major Image_, _Plane Shift_
```
