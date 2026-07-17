---
agility: 2
ev: 5 for four minions
file_basename: time-raider-archon
file_dpath: monster/time-raider/statblock
free_strike: 2
immunities:
    - Psychic 3
intuition: 1
item_id: time-raider-archon
item_name: Time Raider Archon
keywords:
    - Humanoid
    - Time Raider
level: 3
might: 2
name: Time Raider Archon
organization: Minion
presence: -1
reason: 2
role: Harrier
scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-archon
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "7"
type: statblock
with_captain: +1 damage bonus to strikes
---

```ds-sb
agility: 2
ev: 5 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage
          tier2: 4 damage
          tier3: 5 damage; one ally can make a [free strike](../../../feature/common/main-actions/free-strike.md) against the target
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Psionic
        - Strike
        - Weapon
      name: Brutal Flail
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The archon doesn't take a bane on strikes against creatures with concealment.
      feature_type: trait
      icon: ⭐️
      name: Foresight
      type: feature
free_strike: 2
immunities:
    - Psychic 3
intuition: 1
keywords:
    - Humanoid
    - Time Raider
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.time-raider.statblock/time-raider-archon
    source: mcdm.monsters.v1
might: 2
name: Time Raider Archon
organization: Minion
presence: -1
reason: 2
role: Harrier
size: 1M
speed: 7
stability: 0
stamina: "7"
type: statblock
with_captain: +1 damage bonus to strikes
```
