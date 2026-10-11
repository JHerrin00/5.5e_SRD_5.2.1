---
statblock: inline
source: SRD 5.2.1
cr: '16'
xp: 15000
type: Fiend
initiative_text: +10 (20)
tags:
- srd521/monster
- srd521/type/fiend
---

```statblock
layout: Basic 5e Layout
name: Marilith
source: SRD 5.2.1
type_line: Large Fiend (Demon), Chaotic Evil
initiative_line: +10 (20)
modifier: 10
ability_mods:
- 4
- 5
- 5
- 4
- 3
- 5
ability_saves:
- 9
- 5
- 10
- 4
- 8
- 10
skills_text: Perception +8
resistances: Cold, Fire, Lightning
immunities: Poison; Poisoned
cr_line: 16 (XP 15,000; PB +5)
xp: 15000
size: Large
type: Fiend
subtype: Demon
alignment: Chaotic Evil
ac: 16
hp: 220
hit_dice: 21d10 + 105
speed: 40 ft., Climb 40 ft.
stats:
- 18
- 20
- 20
- 18
- 16
- 20
saves:
- strength: 9
- constitution: 10
- wisdom: 8
- charisma: 10
skillsaves:
- perception: 8
damage_resistances: Cold, Fire, Lightning
damage_immunities: Poison
condition_immunities: Poisoned
senses: Truesight 120 ft.; Passive Perception 18
languages: Abyssal; telepathy 120 ft.
cr: '16'
dice: false
traits:
- name: Demonic Restoration
  desc: If the marilith dies outside the Abyss, its body dissolves into ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Abyss.
- name: Magic Resistance
  desc: The marilith has Advantage on saving throws against spells and other magical effects.
- name: Reactive
  desc: The marilith can take one Reaction on every turn of combat.
actions:
- name: Multiattack
  desc: The marilith makes six Pact Blade attacks and uses Constrict.
- name: Pact Blade
  desc: _Melee Attack Roll:_ +10, reach 5 ft. _Hit:_ 10 (1d10 + 5) Slashing damage plus 7 (2d6) Necrotic damage.
- name: Constrict
  desc: _Strength Saving Throw:_ DC 17, one Medium or smaller creature the marilith can see within 5 feet. _Failure:_ 15 (2d10 + 4) Bludgeoning damage. The target has the Grappled condition (escape DC 14), and it has the Restrained condition until the grapple ends.
bonus_actions:
- name: Teleport (Recharge 5–6)
  desc: The marilith teleports up to 120 feet to an unoccupied space it can see.
reactions:
- name: Parry
  desc: _Trigger:_ The marilith is hit by a melee attack roll while holding a weapon. _Response:_ The marilith adds 5 to its AC against that attack, possibly causing it to miss.
```
