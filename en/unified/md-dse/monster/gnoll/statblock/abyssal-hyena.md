---
agility: 1
ev: 4 for four minions
file_basename: abyssal-hyena
file_dpath: monster/gnoll/statblock
free_strike: 3
intuition: 0
item_id: abyssal-hyena
item_name: Abyssal Hyena
keywords:
    - Abyssal
    - Animal
    - Gnoll
level: 2
might: 2
name: Abyssal Hyena
organization: Minion
presence: -2
reason: -3
role: Brute
scc: mcdm.monsters.v1/monster.gnoll.statblock/abyssal-hyena
size: 1M
source: mcdm.monsters.v1
speed: 8
stability: 1
stamina: "7"
type: statblock
with_captain: +2 bonus to speed
---

```ds-sb
agility: 1
ev: 4 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage
          tier2: 4 damage
          tier3: 6 damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Snapjaw
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the abyssal hyena is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they can make a melee [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) before dying.
      feature_type: trait
      icon: ⭐️
      name: Death Snap
      type: feature
free_strike: 3
intuition: 0
keywords:
    - Abyssal
    - Animal
    - Gnoll
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.gnoll.statblock/abyssal-hyena
    source: mcdm.monsters.v1
might: 2
name: Abyssal Hyena
organization: Minion
presence: -2
reason: -3
role: Brute
size: 1M
speed: 8
stability: 1
stamina: "7"
type: statblock
with_captain: +2 bonus to speed
```
