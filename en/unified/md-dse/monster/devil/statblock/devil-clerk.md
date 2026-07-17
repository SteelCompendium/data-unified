---
agility: 0
ev: 7 for four minions
file_basename: devil-clerk
file_dpath: monster/devil/statblock
free_strike: 3
immunities:
    - Fire 5
intuition: 1
item_id: devil-clerk
item_name: Devil Clerk
keywords:
    - Devil
    - Infernal
level: 5
might: 3
name: Devil Clerk
organization: Minion
presence: 2
reason: 1
role: Brute
scc: mcdm.monsters.v1/monster.devil.statblock/devil-clerk
size: 1M
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "10"
type: statblock
with_captain: +2 damage bonus to strikes
---

```ds-sb
agility: 0
ev: 7 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage; push 1
          tier2: 6 damage; push 2
          tier3: 7 damage; push 3
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Quill Pushing
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: If a creature within 10 squares speaks the clerk's true name, the clerk loses their fire immunity and any nondamaging effects of their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: True Name
      type: feature
free_strike: 3
immunities:
    - Fire 5
intuition: 1
keywords:
    - Devil
    - Infernal
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.devil.statblock/devil-clerk
    source: mcdm.monsters.v1
might: 3
name: Devil Clerk
organization: Minion
presence: 2
reason: 1
role: Brute
size: 1M
speed: 6
stability: 0
stamina: "10"
type: statblock
with_captain: +2 damage bonus to strikes
```
