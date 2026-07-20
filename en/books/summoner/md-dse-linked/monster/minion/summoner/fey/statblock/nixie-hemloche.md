---
agility: 0
cost: 5 essence for three minions
cost_amount: "5"
cost_resource: essence for three minions
file_basename: nixie-hemloche
file_dpath: monster/minion/summoner/fey/statblock
flavor: Hemloches are spotted nixies whose long, wavy hair endlessly bobs and flows into the water surrounding them. Any sailor caught in a whirlpool created by hemloches knows that their ship won't survive the encounter.
free_strike: 3
free_strike_damage_type: Lightning
immunities: []
intuition: 3
item_id: nixie-hemloche
item_name: Nixie Hemloche
keywords:
    - Fey
might: -2
movement: Swim
name: Nixie Hemloche
organization: Minion
presence: 2
reason: 1
role: Hexer
scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/nixie-hemloche
size: 1T
source: mcdm.summoner.v1
speed: 6
stability: 0
stamina: 4 | 4 | 4
type: statblock
weaknesses: []
---

```ds-sb
agility: 0
cost: 5 essence for three minions
ev: ""
features:
    - effects:
        - effect: Once per [turn](../../../../../rule/combat/turn.md) during their move action, each nixie under your control can [teleport](../../../../../movement/teleport.md) to a body of water within 6. The hemloche can't [teleport](../../../../../movement/teleport.md) into water created by their own whirling waves.
      feature_type: trait
      icon: ⭐️
      name: Water Weird
      type: feature
    - effects:
        - effect: The area within 1 square of the hemloche is filled with churning water and is considered [difficult terrain](../../../../../movement/difficult-terrain.md). At the end of the hemloche's [turn](../../../../../rule/combat/turn.md), the hemloche can choose to [slide](../../../../../movement/forced-movement.md) each enemy in the affected area 3 squares. An enemy that takes [damage](../../../../../rule/damage/damage.md) while being [force moved](../../../../../movement/forced-movement.md) is also M < AVERAGE knocked [prone](../../../../../condition/prone.md).
      feature_type: trait
      icon: ⭐️
      name: Whirling Waves
      type: feature
    - effects:
        - effect: The hemloche has [cover](../../../../../rule/combat/cover.md) while occupying a larger creature's space.
      feature_type: trait
      icon: ⭐️
      name: Minuscule
      type: feature
flavor: Hemloches are spotted nixies whose long, wavy hair endlessly bobs and flows into the water surrounding them. Any sailor caught in a whirlpool created by hemloches knows that their ship won't survive the encounter.
free_strike: 3
immunities: []
intuition: 3
keywords:
    - Fey
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/nixie-hemloche
    source: mcdm.summoner.v1
might: -2
movement: Swim
name: Nixie Hemloche
organization: Minion
presence: 2
reason: 1
role: Hexer
size: 1T
speed: 6
stability: 0
stamina: 4 | 4 | 4
type: statblock
weaknesses: []
```
