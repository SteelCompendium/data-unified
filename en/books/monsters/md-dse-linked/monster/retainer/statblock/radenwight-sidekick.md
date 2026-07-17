---
agility: 2
ev: '-'
file_basename: radenwight-sidekick
file_dpath: monster/retainer/statblock
free_strike: 2
intuition: 1
item_id: radenwight-sidekick
item_name: Radenwight Sidekick
keywords:
    - Humanoid
    - Radenwight
level: 1
might: 0
movement: Climb
name: Radenwight Sidekick
organization: Retainer
presence: 0
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.retainer.statblock/radenwight-sidekick
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "21"
type: statblock
---

```ds-sb
agility: 2
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 3 damage
          tier2: 5 damage
          tier3: 7 damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Dagger's Bite
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** An ally deals damage to the target.
            **Effect:** The sidekick makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the target.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
        - Weapon
      name: Ready Rodent
      target: One creature
      type: feature
      usage: Triggered action
free_strike: 2
intuition: 1
keywords:
    - Humanoid
    - Radenwight
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/radenwight-sidekick
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: Radenwight Sidekick
organization: Retainer
presence: 0
reason: 0
role: Support
size: 1S
speed: 5
stability: 0
stamina: "21"
type: statblock
```
