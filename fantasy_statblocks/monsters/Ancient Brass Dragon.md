---
statblock: inline
source: SRD 5.2.1
cr: '20'
xp: 25000
type: Dragon
initiative_text: +12 (22)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 33000
---

```statblock
layout: Basic 5e Layout
name: Ancient Brass Dragon
source: SRD 5.2.1
type_line: Gargantuan Dragon (Metallic), Chaotic Good
initiative_line: +12 (22)
modifier: 12
ability_mods:
- 8
- 0
- 7
- 3
- 2
- 6
ability_saves:
- 8
- 6
- 7
- 3
- 8
- 6
skills_text: History +9, Perception +14, Persuasion +12, Stealth +6
immunities: Fire
cr_line: 20 (XP 25,000, or 33,000 in lair; PB +6)
xp: 25000
size: Gargantuan
type: Dragon
subtype: Metallic
alignment: Chaotic Good
ac: 20
hp: 332
hit_dice: 19d20 + 133
speed: 40 ft., Burrow 40 ft., Fly 80 ft.
stats:
- 27
- 10
- 25
- 16
- 15
- 22
saves:
- dexterity: 6
- wisdom: 8
skillsaves:
- history: 9
- perception: 14
- persuasion: 12
- stealth: 6
damage_immunities: Fire
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 24
languages: Common, Draconic
cr: '20'
dice: false
traits:
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of (A) Sleep Breath or (B) Spellcasting to cast _Scorching Ray_ (level 3 version).
- name: Rend
  desc: _Melee Attack Roll:_ +14, reach 15 ft. _Hit:_ 19 (2d10 + 8) Slashing damage plus 7 (2d6) Fire damage.
- name: Fire Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 21, each creature in a 90-foot-long, 5-foot-wide Line. _Failure:_ 58 (13d8) Fire damage. _Success:_ Half damage.
- name: Sleep Breath
  desc: _Constitution Saving Throw:_ DC 21, each creature in a 90-foot Cone. _Failure:_ The target has the Incapacitated condition until the end of its next turn, at which point it repeats the save. _Second Failure:_ The target has the Unconscious condition for 10 minutes. This effect ends for the target if it takes damage or a creature within 5 feet of it takes an action to wake it.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 20):
    **At Will:** _Detect Magic_, _Minor Illusion_, _Scorching Ray_ (level 3 version), _Shapechange_ (Beast or Humanoid form only, no Temporary Hit Points gained from the spell, and no Concentration or Temporary Hit Points required to maintain the spell), _Speak with Animals_
    **1/Day Each:** _Control Weather_, _Detect Thoughts_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Blazing Light
  desc: The dragon uses Spellcasting to cast _Scorching Ray_ (level 3 version).
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
- name: Scorching Sands
  desc: _Dexterity Saving Throw:_ DC 20, one creature the dragon can see within 120 feet. _Failure:_ 36 (8d8) Fire damage, and the target's Speed is halved until the end of its next turn. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
```
