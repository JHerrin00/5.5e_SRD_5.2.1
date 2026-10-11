---
statblock: inline
source: SRD 5.2.1
cr: '4'
xp: 1100
type: Monstrosity
initiative_text: +2 (12)
tags:
- srd521/monster
- srd521/type/monstrosity
---

```statblock
layout: Basic 5e Layout
name: Weretiger
source: SRD 5.2.1
type_line: Medium or Small Monstrosity (Lycanthrope), Neutral
initiative_line: +2 (12)
modifier: 2
ability_mods:
- 3
- 2
- 3
- 0
- 1
- 0
ability_saves:
- 3
- 2
- 3
- 0
- 1
- 0
skills_text: Perception +5, Stealth +4
cr_line: 4 (XP 1,100; PB +2)
xp: 1100
size: Medium or Small
type: Monstrosity
subtype: Lycanthrope
alignment: Neutral
ac: 12
hp: 120
hit_dice: 16d8 + 48
speed: 30 ft., 40 ft. (tiger form only)
stats:
- 17
- 15
- 16
- 10
- 13
- 11
skillsaves:
- perception: 5
- stealth: 4
gear: Longbow
senses: Darkvision 60 ft.; Passive Perception 15
languages: Common (can't speak in tiger form)
cr: '4'
dice: false
actions:
- name: Multiattack
  desc: The weretiger makes two attacks, using Scratch or Longbow in any combination. It can replace one attack with a Bite attack.
- name: Bite (Tiger or Hybrid Form Only)
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 12 (2d8 + 3) Piercing damage. If the target is a Humanoid, it is subjected to the following effect. _Constitution Saving Throw:_ DC 13. _Failure:_ The target is cursed. If the cursed target drops to 0 Hit Points, it instead becomes a **Weretiger** under the GM's control and has 10 Hit Points. _Success:_ The target is immune to this weretiger's curse for 24 hours.
- name: Scratch
  desc: _Melee Attack Roll:_ +5, reach 5 ft. _Hit:_ 10 (2d6 + 3) Slashing damage.
- name: Longbow (Humanoid or Hybrid Form Only)
  desc: _Ranged Attack Roll:_ +4, range 150/600 ft. _Hit:_ 11 (2d8 + 2) Piercing damage.
bonus_actions:
- name: Prowl (Tiger or Hybrid Form Only)
  desc: The weretiger moves up to its Speed without provoking Opportunity Attacks. At the end of this movement, the weretiger can take the Hide action.
- name: Shape-Shift
  desc: The weretiger shape-shifts into a Large tiger-humanoid hybrid or a Large tiger, or it returns to its true humanoid form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.
```
