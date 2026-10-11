---
statblock: inline
source: SRD 5.2.1
cr: '23'
xp: 50000
type: Dragon
initiative_text: +14 (24)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 62000
---

```statblock
layout: Basic 5e Layout
name: Ancient Silver Dragon
source: SRD 5.2.1
type_line: Gargantuan Dragon (Metallic), Lawful Good
initiative_line: +14 (24)
modifier: 14
ability_mods:
- 10
- 0
- 9
- 4
- 2
- 8
ability_saves:
- 10
- 7
- 9
- 4
- 9
- 8
skills_text: History +11, Perception +16, Stealth +7
immunities: Cold
cr_line: 23 (XP 50,000, or 62,000 in lair; PB +7)
xp: 50000
size: Gargantuan
type: Dragon
subtype: Metallic
alignment: Lawful Good
ac: 22
hp: 468
hit_dice: 24d20 + 216
speed: 40 ft., Fly 80 ft.
stats:
- 30
- 10
- 29
- 18
- 15
- 26
saves:
- dexterity: 7
- wisdom: 9
skillsaves:
- history: 11
- perception: 16
- stealth: 7
damage_immunities: Cold
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 26
languages: Common, Draconic
cr: '23'
dice: false
traits:
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of (A) Paralyzing Breath or (B) Spellcasting to cast _Ice Knife_ (level 2 version).
- name: Rend
  desc: _Melee Attack Roll:_ +17, reach 15 ft. _Hit:_ 19 (2d8 + 10) Slashing damage plus 9 (2d8) Cold damage.
- name: Cold Breath (Recharge 5–6)
  desc: _Constitution Saving Throw:_ DC 24, each creature in a 90-foot Cone. _Failure:_ 67 (15d8) Cold damage. _Success:_ Half damage.
- name: Paralyzing Breath
  desc: _Constitution Saving Throw:_ DC 24, each creature in a 90-foot Cone. _First Failure:_ The target has the Incapacitated condition until the end of its next turn, when it repeats the save. _Second Failure:_ The target has the Paralyzed condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 23, +15 to hit with spell attacks):
    **At Will:** _Detect Magic_, _Hold Monster_, _Ice Knife_ (level 2 version), _Shapechange_ (Beast or Humanoid form only, no Temporary Hit Points gained from the spell, and no Concentration or Temporary Hit Points required to maintain the spell)
    **1/Day Each:** _Control Weather_, _Ice Storm_ (level 7 version), _Teleport_, _Zone of Truth_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Chill
  desc: The dragon uses Spellcasting to cast _Hold Monster_. The dragon can't take this action again until the start of its next turn.
- name: Cold Gale
  desc: _Dexterity Saving Throw:_ DC 23, each creature in a 60-foot-long, 10-foot-wide Line. _Failure:_ 14 (4d6) Cold damage, and the target is pushed up to 30 feet straight away from the dragon. _Success:_ Half damage only. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
```
