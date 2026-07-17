---
agility: 2
ev: '-'
file_basename: orc-charger
file_dpath: monster/retainer/statblock
free_strike: 3
intuition: 0
item_id: orc-charger
item_name: Orc Charger
keywords:
    - Humanoid
    - Orc
level: 1
might: 2
name: Orc Charger
organization: Retainer
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.retainer.statblock/orc-charger
size: 1M
source: mcdm.monsters.v1
speed: 8
stability: 0
stamina: "21"
type: statblock
---

```ds-sb
agility: 2
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 3 damage
          tier2: 5 damage
          tier3: 7 damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Charge
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Notched Axe
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: If the charger is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the [free strike](../../../feature/common/main-actions/free-strike.md) is reduced to 0 [Stamina](../../../rule/health/stamina.md), the charger is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
      feature_type: trait
      icon: ⭐️
      name: Relentless
      type: feature
free_strike: 3
intuition: 0
keywords:
    - Humanoid
    - Orc
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/orc-charger
    source: mcdm.monsters.v1
might: 2
name: Orc Charger
organization: Retainer
presence: 0
reason: 0
role: Harrier
size: 1M
speed: 8
stability: 0
stamina: "21"
type: statblock
```
