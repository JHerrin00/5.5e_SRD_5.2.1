---
statblock: inline
source: SRD 5.2.1
cr: '6'
xp: 2300
type: Humanoid
initiative_text: +7 (17)
tags:
- srd521/monster
- srd521/type/humanoid
---

```statblock
layout: Basic 5e Layout
name: Pirate Captain
source: SRD 5.2.1
type_line: Medium or Small Humanoid, Neutral
initiative_line: +7 (17)
modifier: 7
ability_mods:
- 0
- 4
- 2
- 0
- 2
- 3
ability_saves:
- 3
- 7
- 2
- 0
- 5
- 6
skills_text: Acrobatics +7, Perception +5
cr_line: 6 (XP 2,300; PB +3)
xp: 2300
size: Medium or Small
type: Humanoid
alignment: Neutral
ac: 17
hp: 84
hit_dice: 13d8 + 26
speed: 30 ft.
stats:
- 10
- 18
- 14
- 10
- 14
- 17
saves:
- strength: 3
- dexterity: 7
- wisdom: 5
- charisma: 6
skillsaves:
- acrobatics: 7
- perception: 5
gear: Pistol, Rapier
senses: Passive Perception 15
languages: Common plus one other language
cr: '6'
dice: false
actions:
- name: Multiattack
  desc: The pirate makes three attacks, using Rapier or Pistol in any combination.
- name: Rapier
  desc: _Melee Attack Roll:_ +7, reach 5 ft. _Hit:_ 13 (2d8 + 4) Piercing damage, and the pirate has Advantage on the next attack roll it makes before the end of this turn.
- name: Pistol
  desc: _Ranged Attack Roll:_ +7, range 30/90 ft. _Hit:_ 15 (2d10 + 4) Piercing damage.
bonus_actions:
- name: Captain's Charm
  desc: _Wisdom Saving Throw:_ DC 14, one creature the pirate can see within 30 feet. _Failure:_ The target has the Charmed condition until the start of the pirate's next turn.
reactions:
- name: Riposte
  desc: _Trigger:_ The pirate is hit by a melee attack roll while holding a weapon. _Response:_ The pirate adds 3 to its AC against that attack, possibly causing it to miss. On a miss, the pirate makes one Rapier attack against the triggering creature if within range.
```
