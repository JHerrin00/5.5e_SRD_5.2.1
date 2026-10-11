---
statblock: inline
source: SRD 5.2.1
cr: '7'
xp: 2900
type: Giant
initiative_text: +5 (15)
tags:
- srd521/monster
- srd521/type/giant
---

```statblock
layout: Basic 5e Layout
name: Stone Giant
source: SRD 5.2.1
type_line: Huge Giant, Neutral
initiative_line: +5 (15)
modifier: 5
ability_mods:
- 6
- 2
- 5
- 0
- 1
- -1
ability_saves:
- 6
- 5
- 8
- 0
- 4
- -1
skills_text: Athletics +12, Perception +4, Stealth +5
cr_line: 7 (XP 2,900; PB +3)
xp: 2900
size: Huge
type: Giant
alignment: Neutral
ac: 17
hp: 126
hit_dice: 11d12 + 55
speed: 40 ft.
stats:
- 23
- 15
- 20
- 10
- 12
- 9
saves:
- dexterity: 5
- constitution: 8
- wisdom: 4
skillsaves:
- athletics: 12
- perception: 4
- stealth: 5
senses: Darkvision 60 ft.; Passive Perception 14
languages: Giant
cr: '7'
dice: false
actions:
- name: Multiattack
  desc: The giant makes two attacks, using Stone Club or Boulder in any combination.
- name: Stone Club
  desc: _Melee Attack Roll:_ +9, reach 15 ft. _Hit:_ 22 (3d10 + 6) Bludgeoning damage.
- name: Boulder
  desc: _Ranged Attack Roll:_ +9, range 60/240 ft. _Hit:_ 15 (2d8 + 6) Bludgeoning damage. If the target is a Large or smaller creature, it has the Prone condition.
reactions:
- name: Deflect Missile (Recharge 5–6)
  desc: _Trigger:_ The giant is hit by a ranged attack roll and takes Bludgeoning, Piercing, or Slashing damage from it. _Response:_ The giant reduces the damage it takes from the attack by 11 (1d10 + 6), and if that damage is reduced to 0, the giant can redirect some of the attack's force. _Dexterity Saving Throw:_ DC 17, one creature the giant can see within 60 feet. _Failure:_ 11 (1d10 + 6) Force damage.
```
