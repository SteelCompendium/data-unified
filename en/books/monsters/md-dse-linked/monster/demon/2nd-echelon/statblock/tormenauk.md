---
agility: 0
ev: "8"
file_basename: tormenauk
file_dpath: monster/demon/2nd-echelon/statblock
free_strike: 4
intuition: 1
item_id: tormenauk
item_name: Tormenauk
keywords:
    - Abyssal
    - Demon
level: 6
might: 3
name: Tormenauk
organization: Horde
presence: 2
reason: 2
role: Brute
scc: mcdm.monsters.v1/monster.demon.2nd-echelon.statblock/tormenauk
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "45"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 0
ev: "8"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 7 damage
          tier2: 9 damage
          tier3: 11 damage; [grabbed](../../../../condition/grabbed.md), and the target takes a [bane](../../../../rule/dice/bane.md) on the [Escape Grab](../../../../feature/common/maneuvers/escape-grab.md) maneuver
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Many Maws
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 3
          tier1: 4 psychic damage; I < 1 [dazed](../../../../condition/dazed.md) (save ends)
          tier2: 6 psychic damage; I < 2 [dazed](../../../../condition/dazed.md) (save ends)
          tier3: 8 psychic damage; I < 3 [dazed](../../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Agony Wail
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: While the tormenauk is [winded](../../../../rule/health/winded.md), they gain an [edge](../../../../rule/dice/edge.md) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the tormenauk can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 4
intuition: 1
keywords:
    - Abyssal
    - Demon
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.demon.2nd-echelon.statblock/tormenauk
    source: mcdm.monsters.v1
might: 3
name: Tormenauk
organization: Horde
presence: 2
reason: 2
role: Brute
size: "2"
speed: 6
stability: 2
stamina: "45"
type: statblock
weaknesses:
    - Holy 5
```
