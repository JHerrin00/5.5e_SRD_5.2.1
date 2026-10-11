---
statblock: inline
source: SRD 5.2.1
cr: '4'
xp: 1100
type: Fiend
initiative_text: +1 (11)
tags:
- srd521/monster
- srd521/type/fiend
---

```statblock
layout: Basic 5e Layout
name: Lamia
source: SRD 5.2.1
type_line: Large Fiend, Chaotic Evil
initiative_line: +1 (11)
modifier: 1
ability_mods:
- 3
- 1
- 2
- 2
- 2
- 3
ability_saves:
- 3
- 1
- 2
- 2
- 2
- 3
skills_text: Deception +7, Insight +4, Stealth +5
cr_line: 4 (XP 1,100; PB +2)
xp: 1100
size: Large
type: Fiend
alignment: Chaotic Evil
ac: 13
hp: 97
hit_dice: 13d10 + 26
speed: 40 ft.
stats:
- 16
- 13
- 15
- 14
- 15
- 16
skillsaves:
- deception: 7
- insight: 4
- stealth: 5
senses: Darkvision 60 ft.; Passive Perception 12
languages: Abyssal, Common
cr: '4'
dice: false
actions:
- name: Multiattack
  desc: The lamia makes two Claw attacks. It can replace one attack with a use of Corrupting Touch.
- name: Claw
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 7 (1d8 + 3) Slashing damage plus 7 (2d6) Psychic damage.
- name: Corrupting Touch
  desc: _Wisdom Saving Throw:_ DC 13, one creature the lamia can see within 5 feet. _Failure:_ 13 (3d8) Psychic damage, and the target is cursed for 1 hour. Until the curse ends, the target has the Charmed and Poisoned conditions.
- name: Spellcasting
  desc: |-
    The lamia casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 13):
    **At Will:** _Disguise Self_ (can appear as a Large or Medium biped), _Minor Illusion_
    **1/Day Each:** _Geas_, _Major Image_, _Scrying_
bonus_actions:
- name: Leap
  desc: The lamia jumps up to 30 feet by spending 10 feet of movement.
```
