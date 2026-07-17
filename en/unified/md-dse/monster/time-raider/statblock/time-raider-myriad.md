---
agility: 1
ev: 5 for four minions
file_basename: time-raider-myriad
file_dpath: monster/time-raider/statblock
free_strike: 3
immunities:
    - Psychic 3
intuition: 1
item_id: time-raider-myriad
item_name: Time Raider Myriad
keywords:
    - Humanoid
    - Time Raider
level: 3
might: 2
name: Time Raider Myriad
organization: Minion
presence: 1
reason: 2
role: Brute
scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-myriad
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "8"
type: statblock
with_captain: +1 damage bonus to strikes
---

```ds-sb
agility: 1
ev: 5 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 5 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 6 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3, [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
      name: Fifth Fist
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The myriad doesn't take a bane on strikes against creatures with concealment.
      feature_type: trait
      icon: ⭐️
      name: Foresight
      type: feature
free_strike: 3
immunities:
    - Psychic 3
intuition: 1
keywords:
    - Humanoid
    - Time Raider
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-myriad
    source: mcdm.monsters.v1
might: 2
name: Time Raider Myriad
organization: Minion
presence: 1
reason: 2
role: Brute
size: 1M
speed: 5
stability: 0
stamina: "8"
type: statblock
with_captain: +1 damage bonus to strikes
```
