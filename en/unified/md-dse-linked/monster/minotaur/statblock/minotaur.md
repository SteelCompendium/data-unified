---
agility: 2
ev: "20"
file_basename: minotaur
file_dpath: monster/minotaur/statblock
free_strike: 5
intuition: 1
item_id: minotaur
item_name: Minotaur
keywords:
    - Accursed
    - Humanoid
    - Minotaur
level: 3
might: 2
name: Minotaur
organization: Elite
presence: -1
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.minotaur.statblock/minotaur
size: "2"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "100"
type: statblock
---

```ds-sb
agility: 2
ev: "20"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; [push](../../../movement/forced-movement.md) 1
          tier2: 11 damage; [push](../../../movement/forced-movement.md) 2
          tier3: 14 damage; [push](../../../movement/forced-movement.md) 3
        - effect: The minotaur [shifts](../../../movement/shifting.md) up to 3 squares.
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Flail and Blade
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Self
      effects:
        - effect: Until the end of their next turn, the minotaur has damage immunity 2 and deals an extra 5 damage with strikes. On their next turn, the minotaur can use one additional maneuver.
          name: Effect
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Primal Bay
      target: Self
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage; I < 0 [dazed](../../../condition/dazed.md) (save ends)
          tier2: 8 damage; I < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 9 damage; I < 2 [dazed](../../../condition/dazed.md) (save ends)
        - effect: If this ability is used as part of the Charge main action, its [potency](../../../rule/character/potency.md) increases by 1.
          name: Effect
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Goring Horns
      target: One creature or object
      type: feature
      usage: Maneuver
    - distance: Ranged 8
      effects:
        - effect: The minotaur uses the Charge main action and either Flail and Blade or Goring Horns against the target.
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Retaliatory Strike
      target: The triggering creature
      trigger: A creature within distance deals damage to the minotaur.
      type: feature
      usage: Triggered action
    - effects:
        - effect: The minotaur can't obtain less than a tier 2 outcome when making tests to navigate, search, or seek.
      feature_type: trait
      icon: ⭐️
      name: Minotaur Sense
      type: feature
free_strike: 5
intuition: 1
keywords:
    - Accursed
    - Humanoid
    - Minotaur
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.minotaur.statblock/minotaur
    source: mcdm.monsters.v1
might: 2
name: Minotaur
organization: Elite
presence: -1
reason: 0
role: Harrier
size: "2"
speed: 8
stability: 2
stamina: "100"
type: statblock
```
