---
agility: 1
ev: 3 for four minions
file_basename: lizardfolk-shellguard
file_dpath: monster/lizardfolk/statblock
free_strike: 1
intuition: 0
item_id: lizardfolk-shellguard
item_name: Lizardfolk Shellguard
keywords:
    - Humanoid
    - Lizardfolk
level: 1
might: 2
movement: Swim
name: Lizardfolk Shellguard
organization: Minion
presence: 0
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-shellguard
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "6"
type: statblock
with_captain: +2 bonus to Stamina
---

```ds-sb
agility: 1
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
        - Melee
        - Strike
        - Weapon
      name: Shield Smash
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: While the shellguard has a tail, whenever they are [grabbed](../../../condition/grabbed.md), [prone](../../../condition/prone.md), [slowed](../../../condition/slowed.md), or [weakened](../../../condition/weakened.md), they can lose their tail to immediately end that condition, then [shift](../../../movement/shifting.md) up to 2 squares.
      feature_type: trait
      icon: ⭐️
      name: Reptilian Escape
      type: feature
free_strike: 1
intuition: 0
keywords:
    - Humanoid
    - Lizardfolk
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-shellguard
    source: mcdm.monsters.v1
might: 2
movement: Swim
name: Lizardfolk Shellguard
organization: Minion
presence: 0
reason: 0
role: Defender
size: 1L
speed: 5
stability: 1
stamina: "6"
type: statblock
with_captain: +2 bonus to Stamina
```
