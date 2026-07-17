---
agility: 0
cost: 7 essence for two minions
cost_amount: "7"
cost_resource: essence for two minions
file_basename: faded-blightling
file_dpath: monster/minion/summoner/demon/statblock
flavor: This cherubin creature is bloated and warped by demonic energy. The lights from their myriad eyes have all but gone out, now resembling pustules across their body.
free_strike: 7
immunities: []
intuition: 4
item_id: faded-blightling
item_name: Faded Blightling
keywords:
    - Abyssal
    - Demon
might: 0
movement: Fly
name: Faded Blightling
organization: Minion
presence: 3
reason: -1
role: Support
scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/faded-blightling
size: 1L
source: mcdm.summoner.v1
speed: 5
stability: 0
stamina: 17 | 17
type: statblock
weaknesses:
    - Holy 1
---

```ds-sb
agility: 0
cost: 7 essence for two minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: 2d10 + R
          tier1: 7 corruption [damage](../../../../../rule/damage/damage.md); P < WEAK [bleeding](../../../../../condition/bleeding.md) (EoT)
          tier2: 11 corruption [damage](../../../../../rule/damage/damage.md); P < AVERAGE [bleeding](../../../../../condition/bleeding.md) (EoT)
          tier3: 16 corruption [damage](../../../../../rule/damage/damage.md); P < STRONG [bleeding](../../../../../condition/bleeding.md) (EoT)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Blighted Strike
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The blightling must land on the ground at the end of their [turn](../../../../../rule/combat/turn.md) or fall [prone](../../../../../condition/prone.md).
      feature_type: trait
      icon: ⭐️
      name: Wilted Wings
      type: feature
    - effects:
        - effect: Each creature [adjacent](../../../../../rule/combat/adjacent.md) to the blightling can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
flavor: This cherubin creature is bloated and warped by demonic energy. The lights from their myriad eyes have all but gone out, now resembling pustules across their body.
free_strike: 7
immunities: []
intuition: 4
keywords:
    - Abyssal
    - Demon
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/faded-blightling
    source: mcdm.summoner.v1
might: 0
movement: Fly
name: Faded Blightling
organization: Minion
presence: 3
reason: -1
role: Support
size: 1L
speed: 5
stability: 0
stamina: 17 | 17
type: statblock
weaknesses:
    - Holy 1
```
