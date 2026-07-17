---
agility: 1
ev: "4"
file_basename: gnoll-bonesplitter
file_dpath: monster/gnoll/statblock
free_strike: 3
intuition: 0
item_id: gnoll-bonesplitter
item_name: Gnoll Bonesplitter
keywords:
    - Abyssal
    - Gnoll
level: 2
might: 2
name: Gnoll Bonesplitter
organization: Horde
presence: 1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.gnoll.statblock/gnoll-bonesplitter
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "25"
type: statblock
---

```ds-sb
agility: 1
ev: "4"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier2: 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 8 damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed); M < 2 the target takes a bane on the Escape Grab maneuver
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Three-Tail Flail
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 4 Malice
      distance: 2 burst
      effects:
        - effect: '**Effect:** Up to three targets can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike). If any target hasn''t used their own Cackletongue maneuver on this turn, they can use it immediately at no cost.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Bonesplitter's Cackletongue
      target: Self and each ally in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: Whenever a non-[minion](scc.v1:mcdm.monsters.v1/rule.organization/minion) ally within 5 squares of the bonesplitter is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), the bonesplitter moves up to their speed and can make a melee [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
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
    scc: mcdm.monsters.v1/monster.gnoll.statblock/gnoll-bonesplitter
    source: mcdm.monsters.v1
might: 2
name: Gnoll Bonesplitter
organization: Horde
presence: 1
reason: 0
role: Brute
size: 1L
speed: 5
stability: 1
stamina: "25"
type: statblock
```
