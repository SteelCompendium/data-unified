---
agility: 1
ev: "3"
file_basename: goblin-cursespitter
file_dpath: monster/goblin/statblock
free_strike: 1
intuition: 2
item_id: goblin-cursespitter
item_name: Goblin Cursespitter
keywords:
    - Goblin
    - Humanoid
level: 1
might: -2
movement: Climb
name: Goblin Cursespitter
organization: Horde
presence: 0
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-cursespitter
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "10"
type: statblock
---

```ds-sb
agility: 1
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 2
          tier1: 3 corruption damage; I < 0 [weakened](../../../condition/weakened.md) (save ends)
          tier2: 4 corruption damage; I < 1 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 5 corruption damage; I < 2 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Eye of Surlach
      target: One creature
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: I < 0 [prone](../../../condition/prone.md)
          tier2: I < 1 [prone](../../../condition/prone.md) and can't stand (EoT)
          tier3: '[Prone](../../../condition/prone.md); I < 2 can''t stand (save ends)'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Dizzying Hex
      target: One creature
      type: feature
      usage: Maneuver
    - effects:
        - effect: The cursespitter doesn't provoke [opportunity attacks](../../../rule/combat/opportunity-attack.md) by moving.
      feature_type: trait
      icon: ⭐️
      name: Crafty
      type: feature
free_strike: 1
intuition: 2
keywords:
    - Goblin
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-cursespitter
    source: mcdm.monsters.v1
might: -2
movement: Climb
name: Goblin Cursespitter
organization: Horde
presence: 0
reason: 0
role: Hexer
size: 1S
speed: 5
stability: 0
stamina: "10"
type: statblock
```
