---
agility: 5
ev: 12 for four minions
file_basename: unguloid
file_dpath: monster/demon/4th-echelon/statblock
free_strike: 5
intuition: -1
item_id: unguloid
item_name: Unguloid
keywords:
    - Abyssal
    - Demon
level: 10
might: 5
name: Unguloid
organization: Minion
presence: -1
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.demon.4th-echelon.statblock/unguloid
size: "2"
source: mcdm.monsters.v1
speed: 8
stability: 3
stamina: "17"
type: statblock
weaknesses:
    - Holy 5
with_captain: Have a double edge on strikes
---

```ds-sb
agility: 5
ev: 12 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 5 damage; push 2
          tier2: 8 damage; push 4
          tier3: 10 damage; push 6
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Gore Horn
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Any creature within 2 squares of the unguloid can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 5
intuition: -1
keywords:
    - Abyssal
    - Demon
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.demon.4th-echelon.statblock/unguloid
    source: mcdm.monsters.v1
might: 5
name: Unguloid
organization: Minion
presence: -1
reason: -1
role: Brute
size: "2"
speed: 8
stability: 3
stamina: "17"
type: statblock
weaknesses:
    - Holy 5
with_captain: Have a double edge on strikes
```
