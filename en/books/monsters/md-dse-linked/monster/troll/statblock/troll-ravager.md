---
agility: 2
ev: 11 for four minions
file_basename: troll-ravager
file_dpath: monster/troll/statblock
free_strike: 4
intuition: 1
item_id: troll-ravager
item_name: Troll Ravager
keywords:
    - Giant
    - Troll
level: 9
might: 4
name: Troll Ravager
organization: Minion
presence: 1
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.troll.statblock/troll-ravager
size: "2"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "15"
type: statblock
weaknesses:
    - Acid 5
    - fire
with_captain: +2 bonus to speed
---

```ds-sb
agility: 2
ev: 11 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 4 damage; the ravager can [shift](../../../movement/shifting.md) 1 square
          tier2: 6 damage; the ravager [shifts](../../../movement/shifting.md) up to 2 squares
          tier3: 8 damage; the ravager [shifts](../../../movement/shifting.md) up to 3 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Dine and Dash
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The ravager dies only if their [squad](../../../rule/monster/squad.md)'s [Stamina](../../../rule/health/stamina.md) pool is reduced to 0 [Stamina](../../../rule/health/stamina.md) by acid or fire damage, if they end their turn with 0 [Stamina](../../../rule/health/stamina.md) in their [squad](../../../rule/monster/squad.md)'s [Stamina](../../../rule/health/stamina.md) pool, or if they take acid or fire damage while their [squad](../../../rule/monster/squad.md)'s [Stamina](../../../rule/health/stamina.md) pool is at 0 [Stamina](../../../rule/health/stamina.md).
      feature_type: trait
      icon: ⭐️
      name: Group Appetite
      type: feature
free_strike: 4
intuition: 1
keywords:
    - Giant
    - Troll
level: 9
metadata:
    scc: mcdm.monsters.v1/monster.troll.statblock/troll-ravager
    source: mcdm.monsters.v1
might: 4
name: Troll Ravager
organization: Minion
presence: 1
reason: 0
role: Harrier
size: "2"
speed: 8
stability: 2
stamina: "15"
type: statblock
weaknesses:
    - Acid 5
    - fire
with_captain: +2 bonus to speed
```
