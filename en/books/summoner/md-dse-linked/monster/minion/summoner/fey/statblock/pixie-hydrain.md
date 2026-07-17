---
agility: 0
cost: 3 essence for two minions
cost_amount: "3"
cost_resource: essence for two minions
file_basename: pixie-hydrain
file_dpath: monster/minion/summoner/fey/statblock
flavor: This pixie flies on a delicate array of vibrant flower petals for wings. The color drains from their wings as they call forth acid rain showers.
free_strike: 5
immunities:
    - Acid R
intuition: 0
item_id: pixie-hydrain
item_name: Pixie Hydrain
keywords:
    - Fey
might: -3
movement: Fly, hover
name: Pixie Hydrain
organization: Minion
presence: 2
reason: 1
role: Artillery
scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/pixie-hydrain
size: 1T
source: mcdm.summoner.v1
speed: 5
stability: 0
stamina: 5 | 5
type: statblock
weaknesses: []
---

```ds-sb
agility: 0
cost: 3 essence for two minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: 2d10 + R
          tier1: 5 acid damage; M < WEAK [weakened](../../../../../condition/weakened.md) ([EoT](../../../../../rule/combat/end-of-turn.md))
          tier2: 7 acid damage; M < AVERAGE [weakened](../../../../../condition/weakened.md) ([EoT](../../../../../rule/combat/end-of-turn.md))
          tier3: 9 acid damage; M < STRONG [weakened](../../../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Burning/Healing Rain
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The hydrain has [cover](../../../../../rule/combat/cover.md) while occupying a larger creature's space.
      feature_type: trait
      icon: ⭐️
      name: Minuscule
      type: feature
flavor: This pixie flies on a delicate array of vibrant flower petals for wings. The color drains from their wings as they call forth acid rain showers.
free_strike: 5
immunities:
    - Acid R
intuition: 0
keywords:
    - Fey
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/pixie-hydrain
    source: mcdm.summoner.v1
might: -3
movement: Fly, hover
name: Pixie Hydrain
organization: Minion
presence: 2
reason: 1
role: Artillery
size: 1T
speed: 5
stability: 0
stamina: 5 | 5
type: statblock
weaknesses: []
```
