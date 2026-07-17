---
agility: 4
cost: 2 Malice for two minions
cost_amount: "2"
cost_resource: Malice for two minions
file_basename: grave-knight
file_dpath: monster/rival/4th-echelon/summoner/minion/statblock
free_strike: 5
immunities:
    - Corruption 5
    - poison 5
intuition: 3
item_id: grave-knight
item_name: Grave Knight
keywords:
    - Undead
might: 5
movement: —
name: Grave Knight
organization: Minion
presence: 4
reason: 3
role: Brute
scc: mcdm.summoner.v1/monster.rival.4th-echelon.summoner.minion.statblock/grave-knight
size: 1M
source: mcdm.summoner.v1
speed: 6
stability: 1
stamina: 15 | 15
type: statblock
weaknesses: []
---

```ds-sb
agility: 4
cost: 2 Malice for two minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: 2d10 + 5
          tier1: 5 corruption damage; M < 3 [bleeding](../../../../../../condition/bleeding.md) ([EoT](../../../../../../rule/combat/end-of-turn.md))
          tier2: 7 corruption damage; M < 4 [bleeding](../../../../../../condition/bleeding.md) ([EoT](../../../../../../rule/combat/end-of-turn.md))
          tier3: 9 corruption damage; M < 5 [bleeding](../../../../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Knight Strike
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the grave knight is reduced to 0 [Stamina](../../../../../../rule/health/stamina.md), they can make a melee [free strike](../../../../../../feature/common/main-actions/free-strike.md) before being destroyed.
      feature_type: trait
      icon: ⭐️
      name: To the Grave
      type: feature
free_strike: 5
immunities:
    - Corruption 5
    - poison 5
intuition: 3
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.rival.4th-echelon.summoner.minion.statblock/grave-knight
    source: mcdm.summoner.v1
might: 5
movement: —
name: Grave Knight
organization: Minion
presence: 4
reason: 3
role: Brute
size: 1M
speed: 6
stability: 1
stamina: 15 | 15
type: statblock
weaknesses: []
```
