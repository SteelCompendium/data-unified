---
agility: 1
cost: 1 essence per minion summoned
cost_amount: "1"
cost_resource: essence per minion summoned
file_basename: pixie-bellringer
file_dpath: monster/minion/summoner/fey/statblock
flavor: The bellringers are glowing pixies that jingle as they fly. Historically, these pixies worked alongside bowman to ensure their arrows struck true.
free_strike: 1
immunities: []
intuition: 0
item_id: pixie-bellringer
item_name: Pixie Bellringer
keywords:
    - Fey
might: -3
movement: Fly, hover
name: Pixie Bellringer
organization: Minion
presence: 2
reason: 0
role: Support
scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/pixie-bellringer
size: 1T
source: mcdm.summoner.v1
speed: 5
stability: 0
stamina: "2"
type: statblock
weaknesses: []
---

```ds-sb
agility: 1
cost: 1 essence per minion summoned
ev: ""
features:
    - effects:
        - effect: The bellringer's [free strikes](../../../../../feature/common/main-actions/free-strike.md) grant an [edge](../../../../../rule/dice/edge.md) to the next [strike](../../../../../rule/combat/strike.md) made against the target, or a double [edge](../../../../../rule/dice/edge.md) if two or more bellringers strike the same target.
      feature_type: trait
      icon: ⭐️
      name: Ringing Strike
      type: feature
    - effects:
        - effect: Each ally within 1 square of a bellringer has a +1 to [saving throws](../../../../../rule/general/saving-throw.md). Each enemy within 1 square of a bellringer has a -1 to [saving throws](../../../../../rule/general/saving-throw.md).
      feature_type: trait
      icon: ⭐️
      name: Fairy Chime
      type: feature
    - effects:
        - effect: The bellringer has [cover](../../../../../rule/combat/cover.md) while occupying a larger creature's space.
      feature_type: trait
      icon: ⭐️
      name: Minuscule
      type: feature
flavor: The bellringers are glowing pixies that jingle as they fly. Historically, these pixies worked alongside bowman to ensure their arrows struck true.
free_strike: 1
immunities: []
intuition: 0
keywords:
    - Fey
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/pixie-bellringer
    source: mcdm.summoner.v1
might: -3
movement: Fly, hover
name: Pixie Bellringer
organization: Minion
presence: 2
reason: 0
role: Support
size: 1T
speed: 5
stability: 0
stamina: "2"
type: statblock
weaknesses: []
```
