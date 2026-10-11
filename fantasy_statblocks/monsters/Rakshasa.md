---
statblock: inline
source: SRD 5.2.1
cr: '13'
xp: 10000
type: Fiend
initiative_text: +8 (18)
tags:
- srd521/monster
- srd521/type/fiend
---

```statblock
layout: Basic 5e Layout
name: Rakshasa
source: SRD 5.2.1
type_line: Medium Fiend, Lawful Evil
initiative_line: +8 (18)
modifier: 8
ability_mods:
- 2
- 3
- 4
- 1
- 3
- 5
ability_saves:
- 2
- 3
- 4
- 1
- 3
- 5
skills_text: Deception +10, Insight +8, Perception +8
vulnerabilities: Piercing damage from weapons wielded by creatures under the effect of a _Bless_ spell
immunities: Charmed, Frightened
cr_line: 13 (XP 10,000; PB +5)
xp: 10000
size: Medium
type: Fiend
alignment: Lawful Evil
ac: 17
hp: 221
hit_dice: 26d8 + 104
speed: 40 ft.
stats:
- 14
- 17
- 18
- 13
- 16
- 20
skillsaves:
- deception: 10
- insight: 8
- perception: 8
damage_vulnerabilities: Piercing damage from weapons wielded by creatures under the effect of a _Bless_ spell
condition_immunities: Charmed, Frightened
senses: Truesight 60 ft.; Passive Perception 18
languages: Common, Infernal
cr: '13'
dice: false
traits:
- name: Greater Magic Resistance
  desc: The rakshasa automatically succeeds on saving throws against spells and other magical effects, and the attack rolls of spells automatically miss it. Without the rakshasa's permission, no spell can observe the rakshasa remotely or detect its thoughts, creature type, or alignment.
- name: Fiendish Restoration
  desc: If the rakshasa dies outside the Nine Hells, its body turns to ichor, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.
actions:
- name: Multiattack
  desc: The rakshasa makes three Cursed Touch attacks.
- name: Cursed Touch
  desc: _Melee Attack Roll:_ +10, reach 5 ft. _Hit:_ 12 (2d6 + 5) Slashing damage plus 19 (3d12) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target gains no benefit from finishing a Short or Long Rest.
- name: Baleful Command (Recharge 5–6)
  desc: _Wisdom Saving Throw:_ DC 18, each enemy in a 30-foot Emanation originating from the rakshasa. _Failure:_ 28 (8d6) Psychic damage, and the target has the Frightened and Incapacitated conditions until the start of the rakshasa's next turn.
- name: Spellcasting
  desc: |-
    The rakshasa casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 18):
    **At Will:** _Detect Magic_, _Detect Thoughts_, _Disguise Self_, _Mage Hand_, _Minor Illusion_
    **1/Day Each:** _Fly_, _Invisibility_, _Major Image_, _Plane Shift_
```
