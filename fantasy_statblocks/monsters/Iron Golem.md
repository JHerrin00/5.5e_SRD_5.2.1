---
statblock: inline
source: SRD 5.2.1
cr: '16'
xp: 15000
type: Construct
initiative_text: +9 (19)
tags:
- srd521/monster
- srd521/type/construct
---

```statblock
layout: Basic 5e Layout
name: Iron Golem
source: SRD 5.2.1
type_line: Large Construct, Unaligned
initiative_line: +9 (19)
modifier: 9
ability_mods:
- 7
- -1
- 5
- -4
- 0
- -5
ability_saves:
- 7
- -1
- 5
- -4
- 0
- -5
immunities: Fire, Poison, Psychic; Charmed, Exhaustion, Frightened, Paralyzed, Petrified, Poisoned
cr_line: 16 (XP 15,000; PB +5)
xp: 15000
size: Large
type: Construct
alignment: Unaligned
ac: 20
hp: 252
hit_dice: 24d10 + 120
speed: 30 ft.
stats:
- 24
- 9
- 20
- 3
- 11
- 1
damage_immunities: Fire, Poison, Psychic
condition_immunities: Charmed, Exhaustion, Frightened, Paralyzed, Petrified, Poisoned
senses: Darkvision 120 ft.; Passive Perception 10
languages: Understands Common plus two other languages but can't speak
cr: '16'
dice: false
traits:
- name: Fire Absorption
  desc: Whenever the golem is subjected to Fire damage, it regains a number of Hit Points equal to the Fire damage dealt.
- name: Immutable Form
  desc: The golem can't shape-shift.
- name: Magic Resistance
  desc: The golem has Advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: The golem makes two attacks, using Bladed Arm or Fiery Bolt in any combination.
- name: Bladed Arm
  desc: _Melee Attack Roll:_ +12, reach 10 ft. _Hit:_ 20 (3d8 + 7) Slashing damage plus 10 (3d6) Fire damage.
- name: Fiery Bolt
  desc: _Ranged Attack Roll:_ +10, range 120 ft. _Hit:_ 36 (8d8) Fire damage.
- name: Poison Breath (Recharge 6)
  desc: _Constitution Saving Throw:_ DC 18, each creature in a 60-foot Cone. _Failure:_ 55 (10d10) Poison damage. _Success:_ Half damage.
```
