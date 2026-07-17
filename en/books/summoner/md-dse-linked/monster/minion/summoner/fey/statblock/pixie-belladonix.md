---
agility: 2
cost: 7 essence for two minions
cost_amount: "7"
cost_resource: essence for two minions
file_basename: pixie-belladonix
file_dpath: monster/minion/summoner/fey/statblock
flavor: The belladonix are found among the elite guard of fey monarchs and carry themselves like royalty. Their moth-like wings ooze with vibrant colors and are barbed; the poison within threatening to completely shift the reality of their victims.
free_strike: 8
immunities:
    - Poison R
intuition: 0
item_id: pixie-belladonix
item_name: Pixie Belladonix
keywords:
    - Fey
might: -2
movement: Fly, hover
name: Pixie Belladonix
organization: Minion
presence: 4
reason: 4
role: Artillery
scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/pixie-belladonix
size: 1T
source: mcdm.summoner.v1
speed: 6
stability: 0
stamina: 16 | 16
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 7 essence for two minions
ev: ""
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: 2d10 + R
          tier1: 8 poison [damage](../../../../../rule/damage/damage.md); M < WEAK [restrained](../../../../../condition/restrained.md) (save ends)
          tier2: 12 poison [damage](../../../../../rule/damage/damage.md); M < AVERAGE [restrained](../../../../../condition/restrained.md) (save ends)
          tier3: 17 poison [damage](../../../../../rule/damage/damage.md); M < STRONG [restrained](../../../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: A Thorn, Woe to the Pricked
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The belladonix has [cover](../../../../../rule/combat/cover.md) while occupying a larger creature's space.
      feature_type: trait
      icon: ⭐️
      name: Minuscule
      type: feature
flavor: The belladonix are found among the elite guard of fey monarchs and carry themselves like royalty. Their moth-like wings ooze with vibrant colors and are barbed; the poison within threatening to completely shift the reality of their victims.
free_strike: 8
immunities:
    - Poison R
intuition: 0
keywords:
    - Fey
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/pixie-belladonix
    source: mcdm.summoner.v1
might: -2
movement: Fly, hover
name: Pixie Belladonix
organization: Minion
presence: 4
reason: 4
role: Artillery
size: 1T
speed: 6
stability: 0
stamina: 16 | 16
type: statblock
weaknesses: []
```
