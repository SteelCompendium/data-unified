---
agility: 0
cost: 1 essence per minion summoned
cost_amount: "1"
cost_resource: essence per minion summoned
file_basename: sprite-dandeknight
file_dpath: monster/minion/summoner/fey/statblock
flavor: Dandeknights are sprite warriors whose dragonfly wingbeats emit a tonal drone. They're usually clad in tassels that shift color as they swing their weapons.
free_strike: 1
immunities: []
intuition: -1
item_id: sprite-dandeknight
item_name: Sprite Dandeknight
keywords:
    - Fey
might: 2
movement: Fly
name: Sprite Dandeknight
organization: Minion
presence: -1
reason: -1
role: Harrier
scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/sprite-dandeknight
size: 1T
source: mcdm.summoner.v1
speed: 6
stability: 0
stamina: "2"
type: statblock
weaknesses: []
---

```ds-sb
agility: 0
cost: 1 essence per minion summoned
ev: ""
features:
    - effects:
        - effect: 'When the dandeknight strikes, you can choose one of the following damage types: acid, cold, corruption, fire, lightning, poison, or sonic. The strike deals that damage.'
      feature_type: trait
      icon: ⭐️
      name: Magic Strike
      type: feature
    - effects:
        - effect: When the dandeknight makes a [free strike](../../../../../feature/common/main-actions/free-strike.md), they can make two [free strikes](../../../../../feature/common/main-actions/free-strike.md) instead. The damage is added together and treated as a single [strike](../../../../../rule/combat/strike.md) if both strikes hit the same target.
      feature_type: trait
      icon: ⭐️
      name: Staccato Swings
      type: feature
    - effects:
        - effect: The dandeknight has [cover](../../../../../rule/combat/cover.md) while occupying a larger creature's space.
      feature_type: trait
      icon: ⭐️
      name: Minuscule
      type: feature
flavor: Dandeknights are sprite warriors whose dragonfly wingbeats emit a tonal drone. They're usually clad in tassels that shift color as they swing their weapons.
free_strike: 1
immunities: []
intuition: -1
keywords:
    - Fey
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/sprite-dandeknight
    source: mcdm.summoner.v1
might: 2
movement: Fly
name: Sprite Dandeknight
organization: Minion
presence: -1
reason: -1
role: Harrier
size: 1T
speed: 6
stability: 0
stamina: "2"
type: statblock
weaknesses: []
```
