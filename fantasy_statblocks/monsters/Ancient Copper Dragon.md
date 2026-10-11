---
statblock: inline
source: SRD 5.2.1
cr: '21'
xp: 33000
type: Dragon
initiative_text: +15 (25)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 41000
---

```statblock
layout: Basic 5e Layout
name: Ancient Copper Dragon
source: SRD 5.2.1
type_line: Gargantuan Dragon (Metallic), Chaotic Good
initiative_line: +15 (25)
modifier: 15
ability_mods:
- 8
- 1
- 7
- 5
- 3
- 6
ability_saves:
- 8
- 8
- 7
- 5
- 10
- 6
skills_text: Deception +13, Perception +17, Stealth +8
immunities: Acid
cr_line: 21 (XP 33,000, or 41,000 in lair; PB +7)
xp: 33000
size: Gargantuan
type: Dragon
subtype: Metallic
alignment: Chaotic Good
ac: 21
hp: 367
hit_dice: 21d20 + 147
speed: 40 ft., Climb 40 ft., Fly 80 ft.
stats:
- 27
- 12
- 25
- 20
- 17
- 22
saves:
- dexterity: 8
- wisdom: 10
skillsaves:
- deception: 13
- perception: 17
- stealth: 8
damage_immunities: Acid
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 27
languages: Common, Draconic
cr: '21'
dice: false
traits:
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of (A) Slowing Breath or (B) Spellcasting to cast _Mind Spike_ (level 5 version).
- name: Rend
  desc: _Melee Attack Roll:_ +15, reach 15 ft. _Hit:_ 19 (2d10 + 8) Slashing damage plus 9 (2d8) Acid damage.
- name: Acid Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 22, each creature in an 90-foot-long, 10-foot-wide Line. _Failure:_ 63 (14d8) Acid damage. _Success:_ Half damage.
- name: Slowing Breath
  desc: _Constitution Saving Throw:_ DC 22, each creature in a 90-foot Cone. _Failure:_ The target can't take Reactions; its Speed is halved; and it can take either an action or a Bonus Action on its turn, not both. This effect lasts until the end of its next turn.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 21):
    **At Will:** _Detect Magic_, _Mind Spike_ (level 5 version), _Minor Illusion_, _Shapechange_ (Beast or Humanoid form only, no Temporary Hit Points gained from the spell, and no Concentration or Temporary Hit Points required to maintain the spell)
    **1/Day Each:** _Greater Restoration_, _Major Image_, _Project Image_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Giggling Magic
  desc: _Charisma Saving Throw:_ DC 21, one creature the dragon can see within 120 feet. _Failure:_ 31 (9d6) Psychic damage. Until the end of its next turn, the target rolls 1d8 whenever it makes an ability check or attack roll and subtracts the number rolled from the D20 Test. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
- name: Mind Jolt
  desc: The dragon uses Spellcasting to cast _Mind Spike_ (level 5 version). The dragon can't take this action again until the start of its next turn.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
```
