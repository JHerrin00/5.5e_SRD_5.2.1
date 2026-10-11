---
statblock: inline
source: SRD 5.2.1
cr: '17'
xp: 18000
type: Dragon
initiative_text: +14 (24)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 20000
---

```statblock
layout: Basic 5e Layout
name: Adult Gold Dragon
source: SRD 5.2.1
type_line: Huge Dragon (Metallic), Lawful Good
initiative_line: +14 (24)
modifier: 14
ability_mods:
- 8
- 2
- 7
- 3
- 2
- 7
ability_saves:
- 8
- 8
- 7
- 3
- 8
- 7
skills_text: Insight +8, Perception +14, Persuasion +13, Stealth +8
immunities: Fire
cr_line: 17 (XP 18,000, or 20,000 in lair; PB +6)
xp: 18000
size: Huge
type: Dragon
subtype: Metallic
alignment: Lawful Good
ac: 19
hp: 243
hit_dice: 18d12 + 126
speed: 40 ft., Fly 80 ft., Swim 40 ft.
stats:
- 27
- 14
- 25
- 16
- 15
- 24
saves:
- dexterity: 8
- wisdom: 8
skillsaves:
- insight: 8
- perception: 14
- persuasion: 13
- stealth: 8
damage_immunities: Fire
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 24
languages: Common, Draconic
cr: '17'
dice: false
traits:
- name: Amphibious
  desc: The dragon can breathe air and water.
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of (A) Spellcasting to cast _Guiding Bolt_ (level 2 version) or (B) Weakening Breath.
- name: Rend
  desc: _Melee Attack Roll:_ +14, reach 10 ft. _Hit:_ 17 (2d8 + 8) Slashing damage plus 4 (1d8) Fire damage.
- name: Fire Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 21, each creature in a 60-foot Cone. _Failure:_ 66 (12d10) Fire damage. _Success:_ Half damage.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 21, +13 to hit with spell attacks):
    **At Will:** _Detect Magic_, _Guiding Bolt_ (level 2 version), _Shapechange_ (Beast or Humanoid form only, no Temporary Hit Points gained from the spell, and no Concentration or Temporary Hit Points required to maintain the spell)
    **1/Day Each:** _Flame Strike_, _Zone of Truth_
- name: Weakening Breath
  desc: _Strength Saving Throw:_ DC 21, each creature that isn't currently affected by this breath in a 60-foot Cone. _Failure:_ The target has Disadvantage on Strength-based D20 Tests and subtracts 3 (1d6) from its damage rolls. It repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Banish
  desc: _Charisma Saving Throw:_ DC 21, one creature the dragon can see within 120 feet. _Failure:_ 10 (3d6) Force damage, and the target has the Incapacitated condition and is transported to a harmless demiplane until the start of the dragon's next turn, at which point it reappears in an unoccupied space of the dragon's choice within 120 feet of the dragon. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
- name: Guiding Light
  desc: The dragon uses Spellcasting to cast _Guiding Bolt_ (level 2 version).
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
```
