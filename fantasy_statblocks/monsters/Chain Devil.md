---
statblock: inline
source: SRD 5.2.1
cr: '8'
xp: 3900
type: Fiend
initiative_text: +5 (15)
tags:
- srd521/monster
- srd521/type/fiend
---

```statblock
layout: Basic 5e Layout
name: Chain Devil
source: SRD 5.2.1
type_line: Medium Fiend (Devil), Lawful Evil
initiative_line: +5 (15)
modifier: 5
ability_mods:
- 4
- 2
- 4
- 0
- 1
- 2
ability_saves:
- 4
- 2
- 7
- 0
- 4
- 2
resistances: Bludgeoning, Cold, Piercing, Slashing
immunities: Fire, Poison; Poisoned
cr_line: 8 (XP 3,900; PB +3)
xp: 3900
size: Medium
type: Fiend
subtype: Devil
alignment: Lawful Evil
ac: 15
hp: 85
hit_dice: 10d8 + 40
speed: 30 ft.
stats:
- 18
- 15
- 18
- 11
- 12
- 14
saves:
- constitution: 7
- wisdom: 4
damage_resistances: Bludgeoning, Cold, Piercing, Slashing
damage_immunities: Fire, Poison
condition_immunities: Poisoned
senses: Darkvision 120 ft. (unimpeded by magical Darkness); Passive Perception 11
languages: Infernal; telepathy 120 ft.
cr: '8'
dice: false
traits:
- name: Diabolical Restoration
  desc: If the devil dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.
- name: Magic Resistance
  desc: The devil has Advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: The devil makes two Chain attacks and uses Conjure Infernal Chain.
- name: Chain
  desc: _Melee Attack Roll:_ +7, reach 10 ft. _Hit:_ 11 (2d6 + 4) Slashing damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14) from one of two chains, and it has the Restrained condition until the grapple ends.
- name: Conjure Infernal Chain
  desc: The devil conjures a fiery chain to bind a creature. _Dexterity Saving Throw:_ DC 15, one creature the devil can see within 60 feet. _Failure:_ 9 (2d4 + 4) Fire damage, and the target has the Restrained condition until the end of the devil's next turn, at which point the chain disappears. If the target is Large or smaller, the devil moves the target up to 30 feet straight toward itself. _Success:_ The chain disappears.
reactions:
- name: Unnerving Gaze
  desc: _Trigger:_ A creature the devil can see starts its turn within 30 feet of the devil and can see the devil. _Response—Wisdom Saving Throw:_ DC 15, the triggering creature. _Failure:_ The target has the Frightened condition until the end of its turn. _Success:_ The target is immune to this devil's Unnerving Gaze for 24 hours.
```
