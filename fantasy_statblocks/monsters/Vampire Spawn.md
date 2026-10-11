---
statblock: inline
source: SRD 5.2.1
cr: '5'
xp: 1800
type: Undead
initiative_text: +3 (13)
tags:
- srd521/monster
- srd521/type/undead
---

```statblock
layout: Basic 5e Layout
name: Vampire Spawn
source: SRD 5.2.1
type_line: Medium or Small Undead, Neutral Evil
initiative_line: +3 (13)
modifier: 3
ability_mods:
- 3
- 3
- 3
- 0
- 0
- 1
ability_saves:
- 3
- 6
- 3
- 0
- 3
- 1
skills_text: Perception +3, Stealth +6
resistances: Necrotic
cr_line: 5 (XP 1,800; PB +3)
xp: 1800
size: Medium or Small
type: Undead
alignment: Neutral Evil
ac: 16
hp: 90
hit_dice: 12d8 + 36
speed: 30 ft.
stats:
- 16
- 16
- 16
- 11
- 10
- 12
saves:
- dexterity: 6
- wisdom: 3
skillsaves:
- perception: 3
- stealth: 6
damage_resistances: Necrotic
senses: Darkvision 60 ft.; Passive Perception 13
languages: Common plus one other language
cr: '5'
dice: false
traits:
- name: Spider Climb
  desc: The vampire can climb difficult surfaces, including along ceilings, without needing to make an ability check.
- name: Vampire Weakness
  desc: |-
    The vampire has these weaknesses:
    **Forbiddance.** The vampire can't enter a residence without an invitation from an occupant.
    **Running Water.** The vampire takes 20 Acid damage if it ends its turn in running water.
    **Stake to the Heart.** The vampire is destroyed if a weapon that deals Piercing damage is driven into the vampire's heart while the vampire has the Incapacitated condition.
    **Sunlight.** The vampire takes 20 Radiant damage if it starts its turn in sunlight. While in sunlight, it has Disadvantage on attack rolls and ability checks.
actions:
- name: Multiattack
  desc: The vampire makes two Claw attacks and uses Bite.
- name: Claw
  desc: _Melee Attack Roll:_ +6, reach 5 ft. _Hit:_ 8 (2d4 + 3) Slashing damage. If the target is a Medium or smaller creature, it has the Grappled condition (escape DC 13) from one of two claws.
- name: Bite
  desc: _Constitution Saving Throw:_ DC 14, one creature within 5 feet that is willing or that has the Grappled, Incapacitated, or Restrained condition. _Failure:_ 5 (1d4 + 3) Piercing damage plus 10 (3d6) Necrotic damage. The target's Hit Point maximum decreases by an amount equal to the Necrotic damage taken, and the vampire regains Hit Points equal to that amount.
bonus_actions:
- name: Deathless Agility
  desc: The vampire takes the Dash or Disengage action.
```
