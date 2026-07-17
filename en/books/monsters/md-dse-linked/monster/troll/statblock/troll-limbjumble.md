---
agility: 1
ev: 7 for four minions
file_basename: troll-limbjumble
file_dpath: monster/troll/statblock
free_strike: 3
intuition: -1
item_id: troll-limbjumble
item_name: Troll Limbjumble
keywords:
    - Troll
level: 5
might: 3
name: Troll Limbjumble
organization: Minion
presence: -1
reason: -2
role: Hexer
scc: mcdm.monsters.v1/monster.troll.statblock/troll-limbjumble
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "8"
type: statblock
weaknesses:
    - Acid 8
    - fire
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 1
ev: 7 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 3 damage; A < 2 [prone](../../../condition/prone.md)
          tier2: 5 damage; A < 3 [prone](../../../condition/prone.md)
          tier3: 6 damage; [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Arm and a Leg
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: At the start of each of the limbjumble's [squad](../../../rule/monster/squad.md)'s turns, the squad's [Stamina](../../../rule/health/stamina.md) pool increases as if each limbjumble were at full [Stamina](../../../rule/health/stamina.md).
      feature_type: trait
      icon: ⭐️
      name: Hyper-Regeneration
      type: feature
free_strike: 3
intuition: -1
keywords:
    - Troll
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.troll.statblock/troll-limbjumble
    source: mcdm.monsters.v1
might: 3
name: Troll Limbjumble
organization: Minion
presence: -1
reason: -2
role: Hexer
size: 1S
speed: 5
stability: 0
stamina: "8"
type: statblock
weaknesses:
    - Acid 8
    - fire
with_captain: Gain an edge on strikes
```
