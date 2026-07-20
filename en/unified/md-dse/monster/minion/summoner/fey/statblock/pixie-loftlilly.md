---
agility: 1
cost: 3 essence for two minions
cost_amount: "3"
cost_resource: essence for two minions
file_basename: pixie-loftlilly
file_dpath: monster/minion/summoner/fey/statblock
flavor: Loftlillies lazily drift through the air in flower cups. They sip on toxic nectar to emit a powerful haze from their skin.
free_strike: 4
free_strike_damage_type: Poison
immunities:
    - Poison R
intuition: 0
item_id: pixie-loftlilly
item_name: Pixie Loftlilly
keywords:
    - Fey
might: -2
movement: Fly, hover
name: Pixie Loftlilly
organization: Minion
presence: 2
reason: 0
role: Controller
scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/pixie-loftlilly
size: 1T
source: mcdm.summoner.v1
speed: 5
stability: 0
stamina: 5 | 5
type: statblock
weaknesses: []
---

```ds-sb
agility: 1
cost: 3 essence for two minions
ev: ""
features:
    - effects:
        - effect: The area within 1 square of the loftlilly causes each enemy and object with a size equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) or smaller to float 1 square off the ground until they leave the area. A floating enemy that can't [fly](scc.v1:mcdm.heroes.v1/movement/fly) is unable to [shift](scc.v1:mcdm.heroes.v1/movement/shifting), moves 2 additional squares from [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement), and has a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike).
      feature_type: trait
      icon: ⭐️
      name: Floating Toxins
      type: feature
    - effects:
        - effect: The loftlilly has [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover) while occupying a larger creature's space.
      feature_type: trait
      icon: ⭐️
      name: Minuscule
      type: feature
flavor: Loftlillies lazily drift through the air in flower cups. They sip on toxic nectar to emit a powerful haze from their skin.
free_strike: 4
immunities:
    - Poison R
intuition: 0
keywords:
    - Fey
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/pixie-loftlilly
    source: mcdm.summoner.v1
might: -2
movement: Fly, hover
name: Pixie Loftlilly
organization: Minion
presence: 2
reason: 0
role: Controller
size: 1T
speed: 5
stability: 0
stamina: 5 | 5
type: statblock
weaknesses: []
```
