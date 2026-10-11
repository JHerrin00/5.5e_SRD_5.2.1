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
name: Incubus
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
hp: 66
hit_dice: 12d8 + 12
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
- name: Succubus Form
  desc: When the incubus finishes a Long Rest, it can shape-shift into a **Succubus**, using that stat block instead of this one. Any equipment it is wearing or carrying isn't transformed.
actions:
- name: Multiattack
  desc: The incubus makes two Restless Touch attacks.
- name: Restless Touch
  desc: _Melee Attack Roll:_ +7, reach 5 ft. _Hit:_ 15 (3d6 + 5) Psychic damage, and the target is cursed for 24 hours or until the incubus dies. Until the curse ends, the target gains no benefit from finishing Short Rests.
- name: Spellcasting
  desc: |-
    The incubus casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 15):
    **At Will:** _Disguise Self_, _Etherealness_
    **1/Day Each:** _Dream_, _Hypnotic Pattern_
bonus_actions:
- name: Nightmare (Recharge 6)
  desc: _Wisdom Saving Throw:_ DC 15, one creature the incubus can see within 60 feet. _Failure:_ If the target has 20 Hit Points or fewer, it has the Unconscious condition for 1 hour, until it takes damage, or until a creature within 5 feet of it takes an action to wake it. Otherwise, the target takes 18 (4d8) Psychic damage.
```
