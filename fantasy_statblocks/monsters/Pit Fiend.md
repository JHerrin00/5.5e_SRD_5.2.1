---
statblock: inline
source: SRD 5.2.1
cr: '20'
xp: 25000
type: Fiend
initiative_text: +14 (24)
tags:
- srd521/monster
- srd521/type/fiend
---

```statblock
layout: Basic 5e Layout
name: Pit Fiend
source: SRD 5.2.1
type_line: Large Fiend (Devil), Lawful Evil
initiative_line: +14 (24)
modifier: 14
ability_mods:
- 8
- 2
- 7
- 6
- 4
- 7
ability_saves:
- 8
- 8
- 7
- 6
- 10
- 7
skills_text: Perception +10, Persuasion +19
resistances: Cold
immunities: Fire, Poison; Poisoned
cr_line: 20 (XP 25,000; PB +6)
xp: 25000
size: Large
type: Fiend
subtype: Devil
alignment: Lawful Evil
ac: 21
hp: 337
hit_dice: 27d10 + 189
speed: 30 ft., Fly 60 ft.
stats:
- 26
- 14
- 24
- 22
- 18
- 24
saves:
- dexterity: 8
- wisdom: 10
skillsaves:
- perception: 10
- persuasion: 19
damage_resistances: Cold
damage_immunities: Fire, Poison
condition_immunities: Poisoned
senses: Truesight 120 ft.; Passive Perception 20
languages: Infernal; telepathy 120 ft.
cr: '20'
dice: false
traits:
- name: Diabolical Restoration
  desc: If the pit fiend dies outside the Nine Hells, its body disappears in sulfurous smoke, and it gains a new body instantly, reviving with all its Hit Points somewhere in the Nine Hells.
- name: Fear Aura
  desc: The pit fiend emanates an aura in a 20-foot Emanation while it doesn't have the Incapacitated condition. _Wisdom Saving Throw:_ DC 21, any enemy that starts its turn in the aura. _Failure:_ The target has the Frightened condition until the start of its next turn. _Success:_ The target is immune to this pit fiend's aura for 24 hours.
- name: Legendary Resistance (4/Day)
  desc: If the pit fiend fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The pit fiend has Advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: The pit fiend makes one Bite attack, two Devilish Claw attacks, and one Fiery Mace attack.
- name: Bite
  desc: _Melee Attack Roll:_ +14, reach 10 ft. _Hit:_ 18 (3d6 + 8) Piercing damage. If the target is a creature, it must make the following saving throw. _Constitution Saving Throw:_ DC 21. _Failure:_ The target has the Poisoned condition. While Poisoned, the target can't regain Hit Points and takes 21 (6d6) Poison damage at the start of each of its turns, and it repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
- name: Devilish Claw
  desc: _Melee Attack Roll:_ +14, reach 10 ft. _Hit:_ 26 (4d8 + 8) Necrotic damage.
- name: Fiery Mace
  desc: _Melee Attack Roll:_ +14, reach 10 ft. _Hit:_ 22 (4d6 + 8) Force damage plus 21 (6d6) Fire damage.
- name: Hellfire Spellcasting (Recharge 4–6)
  desc: The pit fiend casts _Fireball_ (level 5 version) twice, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 21). It can replace one _Fireball_ with _Hold Monster_ (level 7 version) or _Wall of Fire._
```
