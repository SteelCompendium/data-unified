---
agility: 2
ev: "3"
file_basename: goblin-assassin
file_dpath: monster/goblin/statblock
free_strike: 2
intuition: 0
item_id: goblin-assassin
item_name: Goblin Assassin
keywords:
    - Goblin
    - Humanoid
level: 1
might: -2
movement: Climb
name: Goblin Assassin
organization: Horde
presence: -2
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-assassin
size: 1S
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "15"
type: statblock
---

```ds-sb
agility: 2
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 4 damage
          tier2: 6 damage
          tier3: 7 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Sword Stab
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 2 corruption damage; A < 0 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier2: 4 corruption damage; A < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier3: 5 corruption damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Shadow Chains
      target: Three creatures
      type: feature
      usage: Main action
    - effects:
        - effect: The assassin doesn't provoke [opportunity attacks](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) by moving.
      feature_type: trait
      icon: ⭐️
      name: Crafty
      type: feature
    - effects:
        - effect: The assassin can attempt to hide even while observed.
      feature_type: trait
      icon: ⭐️
      name: Slip Away
      type: feature
free_strike: 2
intuition: 0
keywords:
    - Goblin
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-assassin
    source: mcdm.monsters.v1
might: -2
movement: Climb
name: Goblin Assassin
organization: Horde
presence: -2
reason: 0
role: Ambusher
size: 1S
speed: 6
stability: 0
stamina: "15"
type: statblock
```
