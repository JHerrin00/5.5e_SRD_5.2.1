---
statblock: inline
source: SRD 5.2.1
cr: '21'
xp: 33000
type: Celestial
initiative_text: +20 (30)
tags:
- srd521/monster
- srd521/type/celestial
---

```statblock
layout: Basic 5e Layout
name: Solar
source: SRD 5.2.1
type_line: Large Celestial (Angel), Lawful Good
initiative_line: +20 (30)
modifier: 20
ability_mods:
- 8
- 6
- 8
- 7
- 7
- 10
ability_saves:
- 8
- 6
- 8
- 7
- 7
- 10
skills_text: Perception +14
immunities: Poison, Radiant; Charmed, Exhaustion, Frightened, Poisoned
cr_line: 21 (XP 33,000; PB +7)
xp: 33000
size: Large
type: Celestial
subtype: Angel
alignment: Lawful Good
ac: 21
hp: 297
hit_dice: 22d10 + 176
speed: 50 ft., Fly 150 ft. (hover)
stats:
- 26
- 22
- 26
- 25
- 25
- 30
skillsaves:
- perception: 14
damage_immunities: Poison, Radiant
condition_immunities: Charmed, Exhaustion, Frightened, Poisoned
senses: Truesight 120 ft.; Passive Perception 24
languages: All; telepathy 120 ft.
cr: '21'
dice: false
traits:
- name: Divine Awareness
  desc: The solar knows if it hears a lie.
- name: Exalted Restoration
  desc: If the solar dies outside Mount Celestia, its body disappears, and it gains a new body instantly, reviving with all its Hit Points somewhere in Mount Celestia.
- name: Legendary Resistance (4/Day)
  desc: If the solar fails a saving throw, it can choose to succeed instead.
- name: Magic Resistance
  desc: The solar has Advantage on saving throws against spells and other magical effects.
actions:
- name: Multiattack
  desc: The solar makes two Flying Sword attacks. It can replace one attack with a use of Slaying Bow.
- name: Flying Sword
  desc: _Melee or Ranged Attack Roll:_ +15, reach 10 ft. or range 120 ft. _Hit:_ 22 (4d6 + 8) Slashing damage plus 36 (8d8) Radiant damage. _Hit or Miss:_ The sword magically returns to the solar's hand or hovers within 5 feet of the solar immediately after a ranged attack.
- name: Slaying Bow
  desc: _Dexterity Saving Throw:_ DC 21, one creature the solar can see within 600 feet. _Failure:_ If the creature has 100 Hit Points or fewer, it dies. It otherwise takes 24 (4d8 + 6) Piercing damage plus 36 (8d8) Radiant damage.
- name: Spellcasting
  desc: |-
    The solar casts one of the following spells, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 25):
    **At Will:** _Detect Evil and Good_
    **1/Day Each:** _Commune_, _Control Weather_, _Dispel Evil and Good_, _Resurrection_
bonus_actions:
- name: Divine Aid (3/Day)
  desc: The solar casts _Cure Wounds_ (level 2 version), _Lesser Restoration_, or _Remove Curse_, using the same spellcasting ability as Spellcasting.
legendary_description: 'Legendary Action Uses: 3. Immediately after another creature''s turn, the solar can expend a use to take one of the following actions. The solar regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Blinding Gaze
  desc: _Constitution Saving Throw:_ DC 25, one creature the solar can see within 120 feet. _Failure:_ The target has the Blinded condition for 1 minute. _Failure or Success:_ The solar can't take this action again until the start of its next turn.
- name: Radiant Teleport
  desc: The solar teleports up to 60 feet to an unoccupied space it can see. _Dexterity Saving Throw:_ DC 25, each creature in a 10-foot Emanation originating from the solar at its destination space. _Failure:_ 11 (2d10) Radiant damage. _Success:_ Half damage.
```
