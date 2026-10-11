---
statblock: inline
source: SRD 5.2.1
cr: '8'
xp: 3900
type: Humanoid
initiative_text: +10 (20)
tags:
- srd521/monster
- srd521/type/humanoid
---

```statblock
layout: Basic 5e Layout
name: Assassin
source: SRD 5.2.1
type_line: Medium or Small Humanoid, Neutral
initiative_line: +10 (20)
modifier: 10
ability_mods:
- 0
- 4
- 2
- 3
- 0
- 0
ability_saves:
- 0
- 7
- 2
- 6
- 0
- 0
skills_text: Acrobatics +7, Perception +6, Stealth +10
resistances: Poison
cr_line: 8 (XP 3,900; PB +3)
xp: 3900
size: Medium or Small
type: Humanoid
alignment: Neutral
ac: 16
hp: 97
hit_dice: 15d8 + 30
speed: 30 ft.
stats:
- 11
- 18
- 14
- 16
- 11
- 10
saves:
- dexterity: 7
- intelligence: 6
skillsaves:
- acrobatics: 7
- perception: 6
- stealth: 10
damage_resistances: Poison
gear: Light Crossbow, Shortsword, Studded Leather Armor
senses: Passive Perception 16
languages: Common, Thieves' Cant
cr: '8'
dice: false
traits:
- name: Evasion
  desc: If the assassin is subjected to an effect that allows it to make a Dexterity saving throw to take only half damage, the assassin instead takes no damage if it succeeds on the save and only half damage if it fails. It can't use this trait if it has the Incapacitated condition.
actions:
- name: Multiattack
  desc: The assassin makes three attacks, using Shortsword or Light Crossbow in any combination.
- name: Shortsword
  desc: _Melee Attack Roll:_ +7, reach 5 ft. _Hit:_ 7 (1d6 + 4) Piercing damage plus 17 (5d6) Poison damage, and the target has the Poisoned condition until the start of the assassin's next turn.
- name: Light Crossbow
  desc: _Ranged Attack Roll:_ +7, range 80/320 ft. _Hit:_ 8 (1d8 + 4) Piercing damage plus 21 (6d6) Poison damage.
bonus_actions:
- name: Cunning Action
  desc: The assassin takes the Dash, Disengage, or Hide action.
```
