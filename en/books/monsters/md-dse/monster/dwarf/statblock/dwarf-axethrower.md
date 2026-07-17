---
agility: 0
ev: 3 for 4 minions
file_basename: dwarf-axethrower
file_dpath: monster/dwarf/statblock
free_strike: 1
intuition: 2
item_id: dwarf-axethrower
item_name: Dwarf Axethrower
keywords:
    - Dwarf
    - Humanoid
level: 1
might: 1
name: Dwarf Axethrower
organization: Minion
presence: 0
reason: 0
role: Defender
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-axethrower
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "7"
type: statblock
with_captain: +2 bonus to Stamina
---

```ds-sb
agility: 0
ev: 3 for 4 minions
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 1 damage
          tier2: 2 damage
          tier3: 3 damage; one ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike)
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Whistling Axes
      target: One creature or object per minion
      type: feature
      usage: Main action
free_strike: 1
intuition: 2
keywords:
    - Dwarf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-axethrower
    source: mcdm.monsters.v1
might: 1
name: Dwarf Axethrower
organization: Minion
presence: 0
reason: 0
role: Defender
size: 1M
speed: 5
stability: 2
stamina: "7"
type: statblock
with_captain: +2 bonus to Stamina
```
