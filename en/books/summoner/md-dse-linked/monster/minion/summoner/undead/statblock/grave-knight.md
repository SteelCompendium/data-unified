---
agility: 1
cost: 3 essence for two minions
cost_amount: "3"
cost_resource: essence for two minions
file_basename: grave-knight
file_dpath: monster/minion/summoner/undead/statblock
flavor: The grave knights are zombie warriors that continue to fight after death. Any blood spilled at a grave knight's hand runs pitch black.
free_strike: 5
immunities:
    - Corruption R
    - Poison R
intuition: 0
item_id: grave-knight
item_name: Grave Knight
keywords:
    - Undead
might: 2
movement: —
name: Grave Knight
organization: Minion
presence: 1
reason: 0
role: Brute
scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/grave-knight
size: 1M
source: mcdm.summoner.v1
speed: 6
stability: 1
stamina: 6 | 6
type: statblock
weaknesses: []
---

```ds-sb
agility: 1
cost: 3 essence for two minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: 2d10 + R
          tier1: 5 corruption damage; M < WEAK [bleeding](../../../../../condition/bleeding.md) ([EoT](../../../../../rule/combat/end-of-turn.md))
          tier2: 7 corruption damage; M < AVERAGE [bleeding](../../../../../condition/bleeding.md) ([EoT](../../../../../rule/combat/end-of-turn.md))
          tier3: 9 corruption damage; M < STRONG [bleeding](../../../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Knight Strike
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the grave knight is reduced to 0 [Stamina](../../../../../rule/health/stamina.md), they can make a melee [free strike](../../../../../feature/common/main-actions/free-strike.md) before being destroyed.
      feature_type: trait
      icon: ⭐️
      name: To the Grave
      type: feature
flavor: The grave knights are zombie warriors that continue to fight after death. Any blood spilled at a grave knight's hand runs pitch black.
free_strike: 5
immunities:
    - Corruption R
    - Poison R
intuition: 0
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/grave-knight
    source: mcdm.summoner.v1
might: 2
movement: —
name: Grave Knight
organization: Minion
presence: 1
reason: 0
role: Brute
size: 1M
speed: 6
stability: 1
stamina: 6 | 6
type: statblock
weaknesses: []
```
