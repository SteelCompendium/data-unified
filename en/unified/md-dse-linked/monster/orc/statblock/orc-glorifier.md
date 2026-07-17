---
agility: 1
ev: 3 for four minions
file_basename: orc-glorifier
file_dpath: monster/orc/statblock
free_strike: 1
intuition: 0
item_id: orc-glorifier
item_name: Orc Glorifier
keywords:
    - Humanoid
    - Orc
level: 1
might: 0
name: Orc Glorifier
organization: Minion
presence: 2
reason: 0
role: Controller
scc: mcdm.monsters.v1/monster.orc.statblock/orc-glorifier
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "3"
type: statblock
with_captain: +5 bonus to ranged distance
---

```ds-sb
agility: 1
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 1 sonic damage
          tier2: 2 sonic damage; P < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 3 sonic damage; P < 2 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
      name: Call to Victory
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: If the glorifier is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying.
      feature_type: trait
      icon: ⭐️
      name: Bloodfire Burn
      type: feature
free_strike: 1
intuition: 0
keywords:
    - Humanoid
    - Orc
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/orc-glorifier
    source: mcdm.monsters.v1
might: 0
name: Orc Glorifier
organization: Minion
presence: 2
reason: 0
role: Controller
size: 1M
speed: 6
stability: 0
stamina: "3"
type: statblock
with_captain: +5 bonus to ranged distance
```
