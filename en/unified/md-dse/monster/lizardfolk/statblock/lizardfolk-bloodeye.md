---
agility: 1
ev: "6"
file_basename: lizardfolk-bloodeye
file_dpath: monster/lizardfolk/statblock
free_strike: 3
intuition: 2
item_id: lizardfolk-bloodeye
item_name: Lizardfolk Bloodeye
keywords:
    - Humanoid
    - Lizardfolk
level: 1
might: 1
movement: Swim
name: Lizardfolk Bloodeye
organization: Platoon
presence: 0
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-bloodeye
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "20"
type: statblock
---

```ds-sb
agility: 1
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage; A < 0 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier2: 7 damage; A < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier3: 9 damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Bola Knock
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 5 acid damage; M < 0 the target has line of effect only within 4 squares (save ends)
          tier2: 7 acid damage; M < 1 the target has line of effect only within 3 squares (save ends)
          tier3: 9 acid damage; M < 2 the target has line of effect only within 2 squares (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Bloodshot
      target: One creature
      type: feature
      usage: Main action
    - effects:
        - effect: While the bloodeye has a tail, whenever they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed), [prone](scc.v1:mcdm.heroes.v1/condition/prone), [slowed](scc.v1:mcdm.heroes.v1/condition/slowed), or [weakened](scc.v1:mcdm.heroes.v1/condition/weakened), they can lose their tail to immediately end that condition, then [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares.
      feature_type: trait
      icon: ⭐️
      name: Reptilian Escape
      type: feature
free_strike: 3
intuition: 2
keywords:
    - Humanoid
    - Lizardfolk
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-bloodeye
    source: mcdm.monsters.v1
might: 1
movement: Swim
name: Lizardfolk Bloodeye
organization: Platoon
presence: 0
reason: 0
role: Hexer
size: 1M
speed: 5
stability: 0
stamina: "20"
type: statblock
```
