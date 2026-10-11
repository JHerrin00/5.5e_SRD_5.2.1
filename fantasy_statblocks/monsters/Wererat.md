---
statblock: inline
source: SRD 5.2.1
cr: '2'
xp: 450
type: Monstrosity
initiative_text: +3 (13)
tags:
- srd521/monster
- srd521/type/monstrosity
---

```statblock
layout: Basic 5e Layout
name: Wererat
source: SRD 5.2.1
type_line: Medium or Small Monstrosity (Lycanthrope), Lawful Evil
initiative_line: +3 (13)
modifier: 3
ability_mods:
- 0
- 3
- 1
- 0
- 0
- -1
ability_saves:
- 0
- 3
- 1
- 0
- 0
- -1
skills_text: Perception +4, Stealth +5
cr_line: 2 (XP 450; PB +2)
xp: 450
size: Medium or Small
type: Monstrosity
subtype: Lycanthrope
alignment: Lawful Evil
ac: 13
hp: 60
hit_dice: 11d8 + 11
speed: 30 ft., Climb 30 ft.
stats:
- 10
- 16
- 12
- 11
- 10
- 8
skillsaves:
- perception: 4
- stealth: 5
gear: Hand Crossbow
senses: Darkvision 60 ft.; Passive Perception 14
languages: Common (can't speak in rat form)
cr: '2'
dice: false
actions:
- name: Multiattack
  desc: The wererat makes two attacks, using Scratch or Hand Crossbow in any combination. It can replace one attack with a Bite attack.
- name: Bite (Rat or Hybrid Form Only)
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 8 (2d4 + 3) Piercing damage. If the target is a Humanoid, it is subjected to the following effect. _Constitution Saving Throw:_ DC 11. _Failure:_ The target is cursed. If the cursed target drops to 0 Hit Points, it instead becomes a **Wererat** under the GM's control and has 10 Hit Points. _Success:_ The target is immune to this wererat's curse for 24 hours.
- name: Scratch
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 6 (1d6 + 3) Slashing damage.
- name: Hand Crossbow (Humanoid or Hybrid Form Only)
  desc: _Ranged Attack Roll:_ +5, range 30/120 ft. _Hit:_ 6 (1d6 + 3) Piercing damage.
bonus_actions:
- name: Shape-Shift
  desc: The wererat shape-shifts into a Medium rat-humanoid hybrid or a Small rat, or it returns to its true humanoid form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.
```
