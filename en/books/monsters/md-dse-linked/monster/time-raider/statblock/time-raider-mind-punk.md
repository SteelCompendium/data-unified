---
agility: 0
ev: "10"
file_basename: time-raider-mind-punk
file_dpath: monster/time-raider/statblock
free_strike: 5
immunities:
    - Psychic 3
intuition: 2
item_id: time-raider-mind-punk
item_name: Time Raider Mind Punk
keywords:
    - Humanoid
    - Time Raider
level: 3
might: 2
name: Time Raider Mind Punk
organization: Platoon
presence: 1
reason: 2
role: Hexer
scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-mind-punk
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "40"
type: statblock
---

```ds-sb
agility: 0
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage
          tier2: 8 damage; M < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 11 damage; M < 2 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
      name: Repelling Psihander
      target: Two creatures adjacent to each other
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 2
          tier1: 4 psychic damage; R < 0 [prone](../../../condition/prone.md)
          tier2: 6 psychic damage; [push](../../../movement/forced-movement.md) 1; R < 1 [prone](../../../condition/prone.md) and can't stand (save ends)
          tier3: 9 psychic damage; [push](../../../movement/forced-movement.md) 2; R < 2 [prone](../../../condition/prone.md) and can't stand (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Psionic
      name: Mindpunk
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The mind punk doesn't take a bane on strikes against creatures with concealment.
      feature_type: trait
      icon: ⭐️
      name: Foresight
      type: feature
free_strike: 5
immunities:
    - Psychic 3
intuition: 2
keywords:
    - Humanoid
    - Time Raider
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-mind-punk
    source: mcdm.monsters.v1
might: 2
name: Time Raider Mind Punk
organization: Platoon
presence: 1
reason: 2
role: Hexer
size: "2"
speed: 5
stability: 2
stamina: "40"
type: statblock
```
