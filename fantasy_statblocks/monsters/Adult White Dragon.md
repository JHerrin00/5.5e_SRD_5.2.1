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
name: Adult White Dragon
source: SRD 5.2.1
type_line: Huge Dragon (Chromatic), Chaotic Evil
initiative_line: +10 (20)
modifier: 10
ability_mods:
- 6
- 0
- 6
- -1
- 1
- 1
ability_saves:
- 6
- 5
- 6
- -1
- 6
- 1
skills_text: Perception +11, Stealth +5
immunities: Cold
cr_line: 13 (XP 10,000, or 11,500 in lair; PB +5)
xp: 10000
size: Huge
type: Dragon
subtype: Chromatic
alignment: Chaotic Evil
ac: 18
hp: 200
hit_dice: 16d12 + 96
speed: 40 ft., Burrow 30 ft., Fly 80 ft., Swim 40 ft.
stats:
- 22
- 10
- 22
- 8
- 12
- 12
saves:
- dexterity: 5
- wisdom: 6
skillsaves:
- perception: 11
- stealth: 5
damage_immunities: Cold
senses: Blindsight 60 ft., Darkvision 120 ft.; Passive Perception 21
languages: Common, Draconic
cr: '13'
dice: false
traits:
- name: Ice Walk
  desc: The dragon can move across and climb icy surfaces without needing to make an ability check. Additionally, Difficult Terrain composed of ice or snow doesn't cost it extra movement.
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the dragon fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The dragon makes three Rend attacks.
- name: Rend
  desc: _Melee Attack Roll:_ +11, reach 10 ft. _Hit:_ 13 (2d6 + 6) Slashing damage plus 4 (1d8) Cold damage.
- name: Cold Breath (Recharge 5–6)
  desc: _Constitution Saving Throw:_ DC 19, each creature in a 60-foot Cone. _Failure:_ 54 (12d8) Cold damage. _Success:_ Half damage.
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the dragon can expend a use to take one of the following actions. The dragon regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Freezing Burst
  desc: _Constitution Saving Throw:_ DC 14, each creature in a 30-foot-radius Sphere centered on a point the dragon can see within 120 feet. _Failure:_ 7 (2d6) Cold damage, and the target's Speed is 0 until the end of the target's next turn. _Failure or Success:_ The dragon can't take this action again until the start of its next turn.
- name: Frightful Presence
  desc: The dragon casts _Fear_, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 14). The dragon can't take this action again until the start of its next turn.
- name: Pounce
  desc: The dragon moves up to half its Speed, and it makes one Rend attack.
```
