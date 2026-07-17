---
agility: 3
ev: 6 for four minions
file_basename: grilp
file_dpath: monster/hobgoblin/statblock
free_strike: 3
immunities:
    - Fire 2
intuition: 1
item_id: grilp
item_name: Grilp
keywords:
    - Devil
    - Hobgoblin
    - Infernal
level: 4
might: -1
movement: Fly
name: Grilp
organization: Minion
presence: 0
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/grilp
size: 1T
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "8"
type: statblock
with_captain: +2 bonus to speed
---

```ds-sb
agility: 3
ev: 6 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage
          tier2: 5 damage
          tier3: 7 damage; the grilp [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Flyby Bite
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Any enemy who makes a saving throw takes a −1 penalty to the saving throw for each grilp [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them.
      feature_type: trait
      icon: ⭐️
      name: Bat Out Of Hell
      type: feature
    - effects:
        - effect: The grilp has concealment from all creatures.
      feature_type: trait
      icon: ⭐️
      name: Shifting Camouflage
      type: feature
free_strike: 3
immunities:
    - Fire 2
intuition: 1
keywords:
    - Devil
    - Hobgoblin
    - Infernal
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/grilp
    source: mcdm.monsters.v1
might: -1
movement: Fly
name: Grilp
organization: Minion
presence: 0
reason: 0
role: Ambusher
size: 1T
speed: 7
stability: 0
stamina: "8"
type: statblock
with_captain: +2 bonus to speed
```
