---
agility: 2
ev: "60"
file_basename: gnoll-gnasher
file_dpath: monster/retainer/statblock
free_strike: 3
intuition: 0
item_id: gnoll-gnasher
item_name: Gnoll Gnasher
keywords:
    - Abyssal
    - Gnoll
level: 2
might: 1
name: Gnoll Gnasher
organization: Retainer
presence: 1
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.retainer.statblock/gnoll-gnasher
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: "30"
type: statblock
---

```ds-sb
agility: 2
ev: "60"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 4 damage
          tier2: 7 damage
          tier3: 10 damage; M < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Gnash
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever a non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) ally within 7 squares of the gnasher is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), the gnasher moves up to their speed and can make a melee [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
      feature_type: trait
      icon: ⭐️
      name: Death Frenzy
      type: feature
free_strike: 3
intuition: 0
keywords:
    - Abyssal
    - Gnoll
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/gnoll-gnasher
    source: mcdm.monsters.v1
might: 1
name: Gnoll Gnasher
organization: Retainer
presence: 1
reason: 0
role: Harrier
size: 1M
speed: 7
stability: 1
stamina: "30"
type: statblock
```
