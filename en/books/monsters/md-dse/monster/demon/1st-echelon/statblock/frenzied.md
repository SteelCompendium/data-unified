---
agility: 2
ev: 3 for four minions
file_basename: frenzied
file_dpath: monster/demon/1st-echelon/statblock
free_strike: 1
intuition: -1
item_id: frenzied
item_name: Frenzied
keywords:
    - Abyssal
    - Demon
level: 1
might: 0
name: Frenzied
organization: Minion
presence: -1
reason: -1
role: Harrier
scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/frenzied
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "4"
type: statblock
weaknesses:
    - Holy 3
with_captain: +2 bonus to speed
---

```ds-sb
agility: 2
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 1 damage
          tier2: 2 damage
          tier3: 3 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Rip and Tear
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Any creature within 2 squares of the frenzied can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 1
intuition: -1
keywords:
    - Abyssal
    - Demon
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/frenzied
    source: mcdm.monsters.v1
might: 0
name: Frenzied
organization: Minion
presence: -1
reason: -1
role: Harrier
size: 1M
speed: 6
stability: 0
stamina: "4"
type: statblock
weaknesses:
    - Holy 3
with_captain: +2 bonus to speed
```
