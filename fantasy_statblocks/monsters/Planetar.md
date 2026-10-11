---
statblock: inline
source: SRD 5.2.1
cr: '16'
xp: 15000
type: Celestial
initiative_text: +10 (20)
tags:
- srd521/monster
- srd521/type/celestial
---

```statblock
layout: Basic 5e Layout
name: Planetar
source: SRD 5.2.1
type_line: Large Celestial (Angel), Lawful Good
initiative_line: +10 (20)
modifier: 10
ability_mods:
- 7
- 5
- 7
- 4
- 6
- 7
ability_saves:
- 12
- 5
- 12
- 4
- 11
- 12
skills_text: Perception +11
resistances: Radiant
immunities: Charmed, Exhaustion, Frightened
cr_line: 16 (XP 15,000; PB +5)
xp: 15000
size: Large
type: Celestial
subtype: Angel
alignment: Lawful Good
ac: 19
hp: 262
hit_dice: 21d10 + 147
speed: 40 ft., Fly 120 ft. (hover)
stats:
- 24
- 20
- 24
- 19
- 22
- 25
saves:
- strength: 12
- constitution: 12
- wisdom: 11
- charisma: 12
skillsaves:
- perception: 11
damage_resistances: Radiant
condition_immunities: Charmed, Exhaustion, Frightened
senses: Truesight 120 ft.; Passive Perception 21
languages: All; telepathy 120 ft.
cr: '16'
dice: false
traits:
- name: Divine Awareness
  desc: The planetar knows if it hears a lie.
- name: Exalted Restoration
  desc: If the planetar dies outside Mount Celestia, its body disappears, and it gains a new body instantly, reviving with all its Hit Points somewhere in Mount Celestia.
- name: Magic Resistance
  desc: The planetar has Advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: The planetar makes three Radiant Sword attacks or uses Holy Burst twice.
- name: Radiant Sword
  desc: _Melee Attack Roll:_ +12, reach 10 ft. _Hit:_ 14 (2d6 + 7) Slashing damage plus 18 (4d8) Radiant damage.
- name: Holy Burst
  desc: _Dexterity Saving Throw:_ DC 20, each enemy in a 20-foot-radius Sphere centered on a point the planetar can see within 120 feet. _Failure:_ 24 (7d6) Radiant damage. _Success:_ Half damage.
- name: Spellcasting
  desc: |-
    The planetar casts one of the following spells, requiring no Material components and using Charisma as spellcasting ability (spell save DC 20):
    **At Will:** _Detect Evil and Good_
    **1/Day Each:** _Commune_, _Control Weather_, _Dispel Evil and Good_, _Raise Dead_
bonus_actions:
- name: Divine Aid (2/Day)
  desc: The planetar casts _Cure Wounds_, _Invisibility_, _Lesser Restoration_, or _Remove Curse_, using the same spellcasting ability as Spellcasting.
```
