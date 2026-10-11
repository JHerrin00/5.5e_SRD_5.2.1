---
statblock: inline
source: SRD 5.2.1
cr: '4'
xp: 1100
type: Ooze
initiative_text: -3 (7)
tags:
- srd521/monster
- srd521/type/ooze
---

```statblock
layout: Basic 5e Layout
name: Black Pudding
source: SRD 5.2.1
type_line: Large Ooze, Unaligned
initiative_line: -3 (7)
modifier: -3
ability_mods:
- 3
- -3
- 3
- -5
- -2
- -5
ability_saves:
- 3
- -3
- 3
- -5
- -2
- -5
immunities: Acid, Cold, Lightning, Slashing; Charmed, Deafened, Exhaustion, Frightened, Grappled, Prone, Restrained
cr_line: 4 (XP 1,100; PB +2)
xp: 1100
size: Large
type: Ooze
alignment: Unaligned
ac: 7
hp: 68
hit_dice: 8d10 + 24
speed: 20 ft., Climb 20 ft.
stats:
- 16
- 5
- 16
- 1
- 6
- 1
damage_immunities: Acid, Cold, Lightning, Slashing
condition_immunities: Charmed, Deafened, Exhaustion, Frightened, Grappled, Prone, Restrained
senses: Blindsight 60 ft.; Passive Perception 8
languages: None
cr: '4'
dice: false
traits:
- name: Amorphous
  desc: The pudding can move through a space as narrow as 1 inch without expending extra movement to do so.
- name: Corrosive Form
  desc: |-
    A creature that hits the pudding with a melee attack roll takes 4 (1d8) Acid damage. Nonmagical ammunition is destroyed immediately after hitting the pudding and dealing any damage. Any nonmagical weapon takes a cumulative -1 penalty to attack rolls immediately after dealing damage to the pudding and coming into contact with it. The weapon is destroyed if the penalty reaches -5. The penalty can be removed by casting the _Mending_ spell on the weapon.
    In 1 minute, the pudding can eat through 2 feet of nonmagical wood or metal.
- name: Spider Climb
  desc: The pudding can climb difficult surfaces, including along ceilings, without needing to make an ability check.
actions:
- name: Dissolving Pseudopod
  desc: _Melee Attack Roll:_ +5, reach 10 ft. _Hit:_ 17 (4d6 + 3) Acid damage. Nonmagical armor worn by the target takes a -1 penalty to the AC it offers. The armor is destroyed if the penalty reduces its AC to 10. The penalty can be removed by casting the _Mending_ spell on the armor.
reactions:
- name: Split
  desc: _Trigger:_ While the pudding is Large or Medium and has 10+ Hit Points, it becomes Bloodied or is subjected to Lightning or Slashing damage. _Response:_ The pudding splits into two new **Black Puddings**. Each new pudding is one size smaller than the original pudding and acts on its Initiative. The original pudding's Hit Points are divided evenly between the new puddings (round down).
```
