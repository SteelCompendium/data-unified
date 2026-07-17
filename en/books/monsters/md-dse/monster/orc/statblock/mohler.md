---
agility: 2
ev: 3 for four minions
file_basename: mohler
file_dpath: monster/orc/statblock
free_strike: 2
intuition: 1
item_id: mohler
item_name: Mohler
keywords:
    - Animal
    - Orc
level: 1
might: 0
movement: Burrow
name: Mohler
organization: Minion
presence: -3
reason: -4
role: Ambusher
scc: mcdm.monsters.v1/monster.orc.statblock/mohler
size: 1S
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: "4"
type: statblock
with_captain: +2 bonus to speed
---

```ds-sb
agility: 2
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage
          tier2: 4 damage
          tier3: 5 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Earth Bump
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The mohler doesn't need [line of effect](scc.v1:mcdm.heroes.v1/rule.combat/line-of-effect) to use abilities against creatures or objects touching the ground.
      feature_type: trait
      icon: ⭐️
      name: Seismic Sense
      type: feature
    - effects:
        - effect: The mohler can use the Dig maneuver at the start of the encounter. Additionally, while the mohler [burrows](scc.v1:mcdm.heroes.v1/movement/burrow) within 1 square below the ground, the ground above where they burrow is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
      feature_type: trait
      icon: ⭐️
      name: Ground Grinder
      type: feature
free_strike: 2
intuition: 1
keywords:
    - Animal
    - Orc
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/mohler
    source: mcdm.monsters.v1
might: 0
movement: Burrow
name: Mohler
organization: Minion
presence: -3
reason: -4
role: Ambusher
size: 1S
speed: 7
stability: 1
stamina: "4"
type: statblock
with_captain: +2 bonus to speed
```
