---
statblock: inline
source: SRD 5.2.1
cr: '15'
xp: 13000
type: Dragon
initiative_text: +10 (20)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 15000
---

```statblock
layout: Basic 5e Layout
name: Adult Bronze Dragon
source: SRD 5.2.1
type_line: Huge Dragon (Metallic), Lawful Good
initiative_line: +10 (20)
modifier: 10
ability_mods:
- 7
- 0
- 6
- 3
- 2
- 5
ability_saves:
- 7
- 5
- 6
- 3
- 7
- 5
skills_text: Insight +7, Perception +12, Stealth +5
immunities: Lightning
cr_line: 15 (XP 13,000, or 15,000 in lair; PB +5)
xp: 13000
size: Huge
type: Dragon
subtype: Metallic
alignment: Lawful Good
ac: 18
hp: 212
hit_dice: 17d12 + 102
speed: 40 ft., Fly 80 ft., Swim 40 ft.
stats:
- 25
- 10
- 23
- 16
- 15
- 20
saves:
- dexterity: 5
- wisdom: 7
skillsaves:
- insight: 7
- perception: 12
- stealth: 5
damage_immunities: Lightning
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 22
languages: Common, Draconic
cr: '15'
dice: false
traits:
- name: Amphibious
  desc: The dragon can breathe air and water.
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of (A) Repulsion Breath or (B) Spellcasting to cast _Guiding Bolt_ (level 2 version).
- name: Rend
  desc: _Melee Attack Roll:_ +12, reach 10 ft. _Hit:_ 16 (2d8 + 7) Slashing damage plus 5 (1d10) Lightning damage.
- name: Lightning Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 19, each creature in a 90-foot-long, 5-foot-wide Line. _Failure:_ 55 (10d10) Lightning damage. _Success:_ Half damage.
- name: Repulsion Breath
  desc: _Strength Saving Throw:_ DC 19, each creature in a 30-foot Cone. _Failure:_ The target is pushed up to 60 feet straight away from the dragon and has the Prone condition.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 17, +10 to hit with spell attacks):
    **At Will:** _Detect Magic_, _Guiding Bolt_ (level 2 version), _Shapechange_ (Beast or Humanoid form only, no Temporary Hit Points gained from the spell, and no Concentration or Temporary Hit Points required to maintain the spell), _Speak with Animals_, _Thaumaturgy_
    **1/Day Each:** _Detect Thoughts_, _Water Breathing_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Guiding Light
  desc: The dragon uses Spellcasting to cast _Guiding Bolt_ (level 2 version).
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
- name: Thunderclap
  desc: _Constitution Saving Throw:_ DC 17, each creature in a 20-foot-radius Sphere centered on a point the dragon can see within 90 feet. _Failure:_ 10 (3d6) Thunder damage, and the target has the Deafened condition until the end of its next turn.
```
