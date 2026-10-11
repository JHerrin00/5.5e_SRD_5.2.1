---
statblock: inline
source: SRD 5.2.1
cr: '14'
xp: 11500
type: Dragon
initiative_text: +12 (22)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 13000
---

```statblock
layout: Basic 5e Layout
name: Adult Black Dragon
source: SRD 5.2.1
type_line: Huge Dragon (Chromatic), Chaotic Evil
initiative_line: +12 (22)
modifier: 12
ability_mods:
- 6
- 2
- 5
- 2
- 1
- 4
ability_saves:
- 6
- 7
- 5
- 2
- 6
- 4
skills_text: Perception +11, Stealth +7
immunities: Acid
cr_line: 14 (XP 11,500, or 13,000 in lair; PB +5)
xp: 11500
size: Huge
type: Dragon
subtype: Chromatic
alignment: Chaotic Evil
ac: 19
hp: 195
hit_dice: 17d12 + 85
speed: 40 ft., Fly 80 ft., Swim 40 ft.
stats:
- 23
- 14
- 21
- 14
- 13
- 19
saves:
- dexterity: 7
- wisdom: 6
skillsaves:
- perception: 11
- stealth: 7
damage_immunities: Acid
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 21
languages: Common, Draconic
cr: '14'
dice: false
traits:
- name: Amphibious
  desc: The dragon can breathe air and water.
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast _Acid Arrow_ (level 3 version).
- name: Rend
  desc: _Melee Attack Roll:_ +11, reach 10 ft. _Hit:_ 13 (2d6 + 6) Slashing damage plus 4 (1d8) Acid damage.
- name: Acid Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 18, each creature in a 60-foot-long, 5-foot-wide Line. _Failure:_ 54 (12d8) Acid damage. _Success:_ Half damage.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 17, +9 to hit with spell attacks):
    **At Will:** _Acid Arrow_ (level 3 version), _Detect Magic_, _Fear_
    **1/Day Each:** _Speak with Dead_, _Vitriolic Sphere_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Cloud of Insects
  desc: _Dexterity Saving Throw:_ DC 17, one creature the dragon can see within 120 feet. _Failure:_ 22 (4d10) Poison damage, and the target has Disadvantage on saving throws to maintain Concentration until the end of its next turn. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
- name: Frightful Presence
  desc: The dragon uses Spellcasting to cast _Fear_. The dragon can't take this action again until the start of its next turn.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
```
