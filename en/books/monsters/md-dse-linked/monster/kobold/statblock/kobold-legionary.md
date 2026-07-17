---
agility: 1
ev: "3"
file_basename: kobold-legionary
file_dpath: monster/kobold/statblock
free_strike: 1
intuition: 0
item_id: kobold-legionary
item_name: Kobold Legionary
keywords:
    - Humanoid
    - Kobold
level: 1
might: 2
name: Kobold Legionary
organization: Horde
presence: 0
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-legionary
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "20"
type: statblock
---

```ds-sb
agility: 1
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage; [taunted](../../../condition/taunted.md) (EoT)
          tier2: 4 damage; [taunted](../../../condition/taunted.md) (EoT)
          tier3: 5 damage; [taunted](../../../condition/taunted.md) (EoT)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Gladius
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage; [push](../../../movement/forced-movement.md) 1; M < 0 [prone](../../../condition/prone.md)
          tier2: 3 damage; [push](../../../movement/forced-movement.md) 1; M < 1 [prone](../../../condition/prone.md)
          tier3: 4 damage; [push](../../../movement/forced-movement.md) 1; M < 2 [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Shield Bash
      target: One creature or object
      type: feature
      usage: Maneuver
    - effects:
        - effect: While [adjacent](../../../rule/combat/adjacent.md) to an ally who also has this trait, the legionary has stability 1, has cover, and grants cover to allies.
      feature_type: trait
      icon: ⭐️
      name: Shield? Shield!
      type: feature
free_strike: 1
intuition: 0
keywords:
    - Humanoid
    - Kobold
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-legionary
    source: mcdm.monsters.v1
might: 2
name: Kobold Legionary
organization: Horde
presence: 0
reason: 0
role: Defender
size: 1S
speed: 5
stability: 0
stamina: "20"
type: statblock
```
