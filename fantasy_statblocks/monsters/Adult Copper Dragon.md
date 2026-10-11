---
statblock: inline
source: SRD 5.2.1
cr: '14'
xp: 11500
type: Dragon
initiative_text: +11 (21)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 13000
---

```statblock
layout: Basic 5e Layout
name: Adult Copper Dragon
source: SRD 5.2.1
type_line: Huge Dragon (Metallic), Chaotic Good
initiative_line: +11 (21)
modifier: 11
ability_mods:
- 6
- 1
- 5
- 4
- 2
- 4
ability_saves:
- 6
- 6
- 5
- 4
- 7
- 4
skills_text: Deception +9, Perception +12, Stealth +6
immunities: Acid
cr_line: 14 (XP 11,500, or 13,000 in lair; PB +5)
xp: 11500
size: Huge
type: Dragon
subtype: Metallic
alignment: Chaotic Good
ac: 18
hp: 184
hit_dice: 16d12 + 80
speed: 40 ft., Climb 40 ft., Fly 80 ft.
stats:
- 23
- 12
- 21
- 18
- 15
- 18
saves:
- dexterity: 6
- wisdom: 7
skillsaves:
- deception: 9
- perception: 12
- stealth: 6
damage_immunities: Acid
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 22
languages: Common, Draconic
cr: '14'
dice: false
traits:
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of (A) Slowing Breath or (B) Spellcasting to cast _Mind Spike_ (level 4 version).
- name: Rend
  desc: _Melee Attack Roll:_ +11, reach 10 ft. _Hit:_ 17 (2d10 + 6) Slashing damage plus 4 (1d8) Acid damage.
- name: Acid Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 18, each creature in an 60-foot-long, 5-foot-wide Line. _Failure:_ 54 (12d8) Acid damage. _Success:_ Half damage.
- name: Slowing Breath
  desc: _Constitution Saving Throw:_ DC 18, each creature in a 60-foot Cone. _Failure:_ The target can't take Reactions; its Speed is halved; and it can take either an action or a Bonus Action on its turn, not both. This effect lasts until the end of its next turn.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 17):
    **At Will:** _Detect Magic_, _Mind Spike_ (level 4 version), _Minor Illusion_, _Shapechange_ (Beast or Humanoid form only, no Temporary Hit Points gained from the spell, and no Concentration or Temporary Hit Points required to maintain the spell)
    **1/Day Each:** _Greater Restoration_, _Major Image_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Giggling Magic
  desc: _Charisma Saving Throw:_ DC 17, one creature the dragon can see within 90 feet. _Failure:_ 24 (7d6) Psychic damage. Until the end of its next turn, the target rolls 1d6 whenever it makes an ability check or attack roll and subtracts the number rolled from the D20 Test. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
- name: Mind Jolt
  desc: The dragon uses Spellcasting to cast _Mind Spike_ (level 4 version). The dragon can't take this action again until the start of its next turn.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
```
