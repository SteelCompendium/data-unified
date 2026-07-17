---
agility: 2
ev: 3 for 4 minions
file_basename: radenwight-swiftpaw
file_dpath: monster/radenwight/statblock
free_strike: 1
intuition: 0
item_id: radenwight-swiftpaw
item_name: Radenwight Swiftpaw
keywords:
    - Humanoid
    - Radenwight
level: 1
might: 0
movement: Climb
name: Radenwight Swiftpaw
organization: Minion
presence: -1
reason: 1
role: Harrier
scc: mcdm.monsters.v1/monster.radenwight.statblock/radenwight-swiftpaw
size: 1S
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 2
ev: 3 for 4 minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 1 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1, the swiftpaw can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square
          tier2: 2 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2, the swiftpaw [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares
          tier3: 3 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3, the swiftpaw [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Rapier Flunge
      target: One creature or object per minion
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** An ally deals damage to the target.
            **Effect:** The swiftpaw makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
        - Weapon
      name: Ready Rodent
      target: One creature
      type: feature
      usage: Triggered action
free_strike: 1
intuition: 0
keywords:
    - Humanoid
    - Radenwight
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.radenwight.statblock/radenwight-swiftpaw
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: Radenwight Swiftpaw
organization: Minion
presence: -1
reason: 1
role: Harrier
size: 1S
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: Gain an edge on strikes
```
