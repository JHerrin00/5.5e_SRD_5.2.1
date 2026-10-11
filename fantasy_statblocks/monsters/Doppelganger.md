---
statblock: inline
source: SRD 5.2.1
cr: '3'
xp: 700
type: Monstrosity
initiative_text: +4 (14)
tags:
- srd521/monster
- srd521/type/monstrosity
---

```statblock
layout: Basic 5e Layout
name: Doppelganger
source: SRD 5.2.1
type_line: Medium Monstrosity, Neutral
initiative_line: +4 (14)
modifier: 4
ability_mods:
- 0
- 4
- 2
- 0
- 1
- 2
ability_saves:
- 0
- 4
- 2
- 0
- 1
- 2
skills_text: Deception +6, Insight +3
immunities: Charmed
cr_line: 3 (XP 700; PB +2)
xp: 700
size: Medium
type: Monstrosity
alignment: Neutral
ac: 14
hp: 52
hit_dice: 8d8 + 16
speed: 30 ft.
stats:
- 11
- 18
- 14
- 11
- 12
- 14
skillsaves:
- deception: 6
- insight: 3
condition_immunities: Charmed
senses: Darkvision 60 ft.; Passive Perception 11
languages: Common plus three other languages
cr: '3'
dice: false
actions:
- name: Multiattack
  desc: The doppelganger makes two Slam attacks and uses Unsettling Visage if available.
- name: Slam
  desc: _Melee Attack Roll:_ +6 (with Advantage during the first round of each combat), reach 5 ft. _Hit:_ 11 (2d6 + 4) Bludgeoning damage.
- name: Read Thoughts
  desc: The doppelganger casts _Detect Thoughts_, requiring no spell components and using Charisma as the spellcasting ability (spell save DC 12).
- name: Unsettling Visage (Recharge 6)
  desc: _Wisdom Saving Throw:_ DC 12, each creature in a 15-foot Emanation originating from the doppelganger that can see the doppelganger. _Failure:_ The target has the Frightened condition and repeats the save at the end of each of its turns, ending the effect on itself on a success. After 1 minute, it succeeds automatically.
bonus_actions:
- name: Shape-Shift
  desc: The doppelganger shape-shifts into a Medium or Small Humanoid, or it returns to its true form. Its game statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed.
```
