---
agility: 0
ev: "7"
file_basename: bale-eye
file_dpath: monster/demon/2nd-echelon/statblock
free_strike: 3
intuition: 3
item_id: bale-eye
item_name: Bale Eye
keywords:
    - Abyssal
    - Demon
level: 5
might: 0
movement: Fly
name: Bale Eye
organization: Horde
presence: 3
reason: 3
role: Hexer
scc: mcdm.monsters.v1/monster.demon.2nd-echelon.statblock/bale-eye
size: "4"
source: mcdm.monsters.v1
speed: 6
stability: 2
stamina: "30"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 0
ev: "7"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 3
          tier1: 6 psychic damage
          tier2: 8 psychic damage
          tier3: 9 psychic damage
        - effect: The target has corruption [weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (EoT).
          name: Effect
        - cost: 2 Malice
          effect: If the target has I < 2, they have corruption [weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends).
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Wilting Visions
      target: One creature
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 4 cube within 5
      effects:
        - effect: The bale eye must create the cube beneath themself.
          name: Special
          roll: Power Roll + 3
          tier1: 3 psychic damage; A < 1 the target is warped (save ends)
          tier2: 5 psychic damage; A < 2 the target is warped (save ends)
          tier3: 6 psychic damage; A < 3 the target is warped (save ends)
        - effect: While warped, a creature has a double [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on power rolls using any characteristic higher than 0, and has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on power rolls using any characteristic lower than 0.
          name: Effect
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Demonwarp Tears
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: While the bale eye is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 5 squares of the bale eye can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 3
intuition: 3
keywords:
    - Abyssal
    - Demon
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.demon.2nd-echelon.statblock/bale-eye
    source: mcdm.monsters.v1
might: 0
movement: Fly
name: Bale Eye
organization: Horde
presence: 3
reason: 3
role: Hexer
size: "4"
speed: 6
stability: 2
stamina: "30"
type: statblock
weaknesses:
    - Holy 5
```
