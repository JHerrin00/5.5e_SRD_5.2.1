---
statblock: inline
source: SRD 5.2.1
cr: '10'
xp: 5900
type: Aberration
initiative_text: +7 (17)
tags:
- srd521/monster
- srd521/type/aberration
xp_lair: 7200
---

```statblock
layout: Basic 5e Layout
name: Aboleth
source: SRD 5.2.1
type_line: Large Aberration, Lawful Evil
initiative_line: +7 (17)
modifier: 7
ability_mods:
- 5
- -1
- 2
- 4
- 2
- 4
ability_saves:
- 5
- 3
- 6
- 8
- 6
- 4
skills_text: History +12, Perception +10
cr_line: 10 (XP 5,900, or 7,200 in lair; PB +4)
xp: 5900
size: Large
type: Aberration
alignment: Lawful Evil
ac: 17
hp: 150
hit_dice: 20d10 + 40
speed: 10 ft., Swim 40 ft.
stats:
- 21
- 9
- 15
- 18
- 15
- 18
saves:
- dexterity: 3
- constitution: 6
- intelligence: 8
- wisdom: 6
skillsaves:
- history: 12
- perception: 10
senses: Darkvision 120 ft.; Passive Perception 20
languages: Deep Speech; telepathy 120 ft.
cr: '10'
dice: false
traits:
- name: Amphibious
  desc: The aboleth can breathe air and water.
- name: Eldritch Restoration
  desc: If destroyed, the aboleth gains a new body in 5d10 days, reviving with all its Hit Points in the Far Realm or another location chosen by the GM.
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the aboleth fails a saving throw, it can choose to succeed instead.
- name: Mucus Cloud
  desc: |-
    While underwater, the aboleth is surrounded by mucus. _Constitution Saving Throw:_ DC 14, each creature in a 5-foot Emanation originating from the aboleth at the end of the aboleth's turn. _Failure:_ The target is cursed. Until the curse ends, the target's skin becomes slimy, the target can breathe air and water, and it can't regain Hit Points unless it is underwater.
    While the cursed creature is outside a body of water, the creature takes 6 (1d12) Acid damage at the end of every 10 minutes unless moisture is applied to its skin before those minutes have passed.
- name: Probing Telepathy
  desc: If a creature the aboleth can see communicates telepathically with the aboleth, the aboleth learns the creature's greatest desires.
actions:
- name: Multiattack
  desc: The aboleth makes two Tentacle attacks and uses either Consume Memories or Dominate Mind if available.
- name: Tentacle
  desc: _Melee Attack Roll:_ +9, reach 15 ft. _Hit:_ 12 (2d6 + 5) Bludgeoning damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14) from one of four tentacles.
- name: Consume Memories
  desc: _Intelligence Saving Throw:_ DC 16, one creature within 30 feet that is Charmed or Grappled by the aboleth. _Failure:_ 10 (3d6) Psychic damage. _Success:_ Half damage. _Failure or Success:_ The aboleth gains the target's memories if the target is a Humanoid and is reduced to 0 Hit Points by this action.
- name: Dominate Mind (2/Day)
  desc: |-
    _Wisdom Saving Throw:_ DC 16, one creature the aboleth can see within 30 feet. _Failure:_ The target has the Charmed condition until the aboleth dies or is on a different plane of existence from the target. While Charmed, the target acts as an ally to the aboleth and is under its control while within 60 feet of it. In addition, the aboleth and the target can communicate telepathically with each other over any distance.
    The target repeats the save whenever it takes damage as well as after every 24 hours it spends at least 1 mile away from the aboleth, ending the effect on itself on a success.
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the aboleth can expend a use to take one of the following actions. The aboleth regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Lash
  desc: The aboleth makes one Tentacle attack.
- name: Psychic Drain
  desc: If the aboleth has at least one creature Charmed or Grappled, it uses Consume Memories and regains 5 (1d10) Hit Points.
```
