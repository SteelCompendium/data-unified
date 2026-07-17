---
agility: 3
ev: "14"
file_basename: hobgoblin-smokebinder
file_dpath: monster/hobgoblin/statblock
free_strike: 6
immunities:
    - Fire 5
intuition: 1
item_id: hobgoblin-smokebinder
item_name: Hobgoblin Smokebinder
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 5
might: 1
movement: Fly, hover
name: Hobgoblin Smokebinder
organization: Platoon
presence: 0
reason: 2
role: Ambusher
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-smokebinder
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "70"
type: statblock
---

```ds-sb
agility: 3
ev: "14"
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: Power Roll + 3
          tier1: 9 fire damage
          tier2: 14 fire damage
          tier3: 17 fire damage; R < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Choking Bolt
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 burst
      effects:
        - roll: ""
          tier1: 11 damage; the target has a double bane on their next power roll
          tier2: 9 damage; the target takes a bane on their next power roll
          tier3: 5 damage
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Smoke Bomb
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: The smokebinder can move through spaces as if they were size 1T and can occupy another creature or object's space. At the end of their turn, the smokebinder can attempt to hide if they haven't taken any damage since their last turn.
      feature_type: trait
      icon: ⭐️
      name: Essence of Smoke
      type: feature
    - effects:
        - effect: When the smokebinder is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they spray burning blood. Each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the smokebinder takes 3 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Infernal Ichor
      type: feature
free_strike: 6
immunities:
    - Fire 5
intuition: 1
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-smokebinder
    source: mcdm.monsters.v1
might: 1
movement: Fly, hover
name: Hobgoblin Smokebinder
organization: Platoon
presence: 0
reason: 2
role: Ambusher
size: 1M
speed: 7
stability: 0
stamina: "70"
type: statblock
```
