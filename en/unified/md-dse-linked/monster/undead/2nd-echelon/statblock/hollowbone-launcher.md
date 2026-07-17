---
agility: 3
ev: 6 for four minions
file_basename: hollowbone-launcher
file_dpath: monster/undead/2nd-echelon/statblock
free_strike: 3
immunities:
    - Corruption 4
    - poison 4
intuition: 0
item_id: hollowbone-launcher
item_name: Hollowbone Launcher
keywords:
    - Undead
    - Soulless
level: 4
might: -2
name: Hollowbone Launcher
organization: Minion
presence: 0
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/hollowbone-launcher
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "7"
type: statblock
with_captain: +5 bonus to ranged distance
---

```ds-sb
agility: 3
ev: 6 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage
          tier2: 5 damage
          tier3: 7 damage; M < 3 [bleeding](../../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Hollowbone Slug
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The hollowbone launcher explodes when they are reduced to 0 [Stamina](../../../../rule/health/stamina.md), dealing 2 damage to each [adjacent](../../../../rule/combat/adjacent.md) creature.
      feature_type: trait
      icon: ⭐️
      name: Brittle Revenge
      type: feature
free_strike: 3
immunities:
    - Corruption 4
    - poison 4
intuition: 0
keywords:
    - Undead
    - Soulless
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.undead.2nd-echelon.statblock/hollowbone-launcher
    source: mcdm.monsters.v1
might: -2
name: Hollowbone Launcher
organization: Minion
presence: 0
reason: 0
role: Artillery
size: 1M
speed: 5
stability: 0
stamina: "7"
type: statblock
with_captain: +5 bonus to ranged distance
```
