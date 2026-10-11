---
statblock: inline
source: SRD 5.2.1
cr: '13'
xp: 10000
type: Dragon
initiative_text: +10 (20)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 11500
---

```statblock
layout: Basic 5e Layout
name: Adult Brass Dragon
source: SRD 5.2.1
type_line: Huge Dragon (Metallic), Chaotic Good
initiative_line: +10 (20)
modifier: 10
ability_mods:
- 6
- 0
- 5
- 2
- 1
- 3
ability_saves:
- 6
- 5
- 5
- 2
- 6
- 3
skills_text: History +7, Perception +11, Persuasion +8, Stealth +5
immunities: Fire
cr_line: 13 (XP 10,000, or 11,500 in lair; PB +5)
xp: 10000
size: Huge
type: Dragon
subtype: Metallic
alignment: Chaotic Good
ac: 18
hp: 172
hit_dice: 15d12 + 75
speed: 40 ft., Burrow 30 ft., Fly 80 ft.
stats:
- 23
- 10
- 21
- 14
- 13
- 17
saves:
- dexterity: 5
- wisdom: 6
skillsaves:
- history: 7
- perception: 11
- persuasion: 8
- stealth: 5
damage_immunities: Fire
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 21
languages: Common, Draconic
cr: '13'
dice: false
traits:
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of (A) Sleep Breath or (B) Spellcasting to cast _Scorching Ray_.
- name: Rend
  desc: _Melee Attack Roll:_ +11, reach 10 ft. _Hit:_ 17 (2d10 + 6) Slashing damage plus 4 (1d8) Fire damage.
- name: Fire Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 18, each creature in a 60-foot-long, 5-foot-wide Line. _Failure:_ 45 (10d8) Fire damage. _Success:_ Half damage.
- name: Sleep Breath
  desc: _Constitution Saving Throw:_ DC 18, each creature in a 60-foot Cone. _Failure:_ The target has the Incapacitated condition until the end of its next turn, at which point it repeats the save. _Second Failure:_ The target has the Unconscious condition for 10 minutes. This effect ends for the target if it takes damage or a creature within 5 feet of it takes an action to wake it.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 16):
    **At Will:** _Detect Magic_, _Minor Illusion_, _Scorching Ray_, _Shapechange_ (Beast or Humanoid form only, no Temporary Hit Points gained from the spell, and no Concentration or Temporary Hit Points required to maintain the spell), _Speak with Animals_
    **1/Day Each:** _Detect Thoughts_, _Control Weather_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Blazing Light
  desc: The dragon uses Spellcasting to cast _Scorching Ray_.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
- name: Scorching Sands
  desc: _Dexterity Saving Throw:_ DC 16, one creature the dragon can see within 120 feet. _Failure:_ 27 (6d8) Fire damage, and the target's Speed is halved until the end of its next turn. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
```
