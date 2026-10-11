---
statblock: inline
source: SRD 5.2.1
cr: '21'
xp: 33000
type: Undead
initiative_text: +17 (27)
tags:
- srd521/monster
- srd521/type/undead
xp_lair: 41000
---

```statblock
layout: Basic 5e Layout
name: Lich
source: SRD 5.2.1
type_line: Medium Undead (Wizard), Neutral Evil
initiative_line: +17 (27)
modifier: 17
ability_mods:
- 0
- 3
- 3
- 5
- 2
- 3
ability_saves:
- 0
- 10
- 10
- 12
- 9
- 3
skills_text: Arcana +19, History +12, Insight +9, Perception +9
resistances: Cold, Lightning
immunities: Necrotic, Poison; Charmed, Exhaustion, Frightened, Paralyzed, Poisoned
cr_line: 21 (XP 33,000, or 41,000 in lair; PB +7)
xp: 33000
size: Medium
type: Undead
subtype: Wizard
alignment: Neutral Evil
ac: 20
hp: 315
hit_dice: 42d8 + 126
speed: 30 ft.
stats:
- 11
- 16
- 16
- 21
- 14
- 16
saves:
- dexterity: 10
- constitution: 10
- intelligence: 12
- wisdom: 9
skillsaves:
- arcana: 19
- history: 12
- insight: 9
- perception: 9
damage_resistances: Cold, Lightning
damage_immunities: Necrotic, Poison
condition_immunities: Charmed, Exhaustion, Frightened, Paralyzed, Poisoned
gear: Component Pouch
senses: Truesight 120 ft.; Passive Perception 19
languages: All
cr: '21'
dice: false
traits:
- name: Legendary Resistance (4/Day, or 5/Day in Lair)
  desc: If the lich fails a saving throw, it can choose to succeed instead.
- name: Spirit Jar
  desc: If destroyed, the lich reforms in 1d10 days if it has a spirit jar, reviving with all its Hit Points. The new body appears in an unoccupied space within the lich's lair.
actions:
- name: Multiattack
  desc: The lich makes three attacks, using Eldritch Burst or Paralyzing Touch in any combination.
- name: Eldritch Burst
  desc: _Melee or Ranged Attack Roll:_ +12, reach 5 ft. or range 120 ft. _Hit:_ 31 (4d12 + 5) Force damage.
- name: Paralyzing Touch
  desc: _Melee Attack Roll:_ +12, reach 5 ft. _Hit:_ 15 (3d6 + 5) Cold damage, and the target has the Paralyzed condition until the start of the lich's next turn.
- name: Spellcasting
  desc: |-
    The lich casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 20):
    **At Will:** _Detect Magic_, _Detect Thoughts_, _Dispel Magic_, _Fireball_ (level 5 version), _Invisibility_, _Lightning Bolt_ (level 5 version), _Mage Hand_, _Prestidigitation_
    **2/Day Each:** _Animate Dead_, _Dimension Door_, _Plane Shift_
    **1/Day Each:** _Chain Lightning_, _Finger of Death_, _Power Word Kill_, _Scrying_
reactions:
- name: Protective Magic
  desc: The lich casts _Counterspell_ or _Shield_ in response to the spell's trigger, using the same spellcasting ability as Spellcasting.
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the lich can expend a use to take one of the following actions. The lich regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Deathly Teleport
  desc: The lich teleports up to 60 feet to an unoccupied space it can see, and each creature within 10 feet of the space it left takes 11 (2d10) Necrotic damage.
- name: Disrupt Life
  desc: _Constitution Saving Throw:_ DC 20, each creature that isn't an Undead in a 20-foot Emanation originating from the lich. _Failure:_ 31 (9d6) Necrotic damage. _Success:_ Half damage. _Failure or Success:_ The lich can't take this action again until the start of its next turn.
- name: Frightening Gaze
  desc: The lich casts _Fear_, using the same spellcasting ability as Spellcasting. The lich can't take this action again until the start of its next turn.
```
