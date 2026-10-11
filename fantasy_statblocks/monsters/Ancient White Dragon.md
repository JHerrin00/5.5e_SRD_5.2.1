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
name: Ancient White Dragon
source: SRD 5.2.1
type_line: Gargantuan Dragon (Chromatic), Chaotic Evil
initiative_line: +12 (22)
modifier: 12
ability_mods:
- 8
- 0
- 8
- 0
- 1
- 4
ability_saves:
- 8
- 6
- 8
- 0
- 7
- 4
skills_text: Perception +13, Stealth +6
immunities: Cold
cr_line: 20 (XP 25,000, or 33,000 in lair; PB +6)
xp: 25000
size: Gargantuan
type: Dragon
subtype: Chromatic
alignment: Chaotic Evil
ac: 20
hp: 333
hit_dice: 18d20 + 144
speed: 40 ft., Burrow 40 ft., Fly 80 ft., Swim 40 ft.
stats:
- 26
- 10
- 26
- 10
- 13
- 18
saves:
- dexterity: 6
- wisdom: 7
skillsaves:
- perception: 13
- stealth: 6
damage_immunities: Cold
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 23
languages: Common, Draconic
cr: '20'
dice: false
traits:
- name: Ice Walk
  desc: The dragon can move across and climb icy surfaces without needing to make an ability check. Additionally, Difficult Terrain composed of ice or snow doesn't cost it extra movement.
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks.
- name: Rend
  desc: _Melee Attack Roll:_ +14, reach 15 ft. _Hit:_ 17 (2d8 + 8) Slashing damage plus 7 (2d6) Cold damage.
- name: Cold Breath (Recharge 5–6)
  desc: _Constitution Saving Throw:_ DC 22, each creature in a 90-foot Cone. _Failure:_ 63 (14d8) Cold damage. _Success:_ Half damage.
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Freezing Burst
  desc: _Constitution Saving Throw:_ DC 20, each creature in a 30-foot-radius Sphere centered on a point the dragon can see within 120 feet. _Failure:_ 14 (4d6) Cold damage, and the target's Speed is 0 until the end of the target's next turn. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
- name: Frightful Presence
  desc: The dragon casts _Fear_, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 18). The dragon can't take this action again until the start of its next turn.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
```
