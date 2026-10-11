---
statblock: inline
source: SRD 5.2.1
cr: 1/2
xp: 100
type: Undead
initiative_text: +2 (12)
tags:
- srd521/monster
- srd521/type/undead
---

```statblock
layout: Basic 5e Layout
name: Shadow
source: SRD 5.2.1
type_line: Medium Undead, Chaotic Evil
initiative_line: +2 (12)
modifier: 2
ability_mods:
- -2
- 2
- 1
- -2
- 0
- -1
ability_saves:
- -2
- 2
- 1
- -2
- 0
- -1
skills_text: Stealth +6
vulnerabilities: Radiant
resistances: Acid, Cold, Fire, Lightning, Thunder
immunities: Necrotic, Poison; Exhaustion, Frightened, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained, Unconscious
cr_line: 1/2 (XP 100; PB +2)
xp: 100
size: Medium
type: Undead
alignment: Chaotic Evil
ac: 12
hp: 27
hit_dice: 5d8 + 5
speed: 40 ft.
stats:
- 6
- 14
- 13
- 6
- 10
- 8
skillsaves:
- stealth: 6
damage_vulnerabilities: Radiant
damage_resistances: Acid, Cold, Fire, Lightning, Thunder
damage_immunities: Necrotic, Poison
condition_immunities: Exhaustion, Frightened, Grappled, Paralyzed, Petrified, Poisoned, Prone, Restrained, Unconscious
senses: Darkvision 60 ft.; Passive Perception 10
languages: None
cr: 1/2
dice: false
traits:
- name: Amorphous
  desc: The shadow can move through a space as narrow as 1 inch without expending extra movement to do so.
- name: Sunlight Weakness
  desc: While in sunlight, the shadow has Disadvantage on D20 Tests.
actions:
- name: Draining Swipe
  desc: |-
    _Melee Attack Roll:_ +4, reach 5 ft. _Hit:_ 5 (1d6 + 2) Necrotic damage, and the target's Strength score decreases by 1d4. The target dies if this reduces that score to 0. If a Humanoid is slain by this attack, a
    **Shadow** rises from the corpse 1d4 hours later.
bonus_actions:
- name: Shadow Stealth
  desc: While in Dim Light or Darkness, the shadow takes the Hide action.
```
