---
agility: 2
ev: 10 for four minions
file_basename: sand-stone-giant
file_dpath: monster/giant/statblock
free_strike: 3
intuition: 3
item_id: sand-stone-giant
item_name: Sand Stone Giant
keywords:
    - Giant
    - Stone Giant
level: 8
might: 4
movement: Burrow
name: Sand Stone Giant
organization: Minion
presence: 0
reason: 0
role: Controller
scc: mcdm.monsters.v1/monster.giant.statblock/sand-stone-giant
size: "4"
source: mcdm.monsters.v1
speed: 7
stability: 10
stamina: "14"
type: statblock
with_captain: +6 bonus to Stamina
---

```ds-sb
agility: 2
ev: 10 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 4
          tier1: 3 damage; [slide](../../../movement/forced-movement.md) 2
          tier2: 6 damage; [slide](../../../movement/forced-movement.md) 3; A < 3 [restrained](../../../condition/restrained.md) (save ends)
          tier3: 8 damage; [slide](../../../movement/forced-movement.md) 4; A < 4 [restrained](../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
      name: Buried in Sand
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever an enemy obtains a tier 1 outcome on a melee ability used against the sand stone giant, they take a bane on that ability until the end of the encounter.
      feature_type: trait
      icon: ⭐️
      name: Stonebreaker Flesh
      type: feature
    - effects:
        - effect: The sand stone giant ignores [difficult terrain](../../../movement/difficult-terrain.md).
      feature_type: trait
      icon: ⭐️
      name: Stone Steps
      type: feature
    - effects:
        - effect: The sand stone giant can [burrow](../../../movement/burrow.md) through stone, but can't drag other creatures underground when they do so.
      feature_type: trait
      icon: ⭐️
      name: Stone Swim
      type: feature
free_strike: 3
intuition: 3
keywords:
    - Giant
    - Stone Giant
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.giant.statblock/sand-stone-giant
    source: mcdm.monsters.v1
might: 4
movement: Burrow
name: Sand Stone Giant
organization: Minion
presence: 0
reason: 0
role: Controller
size: "4"
speed: 7
stability: 10
stamina: "14"
type: statblock
with_captain: +6 bonus to Stamina
```
