---
statblock: inline
source: SRD 5.2.1
cr: '22'
xp: 41000
type: Dragon
initiative_text: +14 (24)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 50000
---

```statblock
layout: Basic 5e Layout
name: Ancient Bronze Dragon
source: SRD 5.2.1
type_line: Gargantuan Dragon (Metallic), Lawful Good
initiative_line: +14 (24)
modifier: 14
ability_mods:
- 9
- 0
- 8
- 4
- 3
- 7
ability_saves:
- 9
- 7
- 8
- 4
- 10
- 7
skills_text: Insight +10, Perception +17, Stealth +7
immunities: Lightning
cr_line: 22 (XP 41,000, or 50,000 in lair; PB +7)
xp: 41000
size: Gargantuan
type: Dragon
subtype: Metallic
alignment: Lawful Good
ac: 22
hp: 444
hit_dice: 24d20 + 192
speed: 40 ft., Fly 80 ft., Swim 40 ft.
stats:
- 29
- 10
- 27
- 18
- 17
- 25
saves:
- dexterity: 7
- wisdom: 10
skillsaves:
- insight: 10
- perception: 17
- stealth: 7
damage_immunities: Lightning
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 27
languages: Common, Draconic
cr: '22'
dice: false
traits:
- name: Amphibious
  desc: The dragon can breathe air and water.
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of (A) Repulsion Breath or (B) Spellcasting to cast _Guiding Bolt_ (level 2 version).
- name: Rend
  desc: _Melee Attack Roll:_ +16, reach 15 ft. _Hit:_ 18 (2d8 + 9) Slashing damage plus 9 (2d8) Lightning damage.
- name: Lightning Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 23, each creature in a 120-foot-long, 10-foot-wide Line. _Failure:_ 82 (15d10) Lightning damage. _Success:_ Half damage.
- name: Repulsion Breath
  desc: _Strength Saving Throw:_ DC 23, each creature in a 30-foot Cone. _Failure:_ The target is pushed up to 60 feet straight away from the dragon and has the Prone condition.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 22, +14 to hit with spell attacks):
    **At Will:** _Detect Magic_, _Guiding Bolt_ (level 2 version), _Shapechange_ (Beast or Humanoid form only, no Temporary Hit Points gained from the spell, and no Concentration or Temporary Hit Points required to maintain the spell), _Speak with Animals_, _Thaumaturgy_
    **1/Day Each:** _Detect Thoughts_, _Control Water_, _Scrying_, _Water Breathing_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Guiding Light
  desc: The dragon uses Spellcasting to cast _Guiding Bolt_ (level 2 version).
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
- name: Thunderclap
  desc: _Constitution Saving Throw:_ DC 22, each creature in a 20-foot-radius Sphere centered on a point the dragon can see within 120 feet. _Failure:_ 13 (3d8) Thunder damage, and the target has the Deafened condition until the end of its next turn.
```
