---
agility: 3
ev: "24"
file_basename: wyvern-lurker
file_dpath: monster/wyvern/statblock
free_strike: 6
immunities:
    - Acid 5
intuition: 1
item_id: wyvern-lurker
item_name: Wyvern Lurker
keywords:
    - Beast
    - Wyvern
level: 4
might: 2
movement: Fly
name: Wyvern Lurker
organization: Elite
presence: 0
reason: -1
role: Ambusher
scc: mcdm.monsters.v1/monster.wyvern.statblock/wyvern-lurker
size: "2"
source: mcdm.monsters.v1
speed: 9
stability: 2
stamina: "120"
type: statblock
---

```ds-sb
agility: 3
ev: "24"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage
          tier2: 14 damage; M < 2 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 17 damage; M < 3 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Strike
        - Weapon
      name: Agonizing Stinger
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 10 acid damage; M < 1 [weakened](../../../condition/weakened.md) (save ends)
          tier2: 16 acid damage; M < 2 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 20 acid damage; M < 3 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Strike
        - Weapon
      name: Acidic Anguish
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The lurker [flies](../../../movement/fly.md) up to their speed, then can attempt to hide. Each enemy the lurker moves [adjacent](../../../rule/combat/adjacent.md) to during this movement can choose to take 3 sonic damage or fall [prone](../../../condition/prone.md).'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Swooping Torment
      target: Self
      type: feature
      usage: Maneuver
    - distance: Ranged 5
      effects:
        - effect: |-
            **Trigger:** A creature within distance deals damage to the lurker with a ranged ability.
            **Effect:** The lurker [flies](../../../movement/fly.md) [adjacent](../../../rule/combat/adjacent.md) to the target and can make a [free strike](../../../feature/common/main-actions/free-strike.md) against them.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Retaliatory Dive
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: While within 10 squares of another wyvern, the lurker deals an extra 3 damage with strikes.
      feature_type: trait
      icon: ⭐️
      name: Ruthless Rage
      type: feature
    - effects:
        - effect: Any creature affected by a condition imposed by a wyvern can't be hidden from the lurker.
      feature_type: trait
      icon: ⭐️
      name: Tenacious Hunter
      type: feature
free_strike: 6
immunities:
    - Acid 5
intuition: 1
keywords:
    - Beast
    - Wyvern
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.wyvern.statblock/wyvern-lurker
    source: mcdm.monsters.v1
might: 2
movement: Fly
name: Wyvern Lurker
organization: Elite
presence: 0
reason: -1
role: Ambusher
size: "2"
speed: 9
stability: 2
stamina: "120"
type: statblock
```
