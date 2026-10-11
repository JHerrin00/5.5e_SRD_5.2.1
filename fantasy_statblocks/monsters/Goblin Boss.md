---
statblock: inline
source: SRD 5.2.1
cr: '1'
xp: 200
type: Fey
initiative_text: +2 (12)
tags:
- srd521/monster
- srd521/type/fey
---

```statblock
layout: Basic 5e Layout
name: Goblin Boss
source: SRD 5.2.1
type_line: Small Fey (Goblinoid), Chaotic Neutral
initiative_line: +2 (12)
modifier: 2
ability_mods:
- 0
- 2
- 0
- 0
- -1
- 0
ability_saves:
- 0
- 2
- 0
- 0
- -1
- 0
skills_text: Stealth +6
cr_line: 1 (XP 200; PB +2)
xp: 200
size: Small
type: Fey
subtype: Goblinoid
alignment: Chaotic Neutral
ac: 17
hp: 21
hit_dice: 6d6
speed: 30 ft.
stats:
- 10
- 15
- 10
- 10
- 8
- 10
skillsaves:
- stealth: 6
gear: Chain Shirt, Scimitar, Shield, Shortbow
senses: Darkvision 60 ft.; Passive Perception 9
languages: Common, Goblin
cr: '1'
dice: false
actions:
- name: Multiattack
  desc: The goblin makes two attacks, using Scimitar or Shortbow in any combination.
- name: Scimitar
  desc: _Melee Attack Roll:_ +4, reach 5 ft. _Hit:_ 5 (1d6 + 2) Slashing damage, plus 2 (1d4) Slashing damage if the attack roll had Advantage.
- name: Shortbow
  desc: _Ranged Attack Roll:_ +4, range 80/320 ft. _Hit:_ 5 (1d6 + 2) Piercing damage, plus 2 (1d4) Piercing damage if the attack roll had Advantage.
bonus_actions:
- name: Nimble Escape
  desc: The goblin takes the Disengage or Hide action.
reactions:
- name: Redirect Attack
  desc: _Trigger:_ A creature the goblin can see makes an attack roll against it. _Response:_ The goblin chooses a Small or Medium ally within 5 feet of itself. The goblin and that ally swap places, and the ally becomes the target of the attack instead.
```
