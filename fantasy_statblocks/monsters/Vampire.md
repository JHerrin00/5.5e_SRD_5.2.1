---
statblock: inline
source: SRD 5.2.1
cr: '13'
xp: 10000
type: Undead
initiative_text: +14 (24)
tags:
- srd521/monster
- srd521/type/undead
xp_lair: 11500
---

```statblock
layout: Basic 5e Layout
name: Vampire
source: SRD 5.2.1
type_line: Medium or Small Undead, Lawful Evil
initiative_line: +14 (24)
modifier: 14
ability_mods:
- 4
- 4
- 4
- 3
- 2
- 4
ability_saves:
- 4
- 9
- 9
- 3
- 7
- 9
skills_text: Perception +7, Stealth +9
resistances: Necrotic
cr_line: 13 (XP 10,000, or 11,500 in lair; PB +5)
xp: 10000
size: Medium or Small
type: Undead
alignment: Lawful Evil
ac: 16
hp: 195
hit_dice: 23d8 + 92
speed: 40 ft., Climb 40 ft.
stats:
- 18
- 18
- 18
- 17
- 15
- 18
saves:
- dexterity: 9
- constitution: 9
- wisdom: 7
- charisma: 9
skillsaves:
- perception: 7
- stealth: 9
damage_resistances: Necrotic
senses: Darkvision 120 ft.; Passive Perception 17
languages: Common plus two other languages
cr: '13'
dice: false
traits:
- name: Legendary Resistance (3/Day, or 4/Day in Lair)
  desc: If the vampire fails a saving throw, it can choose to succeed instead.
- name: Misty Escape
  desc: |-
    If the vampire drops to 0 Hit Points outside its resting place, the vampire uses Shape-Shift to become mist (no action required). If it can't use Shape-Shift, it is destroyed.
    While it has 0 Hit Points in mist form, it can't return to its vampire form, and it must reach its resting place within 2 hours or be destroyed. Once in its resting place, it returns to its vampire form and has the Paralyzed condition until it regains any Hit Points, and it regains 1 Hit Point after spending 1 hour there.
- name: Spider Climb
  desc: The vampire can climb difficult surfaces, including along ceilings, without needing to make an ability check.
- name: Vampire Weakness
  desc: |-
    The vampire has these weaknesses:
    **Forbiddance.** The vampire can't enter a residence without an invitation from an occupant.
    **Running Water.** The vampire takes 20 Acid damage if it ends its turn in running water.
    **Stake to the Heart.** If a weapon that deals Piercing damage is driven into the vampire's heart while the vampire has the Incapacitated condition in its resting place, the vampire has the Paralyzed condition until the weapon is removed.
    **Sunlight.** The vampire takes 20 Radiant damage if it starts its turn in sunlight. While in sunlight, it has Disadvantage on attack rolls and ability checks.
actions:
- name: Multiattack (Vampire Form Only)
  desc: The vampire makes two Grave Strike attacks and uses Bite.
- name: Grave Strike (Vampire Form Only)
  desc: _Melee Attack Roll:_ +9, reach 5 ft. _Hit:_ 8 (1d8 + 4) Bludgeoning damage plus 7 (2d6) Necrotic damage. If the target is a Large or smaller creature, it has the Grappled condition (escape DC 14) from one of two hands.
- name: Bite (Bat or Vampire Form Only)
  desc: |-
    _Constitution Saving Throw:_ DC 17, one creature within 5 feet that is willing or that has the Grappled, Incapacitated, or Restrained condition. _Failure:_ 6 (1d4 + 4) Piercing damage plus 13 (3d8) Necrotic damage. The target's Hit Point maximum decreases by an amount equal to the Necrotic damage taken, and the vampire regains Hit Points equal to that amount. A Humanoid reduced to 0 Hit Points by this damage and then buried rises the following sunset as a
    **Vampire Spawn** under the vampire's control.
bonus_actions:
- name: Charm (Recharge 5–6)
  desc: The vampire casts _Charm Person_, requiring no spell components and using Charisma as the spellcasting ability (spell save DC 17), and the duration is 24 hours. The Charmed target is a willing recipient of the vampire's Bite, the damage of which doesn't end the spell. When the spell ends, the target is unaware it was Charmed by the vampire.
- name: Shape-Shift
  desc: |-
    If the vampire isn't in sunlight or running water, it shape-shifts into a Tiny bat (Speed 5 ft., Fly Speed 30 ft.) or a Medium cloud of mist (Speed 5 ft., Fly Speed 20 ft. [hover]), or it returns to its vampire form. Anything it is wearing transforms with it.
    While in bat form, the vampire can't speak. Its game statistics, other than its size and Speed, are unchanged.
    While in mist form, the vampire can't take any actions, speak, or manipulate objects. It is weightless and can enter an enemy's space and stop there. If air can pass through a space, the mist can do so, but it can't pass through liquid. It has Resistance to all damage, except the damage it takes from sunlight.
legendary_description: 'Legendary Action Uses: 3 (4 in Lair). Immediately after another creature''s turn, the vampire can expend a use to take one of the following actions. The vampire regains all expended uses at the start of each of its turns.'
legendary_actions:
- name: Beguile
  desc: The vampire casts _Command_, requiring no spell components and using Charisma as the spellcasting ability (spell save DC 17). The vampire can't take this action again until the start of its next turn.
- name: Deathless Strike
  desc: The vampire moves up to half its Speed, and it makes one Grave Strike attack.
```
