---
agility: 2
ev: 6 for four minions
file_basename: hobgoblin-recruit
file_dpath: monster/hobgoblin/statblock
free_strike: 3
immunities:
    - Fire 2
intuition: 0
item_id: hobgoblin-recruit
item_name: Hobgoblin Recruit
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
might: 3
name: Hobgoblin Recruit
organization: Minion
presence: 1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-recruit
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "9"
type: statblock
with_captain: +4 bonus to Stamina
---

```ds-sb
agility: 2
ev: 6 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage
          tier2: 5 damage
          tier3: 7 damage; [grabbed](../../../condition/grabbed.md) or [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Sword Lunge
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Any non-[minion](../../../rule/organization/minion.md) ally deals 1 extra damage for each recruit [adjacent](../../../rule/combat/adjacent.md) to them.
      feature_type: trait
      icon: ⭐️
      name: Tactical Positioning
      type: feature
    - effects:
        - effect: When the recruit is reduced to 0 [Stamina](../../../rule/health/stamina.md), they spray burning blood. Each creature [adjacent](../../../rule/combat/adjacent.md) to the recruit takes 2 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Infernal Ichor
      type: feature
free_strike: 3
immunities:
    - Fire 2
intuition: 0
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-recruit
    source: mcdm.monsters.v1
might: 3
name: Hobgoblin Recruit
organization: Minion
presence: 1
reason: 0
role: Brute
size: 1M
speed: 5
stability: 0
stamina: "9"
type: statblock
with_captain: +4 bonus to Stamina
```
