---
statblock: inline
source: SRD 5.2.1
cr: '5'
xp: 1800
type: Giant
initiative_text: +1 (11)
tags:
- srd521/monster
- srd521/type/giant
---

```statblock
layout: Basic 5e Layout
name: Troll
source: SRD 5.2.1
type_line: Large Giant, Chaotic Evil
initiative_line: +1 (11)
modifier: 1
ability_mods:
- 4
- 1
- 5
- -2
- -1
- -2
ability_saves:
- 4
- 1
- 5
- -2
- -1
- -2
skills_text: Perception +5
cr_line: 5 (XP 1,800; PB +3)
xp: 1800
size: Large
type: Giant
alignment: Chaotic Evil
ac: 15
hp: 94
hit_dice: 9d10 + 45
speed: 30 ft.
stats:
- 18
- 13
- 20
- 7
- 9
- 7
skillsaves:
- perception: 5
senses: Darkvision 60 ft.; Passive Perception 15
languages: Giant
cr: '5'
dice: false
traits:
- name: Loathsome Limbs (4/Day)
  desc: If the troll ends any turn Bloodied and took 15+ Slashing damage during that turn, one of the troll's limbs is severed, falls into the troll's space, and becomes a **Troll Limb**. The limb acts immediately after the troll's turn. The troll has 1 Exhaustion level for each missing limb, and it grows replacement limbs the next time it regains Hit Points.
- name: Regeneration
  desc: The troll regains 15 Hit Points at the start of each of its turns. If the troll takes Acid or Fire damage, this trait doesn't function on the troll's next turn. The troll dies only if it starts its turn with 0 Hit Points and doesn't regenerate.
actions:
- name: Multiattack
  desc: The troll makes three Rend attacks.
- name: Rend
  desc: _Melee Attack Roll:_ +7, reach 10 ft. _Hit:_ 11 (2d6 + 4) Slashing damage.
bonus_actions:
- name: Charge
  desc: The troll moves up to half its Speed straight toward an enemy it can see.
```
