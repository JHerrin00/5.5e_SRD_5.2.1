---
statblock: inline
source: SRD 5.2.1
cr: '4'
xp: 1100
type: Undead
initiative_text: +1 (11)
tags:
- srd521/monster
- srd521/type/undead
---

```statblock
layout: Basic 5e Layout
name: Ghost
source: SRD 5.2.1
type_line: Medium Undead, Neutral
initiative_line: +1 (11)
modifier: 1
ability_mods:
- -2
- 1
- 0
- 0
- 1
- 3
ability_saves:
- -2
- 1
- 0
- 0
- 1
- 3
resistances: Acid, Bludgeoning, Cold, Fire, Lightning, Piercing, Slashing, Thunder
immunities: Necrotic, Poison; Charmed, Exhaustion, Frightened, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained
cr_line: 4 (XP 1,100; PB +2)
xp: 1100
size: Medium
type: Undead
alignment: Neutral
ac: 11
hp: 45
hit_dice: 10d8
speed: 5 ft., Fly 40 ft. (hover)
stats:
- 7
- 13
- 10
- 10
- 12
- 17
damage_resistances: Acid, Bludgeoning, Cold, Fire, Lightning, Piercing, Slashing, Thunder
damage_immunities: Necrotic, Poison
condition_immunities: Charmed, Exhaustion, Frightened, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained
senses: Darkvision 60 ft.; Passive Perception 11
languages: Common plus one other language
cr: '4'
dice: false
traits:
- name: Ethereal Sight
  desc: The ghost can see 60 feet into the Ethereal Plane when it is on the Material Plane.
- name: Incorporeal Movement
  desc: The ghost can move through other creatures and objects as if they were Difficult Terrain. It takes 5 (1d10) Force damage if it ends its turn inside an object.
actions:
- name: Multiattack
  desc: The ghost makes two Withering Touch attacks.
- name: Withering Touch
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 19 (3d10 + 3) Necrotic damage.
- name: Etherealness
  desc: The ghost casts the _Etherealness_ spell, requiring no spell components and using Charisma as the spellcasting ability. The ghost is visible on the Material Plane while on the Border Ethereal and vice versa, but it can't affect or be affected by anything on the other plane.
- name: Horrific Visage
  desc: _Wisdom Saving Throw:_ DC 13, each creature in a 60-foot Cone that can see the ghost and isn't an Undead. _Failure:_ 10 (2d6 + 3) Psychic damage, and the target has the Frightened condition until the start of the ghost's next turn. _Success:_ The target is immune to this ghost's Horrific Visage for 24 hours.
- name: Possession (Recharge 6)
  desc: |-
    _Charisma Saving Throw:_ DC 13, one Humanoid the ghost can see within 5 feet. _Failure:_ The target is possessed by the ghost; the ghost disappears, and the target has the Incapacitated condition and loses control of its body. The ghost now controls the body, but the target retains awareness. The ghost can't be targeted by any attack, spell, or other effect, except ones that specifically target Undead. The ghost's game statistics are the same, except it uses the possessed target's Speed, as well as the target's Strength, Dexterity, and Constitution modifiers.
    The possession lasts until the body drops to 0 Hit Points or the ghost leaves as a Bonus Action. When the possession ends, the ghost appears in an unoccupied space within 5 feet of the target, and the target is immune to this ghost's Possession for 24 hours.
    _Success:_ The target is immune to this ghost's Possession for 24 hours.
```
