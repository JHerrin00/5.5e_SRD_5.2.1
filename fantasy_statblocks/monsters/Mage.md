---
statblock: inline
source: SRD 5.2.1
cr: '6'
xp: 2300
type: Humanoid
initiative_text: +2 (12)
tags:
- srd521/monster
- srd521/type/humanoid
---

```statblock
layout: Basic 5e Layout
name: Mage
source: SRD 5.2.1
type_line: Medium or Small Humanoid (Wizard), Neutral
initiative_line: +2 (12)
modifier: 2
ability_mods:
- -1
- 2
- 0
- 3
- 1
- 0
ability_saves:
- -1
- 2
- 0
- 6
- 4
- 0
skills_text: Arcana +6, History +6, Perception +4
cr_line: 6 (XP 2,300; PB +3)
xp: 2300
size: Medium or Small
type: Humanoid
subtype: Wizard
alignment: Neutral
ac: 15
hp: 81
hit_dice: 18d8
speed: 30 ft.
stats:
- 9
- 14
- 11
- 17
- 12
- 11
saves:
- intelligence: 6
- wisdom: 4
skillsaves:
- arcana: 6
- history: 6
- perception: 4
gear: Wand
senses: Passive Perception 14
languages: Common plus three other languages
cr: '6'
dice: false
actions:
- name: Multiattack
  desc: The mage makes three Arcane Burst attacks.
- name: Arcane Burst
  desc: _Melee or Ranged Attack Roll:_ +6, reach 5 ft. or range 120 ft. _Hit:_ 16 (3d8 + 3) Force damage.
- name: Spellcasting
  desc: |-
    The mage casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 14):
    **At Will:** _Detect Magic_, _Light_, _Mage Armor_ (included in AC), _Mage Hand_, _Prestidigitation_
    **2/Day Each:** _Fireball_ (level 4 version), _Invisibility_
    **1/Day Each:** _Cone of Cold_, _Fly_
bonus_actions:
- name: Misty Step (3/Day)
  desc: The mage casts _Misty Step_, using the same spellcasting ability as Spellcasting.
reactions:
- name: Protective Magic (3/Day)
  desc: The mage casts _Counterspell_ or _Shield_ in response to the spell's trigger, using the same spellcasting ability as Spellcasting.
```
