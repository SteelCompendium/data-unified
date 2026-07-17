---
agility: 2
ev: "12"
file_basename: hobgoblin-hell-trooper
file_dpath: monster/hobgoblin/statblock
free_strike: 6
immunities:
    - Fire 4
intuition: 0
item_id: hobgoblin-hell-trooper
item_name: Hobgoblin Hell Trooper
keywords:
    - Goblin
    - Hobgoblin
    - Humanoid
    - Infernal
level: 4
might: 3
name: Hobgoblin Hell Trooper
organization: Platoon
presence: 1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-hell-trooper
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "70"
type: statblock
---

```ds-sb
agility: 2
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 7 fire damage
          tier2: 10 fire damage
          tier3: 13 fire damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Fire Flail
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Ranged 5
      effects:
        - effect: '**Effect:** If the target has P < 2, they are taunted (EoT). While taunted this way, the target takes 1d6 fire damage whenever they use an ability or strike that doesn''t target the trooper.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Fight Me, Coward!
      target: One creature
      type: feature
      usage: Maneuver
    - effects:
        - effect: When the trooper is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they spray burning blood. Each creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the trooper takes 3 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Infernal Ichor
      type: feature
free_strike: 6
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
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/hobgoblin-hell-trooper
    source: mcdm.monsters.v1
might: 3
name: Hobgoblin Hell Trooper
organization: Platoon
presence: 1
reason: 0
role: Brute
size: 1M
speed: 5
stability: 2
stamina: "70"
type: statblock
```
