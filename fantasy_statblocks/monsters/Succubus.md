---
statblock: inline
source: SRD 5.2.1
cr: '4'
xp: 1100
type: Fiend
initiative_text: +3 (13)
tags:
- srd521/monster
- srd521/type/fiend
---

```statblock
layout: Basic 5e Layout
name: Succubus
source: SRD 5.2.1
type_line: Medium Fiend, Neutral Evil
initiative_line: +3 (13)
modifier: 3
ability_mods:
- -1
- 3
- 1
- 2
- 1
- 5
ability_saves:
- -1
- 3
- 1
- 2
- 1
- 5
skills_text: Deception +9, Insight +5, Perception +5, Persuasion +9, Stealth +7
resistances: Cold, Fire, Poison, Psychic
cr_line: 4 (XP 1,100; PB +2)
xp: 1100
size: Medium
type: Fiend
alignment: Neutral Evil
ac: 15
hp: 71
hit_dice: 13d8 + 13
speed: 30 ft., Fly 60 ft.
stats:
- 8
- 17
- 13
- 15
- 12
- 20
skillsaves:
- deception: 9
- insight: 5
- perception: 5
- persuasion: 9
- stealth: 7
damage_resistances: Cold, Fire, Poison, Psychic
senses: Darkvision 60 ft.; Passive Perception 15
languages: Abyssal, Common, Infernal; telepathy 60 ft.
cr: '4'
dice: false
traits:
- name: Incubus Form
  desc: When the succubus finishes a Long Rest, it can shape-shift into an **Incubus**, using that stat block instead of this one.
actions:
- name: Multiattack
  desc: The succubus makes one Fiendish Touch attack and uses Charm or Draining Kiss.
- name: Fiendish Touch
  desc: _Melee Attack Roll:_ +7, reach 5 ft. _Hit:_ 16 (2d10 + 5) Psychic damage.
- name: Charm
  desc: The succubus casts _Dominate Person_ (level 8 version), requiring no spell components and using Charisma as the spellcasting ability (spell save DC 15).
- name: Draining Kiss
  desc: _Constitution Saving Throw:_ DC 15, one creature Charmed by the succubus within 5 feet. _Failure:_ 13 (3d8) Psychic damage. _Success:_ Half damage. _Failure or Success:_ The target's Hit Point maximum decreases by an amount equal to the damage taken.
bonus_actions:
- name: Shape-Shift
  desc: The succubus shape-shifts into a Medium or Small Humanoid, or it returns to its true form. Its game statistics are the same in each form, except its Fly Speed is available only in its true form. Any equipment it is wearing or carrying isn't transformed.
```
