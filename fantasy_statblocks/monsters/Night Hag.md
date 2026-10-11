---
statblock: inline
source: SRD 5.2.1
cr: '5'
xp: 1800
type: Fiend
initiative_text: +5 (15)
tags:
- srd521/monster
- srd521/type/fiend
---

```statblock
layout: Basic 5e Layout
name: Night Hag
source: SRD 5.2.1
type_line: Medium Fiend, Neutral Evil
initiative_line: +5 (15)
modifier: 5
ability_mods:
- 4
- 2
- 3
- 3
- 2
- 3
ability_saves:
- 4
- 2
- 3
- 3
- 2
- 3
skills_text: Deception +6, Insight +5, Perception +5, Stealth +5
resistances: Cold, Fire
immunities: Charmed
cr_line: 5 (XP 1,800; PB +3)
xp: 1800
size: Medium
type: Fiend
alignment: Neutral Evil
ac: 17
hp: 112
hit_dice: 15d8 + 45
speed: 30 ft.
stats:
- 18
- 15
- 16
- 16
- 14
- 16
skillsaves:
- deception: 6
- insight: 5
- perception: 5
- stealth: 5
damage_resistances: Cold, Fire
condition_immunities: Charmed
senses: Darkvision 120 ft.; Passive Perception 15
languages: Abyssal, Common, Infernal, Primordial
cr: '5'
dice: false
traits:
- name: Coven Magic
  desc: 'While within 30 feet of at least two hag allies, the hag can cast one of the following spells, requiring no Material components, using the spell''s normal casting time, and using Intelligence as the spellcasting ability (spell save DC 14): _Augury_, _Find Familiar_, _Identify_, _Locate Object_, _Scrying_, or _Unseen Servant_. The hag must finish a Long Rest before using this trait to cast that spell again.'
- name: Magic Resistance
  desc: The hag has Advantage on saving throws against spells and other magical effects.
- name: Soul Bag
  desc: |-
    The hag has a soul bag. While holding or carrying the bag, the hag can use its Nightmare Haunting action.
    The bag has AC 15, HP 20, and Resistance to all damage. The bag turns to dust if reduced to 0 Hit Points. If the bag is destroyed, any souls the bag is holding are released. The hag can create a new bag after 7 days.
actions:
- name: Multiattack
  desc: The hag makes two Claw attacks.
- name: Claw
  desc: _Melee Attack Roll:_ +7, reach 5 ft. _Hit:_ 13 (2d8 + 4) Slashing damage.
- name: Nightmare Haunting (1/Day; Requires Soul Bag)
  desc: |-
    While on the Ethereal Plane, the hag casts _Dream_, using the same spellcasting ability as Spellcasting. Only the hag can serve as the spell's messenger, and the target must be a creature the hag can see on the Material Plane. The spell fails and is wasted if the target is under the effect of the _Protection from Evil and Good_ spell or within a _Magic Circle_ spell.
    If the target takes damage from the _Dream_ spell, the target's Hit Point maximum decreases by an amount equal to that damage. If the spell kills the target, its soul is trapped in the hag's soul bag, and the target can't be raised from the dead until its soul is released.
- name: Spellcasting
  desc: |-
    The hag casts one of the following spells, requiring no Material components and using Intelligence as the spellcasting ability (spell save DC 14):
    **At Will:** _Detect Magic_, _Etherealness_, _Magic Missile_ (level 4 version)
    **2/Day Each:** _Phantasmal Killer_, _Plane Shift_ (self only)
bonus_actions:
- name: Shape-Shift
  desc: The hag shape-shifts into a Small or Medium Humanoid, or it returns to its true form. Other than its size, its game statistics are the same in each form. Any equipment it is wearing or carrying isn't transformed.
```
