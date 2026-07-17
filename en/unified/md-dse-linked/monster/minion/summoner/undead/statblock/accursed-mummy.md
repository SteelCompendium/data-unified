---
agility: -1
cost: 5 essence for three minions
cost_amount: "5"
cost_resource: essence for three minions
file_basename: accursed-mummy
file_dpath: monster/minion/summoner/undead/statblock
flavor: The preserved dead, bound for eternal rest, know only violence when robbed of their future. Accursed mummies use their wrappings to bind others to the same fate.
free_strike: 3
immunities:
    - Corruption R
    - Poison R
intuition: 3
item_id: accursed-mummy
item_name: Accursed Mummy
keywords:
    - Mummy
    - Undead
might: 2
movement: —
name: Accursed Mummy
organization: Minion
presence: -1
reason: 1
role: Hexer
scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/accursed-mummy
size: 1M
source: mcdm.summoner.v1
speed: 5
stability: 2
stamina: 4 | 4 | 4
type: statblock
weaknesses:
    - Fire 1
---

```ds-sb
agility: -1
cost: 5 essence for three minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee R
      effects:
        - roll: 2d10 + R
          tier1: 3 poison [damage](../../../../../rule/damage/damage.md); pull R
          tier2: 4 poison [damage](../../../../../rule/damage/damage.md); pull R + 1
          tier3: 6 poison [damage](../../../../../rule/damage/damage.md); pull R + 2
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Fetid Bindings
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever the mummy takes [damage](../../../../../rule/damage/damage.md), each enemy [adjacent](../../../../../rule/combat/adjacent.md) to the mummy takes 2 poison [damage](../../../../../rule/damage/damage.md).
      feature_type: trait
      icon: ⭐️
      name: Mummy Dust
      type: feature
flavor: The preserved dead, bound for eternal rest, know only violence when robbed of their future. Accursed mummies use their wrappings to bind others to the same fate.
free_strike: 3
immunities:
    - Corruption R
    - Poison R
intuition: 3
keywords:
    - Mummy
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/accursed-mummy
    source: mcdm.summoner.v1
might: 2
movement: —
name: Accursed Mummy
organization: Minion
presence: -1
reason: 1
role: Hexer
size: 1M
speed: 5
stability: 2
stamina: 4 | 4 | 4
type: statblock
weaknesses:
    - Fire 1
```
