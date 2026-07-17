---
agility: 2
ev: '-'
file_basename: time-raider-mind-healer
file_dpath: monster/retainer/statblock
free_strike: 4
immunities:
    - Psychic 5
intuition: 2
item_id: time-raider-mind-healer
item_name: Time Raider Mind Healer
keywords:
    - Humanoid
    - Time Raider
level: 3
might: 0
name: Time Raider Mind Healer
organization: Retainer
presence: 0
reason: 2
role: Support
scc: mcdm.monsters.v1/monster.retainer.statblock/time-raider-mind-healer
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "39"
type: statblock
---

```ds-sb
agility: 2
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Ranged 3
      effects:
        - roll: ""
          tier1: 5 fire damage
          tier2: 8 fire damage
          tier3: 11 fire damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Laser Lancet
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: The mind healer doesn't take a bane on strikes against creatures with concealment.
      feature_type: trait
      icon: ⭐️
      name: Foresight
      type: feature
free_strike: 4
immunities:
    - Psychic 5
intuition: 2
keywords:
    - Humanoid
    - Time Raider
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/time-raider-mind-healer
    source: mcdm.monsters.v1
might: 0
name: Time Raider Mind Healer
organization: Retainer
presence: 0
reason: 2
role: Support
size: 1M
speed: 5
stability: 0
stamina: "39"
type: statblock
```
