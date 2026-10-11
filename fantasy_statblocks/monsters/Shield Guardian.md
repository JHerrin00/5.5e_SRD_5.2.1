---
statblock: inline
source: SRD 5.2.1
cr: '7'
xp: 2900
type: Construct
initiative_text: -1 (9)
tags:
- srd521/monster
- srd521/type/construct
---

```statblock
layout: Basic 5e Layout
name: Shield Guardian
source: SRD 5.2.1
type_line: Large Construct, Unaligned
initiative_line: -1 (9)
modifier: -1
ability_mods:
- 4
- -1
- 4
- -2
- 0
- -4
ability_saves:
- 4
- -1
- 4
- -2
- 0
- -4
immunities: Poison; Charmed, Exhaustion, Frightened, Paralyzed, Petrified, Poisoned
cr_line: 7 (XP 2,900; PB +3)
xp: 2900
size: Large
type: Construct
alignment: Unaligned
ac: 17
hp: 142
hit_dice: 15d10 + 60
speed: 30 ft.
stats:
- 18
- 8
- 18
- 7
- 10
- 3
damage_immunities: Poison
condition_immunities: Charmed, Exhaustion, Frightened, Paralyzed, Petrified, Poisoned
senses: Blindsight 10 ft., Darkvision 60 ft.; Passive Perception 10
languages: Understands commands given in any language but can't speak
cr: '7'
dice: false
traits:
- name: Bound
  desc: The guardian is magically bound to an amulet. While the guardian and its amulet are on the same plane of existence, the amulet's wearer can telepathically call the guardian to travel to it, and the guardian knows the distance and direction to the amulet. If the guardian is within 60 feet of the amulet's wearer, half of any damage the wearer takes (round up) is transferred to the guardian.
- name: Regeneration
  desc: The guardian regains 10 Hit Points at the start of each of its turns if it has at least 1 Hit Point.
- name: Spell Storing
  desc: A spellcaster who wears the guardian's amulet can cause the guardian to store one spell of level 4 or lower. To do so, the wearer must cast the spell on the guardian while within 5 feet of it. The spell has no effect but is stored within the guardian. Any previously stored spell is lost when a new spell is stored. The guardian can cast the spell stored with any parameters set by the original caster, requiring no spell components and using the caster's spellcasting ability. The stored spell is then lost.
actions:
- name: Multiattack
  desc: The guardian makes two Fist attacks.
- name: Fist
  desc: _Melee Attack Roll:_ +7, reach 10 ft. _Hit:_ 11 (2d6 + 4) Bludgeoning damage plus 7 (2d6) Force damage.
reactions:
- name: Protection
  desc: _Trigger:_ An attack roll hits the wearer of the guardian's amulet while the wearer is within 5 feet of the guardian. _Response:_ The wearer gains a +5 bonus to AC, including against the triggering attack and possibly causing it to miss, until the start of the guardian's next turn.
```
