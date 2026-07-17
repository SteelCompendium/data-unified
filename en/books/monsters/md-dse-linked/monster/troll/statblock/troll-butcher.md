---
agility: 1
ev: "28"
file_basename: troll-butcher
file_dpath: monster/troll/statblock
free_strike: 6
intuition: 0
item_id: troll-butcher
item_name: Troll Butcher
keywords:
    - Giant
    - Troll
level: 5
might: 3
name: Troll Butcher
organization: Elite
presence: 0
reason: 1
role: Hexer
scc: mcdm.monsters.v1/monster.troll.statblock/troll-butcher
size: "2"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "120"
type: statblock
weaknesses:
    - Acid 5
    - fire
---

```ds-sb
agility: 1
ev: "28"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage; M < 1 [bleeding](../../../condition/bleeding.md) (save ends)
          tier2: 14 damage; M < 2 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 17 damage; M < 3 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Savoring Bite
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 3 cube within 10
      effects:
        - roll: Power Roll + 3
          tier1: 5 poison damage; M < 1 [weakened](../../../condition/weakened.md) (save ends)
          tier2: 9 poison damage; M < 2 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 11 poison damage; M < 3 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
      name: Rotten Scraps
      target: Each creature in the area
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Self
      effects:
        - effect: '**Effect:** The butcher enhances their next use of Savoring Bite, changing the damage type and condition imposed to one of the following pairs: corruption damage and [dazed](../../../condition/dazed.md), acid damage and [restrained](../../../condition/restrained.md), or lightning damage and [frightened](../../../condition/frightened.md).'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Gourmet Flesh
      target: Self
      type: feature
      usage: Maneuver
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** A creature within distance deals damage to the butcher with an ability that gains an edge, has a double edge, or uses a [surge](../../../rule/resource/surge.md).
            **Effect:** The butcher makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the target. Until the end of their next turn, the butcher gains an edge on power rolls and deals an extra 3 damage with strikes.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Acquired Taste
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: Each ally within 5 squares of the butcher gains an edge on power rolls against any enemy affected by a condition.
      feature_type: trait
      icon: ⭐️
      name: Bloody Feast
      type: feature
    - effects:
        - effect: The butcher dies only if they are reduced to 0 [Stamina](../../../rule/health/stamina.md) by acid or fire damage, if they end their turn with 0 [Stamina](../../../rule/health/stamina.md), or if they take acid or fire damage while at 0 [Stamina](../../../rule/health/stamina.md).
      feature_type: trait
      icon: ⭐️
      name: Relentless Hunger
      type: feature
free_strike: 6
intuition: 0
keywords:
    - Giant
    - Troll
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.troll.statblock/troll-butcher
    source: mcdm.monsters.v1
might: 3
name: Troll Butcher
organization: Elite
presence: 0
reason: 1
role: Hexer
size: "2"
speed: 8
stability: 2
stamina: "120"
type: statblock
weaknesses:
    - Acid 5
    - fire
```
