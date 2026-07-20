---
agility: 3
cost: 5 essence for three minions
cost_amount: "5"
cost_resource: essence for three minions
file_basename: sprite-foxglow
file_dpath: monster/minion/summoner/fey/statblock
flavor: Foxglows are masked sprites that leave behind an evanescent trail of tiny glowing orbs as they fly. They beat their wings at a frequency that completely blocks out all nearby noise.
free_strike: 4
free_strike_damage_type: Fire
immunities:
    - Fire R
intuition: 1
item_id: sprite-foxglow
item_name: Sprite Foxglow
keywords:
    - Fey
might: -1
movement: Fly
name: Sprite Foxglow
organization: Minion
presence: 2
reason: 0
role: Ambusher
scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/sprite-foxglow
size: 1T
source: mcdm.summoner.v1
speed: 8
stability: 0
stamina: 5 | 5 | 5
type: statblock
weaknesses: []
---

```ds-sb
agility: 3
cost: 5 essence for three minions
ev: ""
features:
    - effects:
        - effect: The foxglow's melee [strikes](../../../../../rule/combat/strike.md) inflict I < STRONG [dazed](../../../../../condition/dazed.md) (EoT) if they were hidden when they make the [strike](../../../../../rule/combat/strike.md).
      feature_type: trait
      icon: ⭐️
      name: Flash Strike
      type: feature
    - effects:
        - effect: The area within 2 squares of the foxglow is completely silent. Each enemy has a [bane](../../../../../rule/dice/bane.md) on [tests](../../../../../rule/test/test.md) made to search for the foxglow and allies hidden in the affected area.
      feature_type: trait
      icon: ⭐️
      name: Quiet Flight
      type: feature
    - effects:
        - effect: The foxglow has [cover](../../../../../rule/combat/cover.md) while occupying a larger creature's space.
      feature_type: trait
      icon: ⭐️
      name: Minuscule
      type: feature
flavor: Foxglows are masked sprites that leave behind an evanescent trail of tiny glowing orbs as they fly. They beat their wings at a frequency that completely blocks out all nearby noise.
free_strike: 4
immunities:
    - Fire R
intuition: 1
keywords:
    - Fey
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/sprite-foxglow
    source: mcdm.summoner.v1
might: -1
movement: Fly
name: Sprite Foxglow
organization: Minion
presence: 2
reason: 0
role: Ambusher
size: 1T
speed: 8
stability: 0
stamina: 5 | 5 | 5
type: statblock
weaknesses: []
```
