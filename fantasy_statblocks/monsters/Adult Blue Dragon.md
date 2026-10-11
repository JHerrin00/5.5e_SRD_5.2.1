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
name: Adult Blue Dragon
source: SRD 5.2.1
type_line: Huge Dragon (Chromatic), Lawful Evil
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
skills_text: Perception +12, Stealth +5
immunities: Lightning
cr_line: 16 (XP 15,000, or 18,000 in lair; PB +5)
xp: 15000
size: Huge
type: Dragon
subtype: Chromatic
alignment: Lawful Evil
ac: 19
hp: 212
hit_dice: 17d12 + 102
speed: 40 ft., Burrow 30 ft., Fly 80 ft.
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
- perception: 12
- stealth: 5
damage_immunities: Lightning
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 22
languages: Common, Draconic
cr: '16'
dice: false
traits:
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks. It can replace one attack with a use of Spellcasting to cast _Shatter_.
- name: Rend
  desc: _Melee Attack Roll:_ +12, reach 10 ft. _Hit:_ 16 (2d8 + 7) Slashing damage plus 5 (1d10) Lightning damage.
- name: Lightning Breath (Recharge 5–6)
  desc: _Dexterity Saving Throw:_ DC 19, each creature in a 90-foot-long, 5-foot-wide Line. _Failure:_ 60 (11d10) Lightning damage. _Success:_ Half damage.
- name: Spellcasting
  desc: |-
    The dragon casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 18):
    **At Will:** _Detect Magic_, _Invisibility_, _Mage Hand_, _Shatter_
    **1/Day Each:** _Scrying_, _Sending_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Cloaked Flight
  desc: The dragon uses Spellcasting to cast _Invisibility_ on itself, and it can fly up to half its Fly Speed. The dragon can't take this action again until the start of its next turn.
- name: Sonic Boom
  desc: The dragon uses Spellcasting to cast _Shatter_. The dragon can't take this action again until the start of its next turn.
- name: Tail Swipe
  desc: The dragon makes one Rend attack.
```
