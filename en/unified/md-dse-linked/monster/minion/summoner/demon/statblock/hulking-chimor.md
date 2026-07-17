---
agility: 0
cost: 5 essence for three minions
cost_amount: "5"
cost_resource: essence for three minions
file_basename: hulking-chimor
file_dpath: monster/minion/summoner/demon/statblock
flavor: Chimors have no true shape; their bodies restructure and change endlessly. Pieces of the chimor demon snap off inside their prey, causing their bodies to also restructure from the inside out.
free_strike: 3
immunities: []
intuition: 1
item_id: hulking-chimor
item_name: Hulking Chimor
keywords:
    - Abyssal
    - Demon
might: 3
movement: —
name: Hulking Chimor
organization: Minion
presence: 1
reason: 2
role: Defender
scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/hulking-chimor
size: "2"
source: mcdm.summoner.v1
speed: 5
stability: 3
stamina: 7 | 7 | 7
type: statblock
weaknesses:
    - Holy 1
---

```ds-sb
agility: 0
cost: 5 essence for three minions
ev: ""
features:
    - effects:
        - effect: The chimor's melee [free strikes](../../../../../feature/common/main-actions/free-strike.md) inflict M < WEAK [weakened](../../../../../condition/weakened.md) (EoT). The [potency](../../../../../rule/character/potency.md) is increased by the current [round](../../../../../rule/combat/combat-round.md) number.
      feature_type: trait
      icon: ⭐️
      name: Mercurial Strike
      type: feature
    - effects:
        - effect: The chimor doesn't provoke [opportunity attacks](../../../../../rule/combat/opportunity-attack.md) by moving.
      feature_type: trait
      icon: ⭐️
      name: Evershifting
      type: feature
    - effects:
        - effect: Each creature [adjacent](../../../../../rule/combat/adjacent.md) to the chimor can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
flavor: Chimors have no true shape; their bodies restructure and change endlessly. Pieces of the chimor demon snap off inside their prey, causing their bodies to also restructure from the inside out.
free_strike: 3
immunities: []
intuition: 1
keywords:
    - Abyssal
    - Demon
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/hulking-chimor
    source: mcdm.summoner.v1
might: 3
movement: —
name: Hulking Chimor
organization: Minion
presence: 1
reason: 2
role: Defender
size: "2"
speed: 5
stability: 3
stamina: 7 | 7 | 7
type: statblock
weaknesses:
    - Holy 1
```
