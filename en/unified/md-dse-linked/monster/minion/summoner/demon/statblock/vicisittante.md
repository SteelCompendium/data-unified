---
agility: 4
cost: 7 essence for two minions
cost_amount: "7"
cost_resource: essence for two minions
file_basename: vicisittante
file_dpath: monster/minion/summoner/demon/statblock
flavor: It's difficult to identify the base nature of a vicisittante apart from an ever-changing mass of burning flesh. Any surface they touch immediately scars as the demon leaves parts of themselves behind.
free_strike: 7
free_strike_damage_type: Psychic
immunities: []
intuition: 0
item_id: vicisittante
item_name: Vicisittante
keywords:
    - Abyssal
    - Demon
might: 3
movement: —
name: Vicisittante
organization: Minion
presence: -1
reason: 0
role: Harrier
scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/vicisittante
size: "2"
source: mcdm.summoner.v1
speed: 10
stability: 0
stamina: 17 | 17
type: statblock
weaknesses:
    - Holy 1
---

```ds-sb
agility: 4
cost: 7 essence for two minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: 2d10 + R
          tier1: 7 psychic [damage](../../../../../rule/damage/damage.md); P < WEAK [weakened](../../../../../condition/weakened.md) (save ends)
          tier2: 11 psychic [damage](../../../../../rule/damage/damage.md); P < AVERAGE [weakened](../../../../../condition/weakened.md) (save ends)
          tier3: 16 psychic [damage](../../../../../rule/damage/damage.md); P < STRONG [weakened](../../../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Melee
        - Psionic
        - Strike
      name: Cerebral Flay
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: Each creature [adjacent](../../../../../rule/combat/adjacent.md) to the vicisittante can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
flavor: It's difficult to identify the base nature of a vicisittante apart from an ever-changing mass of burning flesh. Any surface they touch immediately scars as the demon leaves parts of themselves behind.
free_strike: 7
immunities: []
intuition: 0
keywords:
    - Abyssal
    - Demon
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/vicisittante
    source: mcdm.summoner.v1
might: 3
movement: —
name: Vicisittante
organization: Minion
presence: -1
reason: 0
role: Harrier
size: "2"
speed: 10
stability: 0
stamina: 17 | 17
type: statblock
weaknesses:
    - Holy 1
```
