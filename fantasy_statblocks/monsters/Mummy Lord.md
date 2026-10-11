---
statblock: inline
source: SRD 5.2.1
cr: '15'
xp: 13000
type: Undead
initiative_text: +10 (20)
tags:
- srd521/monster
- srd521/type/undead
xp_lair: 15000
---

```statblock
layout: Basic 5e Layout
name: Mummy Lord
source: SRD 5.2.1
type_line: Medium or Small Undead (Cleric), Lawful Evil
initiative_line: +10 (20)
modifier: 10
ability_mods:
- 4
- 0
- 3
- 0
- 4
- 3
ability_saves:
- 4
- 0
- 3
- 5
- 9
- 3
skills_text: History +5, Perception +9, Religion +5
vulnerabilities: Fire
immunities: Necrotic, Poison; Charmed, Exhaustion, Frightened, Paralyzed, Poisoned
cr_line: 15 (XP 13,000, or 15,000 in lair; PB +5)
xp: 13000
size: Medium or Small
type: Undead
subtype: Cleric
alignment: Lawful Evil
ac: 17
hp: 187
hit_dice: 25d8 + 75
speed: 30 ft.
stats:
- 18
- 10
- 17
- 11
- 19
- 16
saves:
- intelligence: 5
- wisdom: 9
skillsaves:
- history: 5
- perception: 9
- religion: 5
damage_vulnerabilities: Fire
damage_immunities: Necrotic, Poison
condition_immunities: Charmed, Exhaustion, Frightened, Paralyzed, Poisoned
senses: Truesight 60 ft.; Passive Perception 19
languages: Common plus three other languages
cr: '15'
dice: false
traits:
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the mummy fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The mummy has Advantage on saving throws against spells and other magical effects.
- name: Undead Restoration
  desc: If destroyed, the mummy gains a new body in 24 hours if its heart is intact, reviving with all its Hit Points. The new body appears in an unoccupied space within the mummy's lair. The heart is a Tiny object that has AC 17, HP 10, and Immunity to all damage except Fire.
actions:
- name: Multiattack
  desc: The mummy makes one Rotting Fist or Channel Negative Energy attack, and it uses Dreadful Glare.
- name: Rotting Fist
  desc: _Melee Attack Roll:_ +9, reach 5 ft. _Hit:_ 15 (2d10 + 4) Bludgeoning damage plus 10 (3d6) Necrotic damage. If the target is a creature, it is cursed. While cursed, the target can't regain Hit Points, it gains no benefit from finishing a Long Rest, and its Hit Point maximum decreases by 10 (3d6) every 24 hours that elapse. A creature dies and turns to dust if reduced to 0 Hit Points by this attack.
- name: Channel Negative Energy
  desc: _Ranged Attack Roll:_ +9, range 60 ft. _Hit:_ 25 (6d6 + 4) Necrotic damage.
- name: Dreadful Glare
  desc: _Wisdom Saving Throw:_ DC 17, one creature the mummy can see within 60 feet. _Failure:_ 25 (6d6 + 4) Psychic damage, and the target has the Paralyzed condition until the end of the mummy's next turn.
- name: Spellcasting
  desc: |-
    The mummy casts one of the following spells, requiring no Material components and using Wisdom as the spellcasting ability (spell save DC 17, +9 to hit with spell attacks):
    **At Will:** _Dispel Magic_, _Thaumaturgy_
    **1/Day Each:** _Animate Dead_, _Harm_, _Insect Plague_ (level 7 version)
reactions:
- name: Whirlwind of Sand
  desc: _Trigger:_ The mummy is hit by an attack roll. _Response:_ The mummy adds 2 to its AC against the attack, possibly causing the attack to miss, and the mummy teleports up to 60 feet to an unoccupied space it can see. Each creature of its choice that it can see within 5 feet of its destination space has the Blinded condition until the end of the mummy's next turn.
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the mummy can expend a use to take one of the following actions. The mummy regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Dread Command
  desc: The mummy casts _Command_ (level 2 version), using the same spellcasting ability as Spellcasting. The mummy can't take this action again until the start of its next turn.
- name: Glare
  desc: The mummy uses Dreadful Glare. The mummy can't take this action again until the start of its next turn.
- name: Necrotic Strike
  desc: The mummy makes one Rotting Fist or Channel Negative Energy attack.
```
