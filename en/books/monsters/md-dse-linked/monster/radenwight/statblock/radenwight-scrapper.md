---
agility: 1
ev: 3 for 4 minions
file_basename: radenwight-scrapper
file_dpath: monster/radenwight/statblock
free_strike: 1
intuition: 0
item_id: radenwight-scrapper
item_name: Radenwight Scrapper
keywords:
    - Humanoid
    - Radenwight
level: 1
might: -1
movement: Climb
name: Radenwight Scrapper
organization: Minion
presence: 2
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.radenwight.statblock/radenwight-scrapper
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "5"
type: statblock
with_captain: +2 bonus to melee distance
---

```ds-sb
agility: 1
ev: 3 for 4 minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 1 damage
          tier2: 2 damage; [taunted](../../../condition/taunted.md) (EoT)
          tier3: 3 damage; [taunted](../../../condition/taunted.md) (EoT)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Buckler Bash
      target: One creature or object per minion
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** An ally deals damage to the target.
            **Effect:** The scrapper makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the target.
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
    scc: mcdm.monsters.v1/monster.radenwight.statblock/radenwight-scrapper
    source: mcdm.monsters.v1
might: -1
movement: Climb
name: Radenwight Scrapper
organization: Minion
presence: 2
reason: 0
role: Defender
size: 1S
speed: 5
stability: 1
stamina: "5"
type: statblock
with_captain: +2 bonus to melee distance
```
