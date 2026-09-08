---
agility: -1
ev: "40"
file_basename: frost-giant-storm-hurler
file_dpath: monster/giant/statblock
free_strike: 9
immunities:
    - Cold 8
intuition: 0
item_id: frost-giant-storm-hurler
item_name: Frost Giant Storm Hurler
keywords:
    - Frost Giant
    - Giant
level: 8
might: 4
name: Frost Giant Storm Hurler
organization: Elite
presence: 0
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.giant.statblock/frost-giant-storm-hurler
size: "4"
source: mcdm.monsters.v1
speed: 7
stability: 5
stamina: "180"
type: statblock
---

```ds-sb
agility: -1
ev: "40"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 4
          tier1: 13 cold damage
          tier2: 18 cold damage; M < 3 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 22 cold damage; M < 4 [bleeding](../../../condition/bleeding.md) (save ends)
        - effect: Whenever a creature [bleeding](../../../condition/bleeding.md) this way takes damage from that condition, their speed decreases by 1 (to a minimum of 0) until that condition ends.
          name: Effect
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Ice Javelins
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 15
      effects:
        - effect: The storm hurler throws three size 1L ice javelins into unoccupied squares within distance. Each javelin has 30 [Stamina](../../../rule/health/stamina.md) and fire weakness 5. At the start of the storm hurler's next turn, all javelins not destroyed explode in a shower of icicles. Each enemy and object within 3 squares of an exploding javelin makes an **Agility test**.
          name: Effect
          tier1: 14 cold damage; [push](../../../movement/forced-movement.md) 4; [bleeding](../../../condition/bleeding.md) (save ends)
          tier2: 11 cold damage; [push](../../../movement/forced-movement.md) 2; [slowed](../../../condition/slowed.md) (save ends)
          tier3: 7 cold damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Flower of Frost
      target: Special
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - effect: The storm hurler and the target each [shift](../../../movement/shifting.md) up to 6 squares while staying [adjacent](../../../rule/combat/adjacent.md) to each other. The target can then jump up to 5 squares and make a [free strike](../../../feature/common/main-actions/free-strike.md).
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
      name: Ice Dance
      target: One giant ally
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: The triggering strike has a double bane. If the strike obtains a tier 1 outcome, the storm hurler uses Ice Javelins against the creature who made it.
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Frozen Retribution
      target: Self
      trigger: The storm hurler is targeted by a ranged strike.
      type: feature
      usage: Triggered action
    - effects:
        - effect: The storm hurler is surrounded by a snowstorm. Any enemy who starts their turn within 2 squares of the storm hurler can't [shift](../../../movement/shifting.md).
      feature_type: trait
      icon: ⭐️
      name: Kingdom of Isolation
      type: feature
free_strike: 9
immunities:
    - Cold 8
intuition: 0
keywords:
    - Frost Giant
    - Giant
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.giant.statblock/frost-giant-storm-hurler
    source: mcdm.monsters.v1
might: 4
name: Frost Giant Storm Hurler
organization: Elite
presence: 0
reason: 0
role: Artillery
size: "4"
speed: 7
stability: 5
stamina: "180"
type: statblock
```
