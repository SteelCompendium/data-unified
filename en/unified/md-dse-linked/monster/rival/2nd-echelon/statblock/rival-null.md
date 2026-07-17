---
agility: 3
ev: "28"
file_basename: rival-null
file_dpath: monster/rival/2nd-echelon/statblock
free_strike: 6
intuition: 3
item_id: rival-null
item_name: Rival Null
keywords:
    - Humanoid
    - Rival
level: 5
might: 0
name: Rival Null
organization: Elite
presence: 0
reason: 2
role: Harrier
scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-null
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 3
stamina: "140"
type: statblock
---

```ds-sb
agility: 3
ev: "28"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage; the null [shifts](../../../../movement/shifting.md) up to 3 squares; A < 1 6 damage
          tier2: 14 damage; the null [shifts](../../../../movement/shifting.md) up to 4 squares; A < 2 11 damage
          tier3: 17 damage; the null [shifts](../../../../movement/shifting.md) up to 5 squares; A < 3 11 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Agile Stride
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage; R < 1 [dazed](../../../../condition/dazed.md) (EoT)
          tier2: 14 damage; R < 2 [dazed](../../../../condition/dazed.md) (save ends)
          tier3: 17 damage; R < 3 [dazed](../../../../condition/dazed.md) and [restrained](../../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
      name: Deaden
      target: One creature or object
      type: feature
      usage: Maneuver
    - effects:
        - effect: The first time each round that the null is targeted by a damage-dealing [strike](../../../../rule/combat/strike.md), they halve the damage.
      feature_type: trait
      icon: ⭐️
      name: Inertial Shield
      type: feature
    - effects:
        - effect: At the start of an encounter, the null chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the null and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 6
intuition: 3
keywords:
    - Humanoid
    - Rival
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-null
    source: mcdm.monsters.v1
might: 0
name: Rival Null
organization: Elite
presence: 0
reason: 2
role: Harrier
size: 1M
speed: 7
stability: 3
stamina: "140"
type: statblock
```
