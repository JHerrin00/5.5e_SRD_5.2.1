---
statblock: inline
source: SRD 5.2.1
cr: '17'
xp: 18000
type: Dragon
initiative_text: +12 (22)
tags:
- srd521/monster
- srd521/type/dragon
xp_lair: 20000
---

```statblock
layout: Basic 5e Layout
name: Adult Red Dragon
source: SRD 5.2.1
type_line: Huge Dragon (Chromatic), Chaotic Evil
initiative_line: +12 (22)
modifier: 12
ability_mods:
- 8
- 0
- 7
- 3
- 1
- 6
ability_saves:
- 8
- 6
- 7
- 3
- 7
- 6
skills_text: Perception +13, Stealth +6
immunities: Fire
cr_line: 17 (XP 18,000, or 20,000 in lair; PB +6)
xp: 18000
size: Huge
type: Dragon
subtype: Chromatic
alignment: Chaotic Evil
ac: 19
hp: 256
hit_dice: 19d12 + 133
speed: 40 ft., Climb 40 ft., Fly 80 ft.
stats:
- 27
- 10
- 25
- 16
- 13
- 23
saves:
- dexterity: 6
- wisdom: 7
skillsaves:
- perception: 13
- stealth: 6
damage_immunities: Fire
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 23
languages: Common, Draconic
cr: '17'
dice: false
traits:
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast _Scorching Ray_.
- name: Rend
  desc: _Melee Attack Roll:_ +14, reach 10 ft. _Hit:_ 13 (1d10 + 8) Slashing damage plus 5 (2d4) Fire damage.
- name: Fire Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 21, each creature in a 60-foot Cone. _Failure:_ 59 (17d6) Fire damage. _Success:_ Half damage.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 20, +12 to hit with spell attacks):
    **At Will:** _Command_ (level 2 version), _Detect Magic_, _Scorching Ray_
    **1/Day:** _Fireball_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Commanding Presence
  desc: The dragon uses Spellcasting to cast _Command_ (level 2 version). The dragon can't take this action again until the start of its next turn.
- name: Fiery Rays
  desc: The dragon uses Spellcasting to cast _Scorching Ray_. The dragon can't take this action again until the start of its next turn.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
```
