---
statblock: inline
source: SRD 5.2.1
cr: '16'
xp: 15000
type: Dragon
initiative_text: +10 (20)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 18000
---

```statblock
layout: Basic 5e Layout
name: Adult Silver Dragon
source: SRD 5.2.1
type_line: Huge Dragon (Metallic), Lawful Good
initiative_line: +10 (20)
modifier: 10
ability_mods:
- 8
- 0
- 7
- 3
- 1
- 6
ability_saves:
- 8
- 5
- 7
- 3
- 6
- 6
skills_text: History +8, Perception +11, Stealth +5
immunities: Cold
cr_line: 16 (XP 15,000, or 18,000 in lair; PB +5)
xp: 15000
size: Huge
type: Dragon
subtype: Metallic
alignment: Lawful Good
ac: 19
hp: 216
hit_dice: 16d12 + 112
speed: 40 ft., Fly 80 ft.
stats:
- 27
- 10
- 25
- 16
- 13
- 22
saves:
- dexterity: 5
- wisdom: 6
skillsaves:
- history: 8
- perception: 11
- stealth: 5
damage_immunities: Cold
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 21
languages: Common, Draconic
cr: '16'
dice: false
traits:
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of (A) Paralyzing Breath or (B) Spellcasting to cast _Ice Knife_.
- name: Rend
  desc: _Melee Attack Roll:_ +13, reach 10 ft. _Hit:_ 17 (2d8 + 8) Slashing damage plus 4 (1d8) Cold damage.
- name: Cold Breath (Recharge 5–6)
  desc: _Constitution Saving Throw:_ DC 20, each creature in a 60-foot Cone. _Failure:_ 54 (12d8) Cold damage. _Success:_ Half damage.
- name: Paralyzing Breath
  desc: _Constitution Saving Throw:_ DC 20, each creature in a 60-foot Cone. _First Failure:_ The target has the Incapacitated condition until the end of its next turn, when it repeats the save. _Second Failure:_ The target has the Paralyzed condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 19, +11 to hit with spell attacks):
    **At Will:** _Detect Magic_, _Hold Monster_, _Ice Knife_, _Shapechange_ (Beast or Humanoid form only, no Temporary Hit Points gained from the spell, and no Concentration or Temporary Hit Points required to maintain the spell)
    **1/Day Each:** _Ice Storm_ (level 5 version), _Zone of Truth_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Chill
  desc: The dragon uses Spellcasting to cast _Hold Monster_. The dragon can't take this action again until the start of its next turn.
- name: Cold Gale
  desc: _Dexterity Saving Throw:_ DC 19, each creature in a 60-foot-long, 10-foot-wide Line. _Failure:_ 14 (4d6) Cold damage, and the target is pushed up to 30 feet straight away from the dragon. _Success:_ Half damage only. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
```
