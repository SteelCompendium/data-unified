---
agility: 2
ev: "6"
file_basename: dwarf-gunner
file_dpath: monster/dwarf/statblock
free_strike: 4
intuition: 1
item_id: dwarf-gunner
item_name: Dwarf Gunner
keywords:
    - Dwarf
    - Humanoid
level: 1
might: 0
name: Dwarf Gunner
organization: Platoon
presence: 0
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-gunner
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "26"
type: statblock
---

```ds-sb
agility: 2
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 9 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier3: 12 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
        - effect: If the target is [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to an object or a wall after the power roll is resolved, they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the end of their next turn. A target [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by a dwarf can be force moved by this ability. This forced movement doesn't end the [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) condition unless the Director determines otherwise.
          name: Effect
        - cost: 5 Malice
          effect: If the target is pushed into another creature, the target and the creature are each [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the end of their next turn.
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Portable Ballista
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Ranged 10
      effects:
        - effect: The gunner makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target, and the [prone](scc.v1:mcdm.heroes.v1/condition/prone), [restrained](scc.v1:mcdm.heroes.v1/condition/restrained), and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) conditions on the target end. The target is then [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).
          name: Effect
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Weapon
      name: Ensnaring Chains
      target: One prone, restrained, or slowed creature
      type: feature
      usage: Maneuver
    - effects:
        - effect: Whenever the gunner deals rolled damage to a target, one creature or object adjacent to the target takes 3 damage.
      feature_type: trait
      icon: ⭐️
      name: Split Shot
      type: feature
free_strike: 4
intuition: 1
keywords:
    - Dwarf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-gunner
    source: mcdm.monsters.v1
might: 0
name: Dwarf Gunner
organization: Platoon
presence: 0
reason: 0
role: Artillery
size: 1M
speed: 5
stability: 1
stamina: "26"
type: statblock
```
