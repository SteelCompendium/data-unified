---
agility: 5
ev: "12"
file_basename: vicisitator
file_dpath: monster/demon/4th-echelon/statblock
free_strike: 4
intuition: -2
item_id: vicisitator
item_name: Vicisitator
keywords:
    - Abyssal
    - Demon
level: 10
might: 4
name: Vicisitator
organization: Horde
presence: -3
reason: -1
role: Harrier
scc: mcdm.monsters.v1/monster.demon.4th-echelon.statblock/vicisitator
size: 1M
source: mcdm.monsters.v1
speed: 9
stability: 0
stamina: "60"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 5
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 10
      effects:
        - roll: Power Roll + 5
          tier1: 9 damage
          tier2: 12 damage
          tier3: 14 damage; I < 5 the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Warp Touch
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 6 x 3 line within 1
      effects:
        - roll: Power Roll + 5
          tier1: 4 psychic damage; P < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier2: 7 psychic damage; P < 4 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier3: 9 psychic damage; P < 5 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
      name: Soul Flay
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: While the vicisitator is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the vicisitator can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 4
intuition: -2
keywords:
    - Abyssal
    - Demon
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.demon.4th-echelon.statblock/vicisitator
    source: mcdm.monsters.v1
might: 4
name: Vicisitator
organization: Horde
presence: -3
reason: -1
role: Harrier
size: 1M
speed: 9
stability: 0
stamina: "60"
type: statblock
weaknesses:
    - Holy 5
```
