---
features:
    - distance: Self
      icon: "\U0001F464"
      level: 4
      name: Big Windup
      sections:
        - label: Effect
          text: Until the start of the retainer's next turn, strikes made against the retainer gain an edge. At the start of the retainer's next turn, they gain 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge), and any ability they use before the end of their turn that [force moves](scc.v1:mcdm.heroes.v1/movement/forced-movement) a creature can move that creature 2 additional squares.
      target: Self
      usage: Maneuver
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Overhand Swat
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            low: 8 damage
            mid: 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      sections:
        - label: Effect
          text: If the target ends any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) from this ability in a square [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the retainer's mentor, the mentor can make a melee [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Dizzying Sweep
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 20 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
            low: 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
            mid: 14 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      sections:
        - label: Effect
          text: The retainer is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) until the end of their next turn.
      target: Each creature in the area
      usage: Main action
file_basename: brute
file_dpath: monster/retainer/role-advancement
item_id: brute
item_name: Brute Abilities
name: Brute Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/brute
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - distance: Self
      icon: "\U0001F464"
      level: 4
      name: Big Windup
      sections:
        - label: Effect
          text: Until the start of the retainer's next turn, strikes made against the retainer gain an edge. At the start of the retainer's next turn, they gain 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge), and any ability they use before the end of their turn that [force moves](scc.v1:mcdm.heroes.v1/movement/forced-movement) a creature can move that creature 2 additional squares.
      target: Self
      usage: Maneuver
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Overhand Swat
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            low: 8 damage
            mid: 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      sections:
        - label: Effect
          text: If the target ends any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) from this ability in a square [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the retainer's mentor, the mentor can make a melee [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Dizzying Sweep
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 20 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
            low: 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
            mid: 14 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      sections:
        - label: Effect
          text: The retainer is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) until the end of their next turn.
      target: Each creature in the area
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.role-advancement/brute
    source: mcdm.monsters.v1
name: Brute Abilities
type: featureblock
```
