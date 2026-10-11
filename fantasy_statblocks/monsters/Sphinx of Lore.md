---
statblock: inline
source: SRD 5.2.1
cr: '11'
xp: 7200
type: Celestial
initiative_text: +10 (20)
tags:
- srd521/monster
- srd521/type/celestial
xp_lair: 8400
---

```statblock
layout: Basic 5e Layout
name: Sphinx of Lore
source: SRD 5.2.1
type_line: Large Celestial, Lawful Neutral
initiative_line: +10 (20)
modifier: 10
ability_mods:
- 4
- 2
- 3
- 4
- 4
- 4
ability_saves:
- 4
- 2
- 3
- 4
- 4
- 4
skills_text: Arcana +12, History +12, Perception +8, Religion +12
resistances: Necrotic, Radiant
immunities: Psychic; Charmed, Frightened
cr_line: 11 (XP 7,200, or 8,400 in lair; PB +4)
xp: 7200
size: Large
type: Celestial
alignment: Lawful Neutral
ac: 17
hp: 170
hit_dice: 20d10 + 60
speed: 40 ft., Fly 60 ft.
stats:
- 18
- 15
- 16
- 18
- 18
- 18
skillsaves:
- arcana: 12
- history: 12
- perception: 8
- religion: 12
damage_resistances: Necrotic, Radiant
damage_immunities: Psychic
condition_immunities: Charmed, Frightened
senses: Truesight 120 ft.; Passive Perception 18
languages: Celestial, Common
cr: '11'
dice: false
traits:
- name: Inscrutable
  desc: No magic can observe the sphinx remotely or detect its thoughts without its permission. Wisdom (Insight) checks made to ascertain its intentions or sincerity are made with Disadvantage.
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the sphinx fails a saving throw, it can choose to succeed instead.
actions:
- name: Multiattack
  desc: The sphinx makes three Claw attacks.
- name: Claw
  desc: _Melee Attack Roll:_ +8, reach 5 ft. _Hit:_ 14 (3d6 + 4) Slashing damage.
- name: Mind-Rending Roar (Recharge 5–6)
  desc: _Wisdom Saving Throw:_ DC 16, each enemy in a 300-foot Emanation originating from the sphinx. _Failure:_ 35 (10d6) Psychic damage, and the target has the Incapacitated condition until the start of the sphinx's next turn.
- name: Spellcasting
  desc: |-
    The sphinx casts one of the following spells, requiring no Material components and using Intelligence as the spellcasting ability (spell save DC 16):
    **At Will:** _Detect Magic_, _Identify_, _Mage Hand_, _Minor Illusion_, _Prestidigitation_
    **1/Day Each:** _Dispel Magic_, _Legend Lore_, _Locate Object_, _Plane Shift_, _Remove Curse_, _Tongues_
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the sphinx can expend a use to take one of the following actions. The sphinx regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Arcane Prowl
  desc: The sphinx can teleport up to 30 feet to an unoccupied space it can see, and it makes one Claw attack.
- name: Weight of Years
  desc: _Constitution Saving Throw:_ DC 16, one creature the sphinx can see within 120 feet. _Failure:_ The target gains 1 Exhaustion level. While the target has any Exhaustion levels, it appears 3d10 years older. _Failure or Success:_ The sphinx can't take this action again until the start of its next turn.
```
