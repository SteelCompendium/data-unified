---
agility: 0
ev: "12"
file_basename: hobgoblin-death-captain
file_dpath: monster/hobgoblin/statblock
free_strike: 5
immunities:
    - Fire 4
intuition: 0
item_id: hobgoblin-death-captain
item_name: Hobgoblin Death Captain
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
might: 3
name: Hobgoblin Death Captain
organization: Platoon
presence: 2
reason: 1
role: Support
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-death-captain
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "60"
type: statblock
---

```ds-sb
agility: 0
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 8 damage
          tier2: 8 damage, 4 corruption damage
          tier3: 8 damage, 7 corruption damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
        - Weapon
      name: Blightblade
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 5
      effects:
        - effect: '**Effect:** The target moves up to their speed and can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: On My Mark!
      target: One ally
      type: feature
      usage: Maneuver
    - effects:
        - effect: Any hidden creature who makes a strike against the death captain or any ally within 2 squares of the death captain takes a bane on the strike.
      feature_type: trait
      icon: ⭐️
      name: Battle Ready
      type: feature
    - effects:
        - effect: When the death captain is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they spray burning blood. Each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the death captain takes 3 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Infernal Ichor
      type: feature
free_strike: 5
immunities:
    - Fire 4
intuition: 0
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-death-captain
    source: mcdm.monsters.v1
might: 3
name: Hobgoblin Death Captain
organization: Platoon
presence: 2
reason: 1
role: Support
size: 1M
speed: 5
stability: 2
stamina: "60"
type: statblock
```
