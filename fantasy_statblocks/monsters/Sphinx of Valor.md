---
statblock: inline
source: SRD 5.2.1
cr: '17'
xp: 18000
type: Celestial
initiative_text: +12 (22)
tags:
- srd521/monster
- srd521/type/celestial
xp_lair: 20000
---

```statblock
layout: Basic 5e Layout
name: Sphinx of Valor
source: SRD 5.2.1
type_line: Large Celestial, Lawful Neutral
initiative_line: +12 (22)
modifier: 12
ability_mods:
- 6
- 0
- 5
- 3
- 6
- 4
ability_saves:
- 6
- 6
- 11
- 9
- 12
- 4
skills_text: Arcana +9, Perception +12, Religion +15
resistances: Necrotic, Radiant
immunities: Psychic; Charmed, Frightened
cr_line: 17 (XP 18,000, or 20,000 in lair; PB +6)
xp: 18000
size: Large
type: Celestial
alignment: Lawful Neutral
ac: 17
hp: 199
hit_dice: 19d10 + 95
speed: 40 ft., Fly 60 ft.
stats:
- 22
- 10
- 20
- 16
- 23
- 18
saves:
- dexterity: 6
- constitution: 11
- intelligence: 9
- wisdom: 12
skillsaves:
- arcana: 9
- perception: 12
- religion: 15
damage_resistances: Necrotic, Radiant
damage_immunities: Psychic
condition_immunities: Charmed, Frightened
senses: Truesight 120 ft.; Passive Perception 22
languages: Celestial, Common
cr: '17'
dice: false
traits:
- name: Inscrutable
  desc: No magic can observe the sphinx remotely or detect its thoughts without its permission. Wisdom (Insight) checks made to ascertain its intentions or sincerity are made with Disadvantage.
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the sphinx fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The sphinx makes two Claw attacks and uses Roar.
- name: Claw
  desc: _Melee Attack Roll:_ +12, reach 5 ft. _Hit:_ 20 (4d6 + 6) Slashing damage.
- name: Roar (3/Day)
  desc: |-
    The sphinx emits a magical roar. Whenever it roars, the roar has a different effect, as detailed below (the sequence resets when it takes a Long Rest):
    **First Roar.** _Wisdom Saving Throw:_ DC 20, each enemy in a 500-foot Emanation originating from the sphinx. _Failure:_ The target has the Frightened condition for 1 minute.
    **Second Roar.** _Wisdom Saving Throw:_ DC 20, each enemy in a 500-foot Emanation originating from the sphinx. _Failure:_ The target has the Paralyzed condition, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
    **Third Roar.** _Constitution Saving Throw:_ DC 20, each enemy in a 500-foot Emanation originating from the sphinx. _Failure:_ 44 (8d10) Thunder damage, and the target has the Prone condition. _Success:_ Half damage only.
- name: Spellcasting
  desc: |-
    The sphinx casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 20):
    **At Will:** _Detect Evil and Good_, _Thaumaturgy_
    **1/Day Each:** _Detect Magic_, _Dispel Magic_, _Greater Restoration_, _Heroes' Feast_, _Zone of Truth_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the sphinx can expend a use to take one of the following actions. The sphinx regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Arcane Prowl
  desc: The sphinx can teleport up to 30 feet to an unoccupied space it can see, and it makes one Claw attack.
- name: Weight of Years
  desc: _Constitution Saving Throw:_ DC 16, one creature the sphinx can see within 120 feet. _Failure:_ The target gains 1 Exhaustion level. While the target has any Exhaustion levels, it appears 3d10 years older. _Failure or Success:_ The sphinx can't take this action again until the start of its next turn.
```
