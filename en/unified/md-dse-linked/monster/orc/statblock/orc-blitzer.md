---
agility: 2
ev: 3 for four minions
file_basename: orc-blitzer
file_dpath: monster/orc/statblock
free_strike: 1
intuition: 0
item_id: orc-blitzer
item_name: Orc Blitzer
keywords:
    - Humanoid
    - Orc
level: 1
might: 1
name: Orc Blitzer
organization: Minion
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.orc.statblock/orc-blitzer
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: +2 bonus to speed
---

```ds-sb
agility: 2
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 1 damage
          tier2: 2 damage
          tier3: 3 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Lugged Spear
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: If the blitzer is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying.
      feature_type: trait
      icon: ⭐️
      name: Bloodfire Bur
      type: feature
free_strike: 1
intuition: 0
keywords:
    - Humanoid
    - Orc
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/orc-blitzer
    source: mcdm.monsters.v1
might: 1
name: Orc Blitzer
organization: Minion
presence: 0
reason: 0
role: Harrier
size: 1M
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: +2 bonus to speed
```
