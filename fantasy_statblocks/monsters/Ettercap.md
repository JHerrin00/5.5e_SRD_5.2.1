---
statblock: inline
source: SRD 5.2.1
cr: '2'
xp: 450
type: Monstrosity
initiative_text: +2 (12)
tags:
- srd521/monster
- srd521/type/monstrosity
---

```statblock
layout: Basic 5e Layout
name: Ettercap
source: SRD 5.2.1
type_line: Medium Monstrosity, Neutral Evil
initiative_line: +2 (12)
modifier: 2
ability_mods:
- 2
- 2
- 1
- -2
- 1
- -1
ability_saves:
- 2
- 2
- 1
- -2
- 1
- -1
skills_text: Perception +3, Stealth +4, Survival +3
cr_line: 2 (XP 450; PB +2)
xp: 450
size: Medium
type: Monstrosity
alignment: Neutral Evil
ac: 13
hp: 44
hit_dice: 8d8 + 8
speed: 30 ft., Climb 30 ft.
stats:
- 14
- 15
- 13
- 7
- 12
- 8
skillsaves:
- perception: 3
- stealth: 4
- survival: 3
senses: Darkvision 60 ft.; Passive Perception 13
languages: None
cr: '2'
dice: false
traits:
- name: Spider Climb
  desc: The ettercap can climb difficult surfaces, including along ceilings, without needing to make an ability check.
- name: Web Walker
  desc: The ettercap ignores movement restrictions caused by webs, and the ettercap knows the location of any other creature in contact with the same web.
actions:
- name: Multiattack
  desc: The ettercap makes one Bite attack and one Claw attack.
- name: Bite
  desc: _Melee Attack Roll:_ +4, reach 5 ft. _Hit:_ 5 (1d6 + 2) Piercing damage plus 2 (1d4) Poison damage, and the target has the Poisoned condition until the start of the ettercap's next turn.
- name: Claw
  desc: _Melee Attack Roll:_ +4, reach 5 ft. _Hit:_ 7 (2d4 + 2) Slashing damage.
- name: Web Strand (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 12, one Large or smaller creature the ettercap can see within 30 feet. _Failure:_ The target has the Restrained condition until the web is destroyed (AC 10; HP 5; Vulnerability to Fire damage; Immunity to Bludgeoning, Poison, and Psychic damage).
bonus_actions:
- name: Reel
  desc: The ettercap pulls one creature within 30 feet of itself that is Restrained by its Web Strand up to 25 feet straight toward itself.
```
