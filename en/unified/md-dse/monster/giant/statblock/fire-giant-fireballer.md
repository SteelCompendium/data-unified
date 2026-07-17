---
agility: 2
ev: 11 for four minions
file_basename: fire-giant-fireballer
file_dpath: monster/giant/statblock
free_strike: 3
immunities:
    - Fire 9
intuition: 2
item_id: fire-giant-fireballer
item_name: Fire Giant Fireballer
keywords:
    - Fire Giant
    - Giant
level: 9
might: 4
name: Fire Giant Fireballer
organization: Minion
presence: 1
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.giant.statblock/fire-giant-fireballer
size: "4"
source: mcdm.monsters.v1
speed: 7
stability: 5
stamina: "13"
type: statblock
with_captain: +3 bonus to speed
---

```ds-sb
agility: 2
ev: 11 for four minions
features:
    - ability_type: Signature Ability
      distance: 1 burst
      effects:
        - roll: Power Roll + 4
          tier1: 2 fire damage
          tier2: 5 fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier3: 6 fire damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Blazing Leap
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy [grabs](scc.v1:mcdm.heroes.v1/condition/grabbed) the fireballer or uses a melee ability against them, that enemy takes 5 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Searing Skin
      type: feature
free_strike: 3
immunities:
    - Fire 9
intuition: 2
keywords:
    - Fire Giant
    - Giant
level: 9
metadata:
    scc: mcdm.monsters.v1/monster.giant.statblock/fire-giant-fireballer
    source: mcdm.monsters.v1
might: 4
name: Fire Giant Fireballer
organization: Minion
presence: 1
reason: 0
role: Harrier
size: "4"
speed: 7
stability: 5
stamina: "13"
type: statblock
with_captain: +3 bonus to speed
```
