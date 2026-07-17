---
agility: -1
cost: 1 essence per minion summoned
cost_amount: "1"
cost_resource: essence per minion summoned
file_basename: nixie-soakreed
file_dpath: monster/minion/summoner/fey/statblock
flavor: These nixies are especially tiny. Their hair grows longer than their bodies and curls into reeds. The water soakreeds swim in tends to turn thick and cling to surfaces.
free_strike: 1
immunities: []
intuition: 2
item_id: nixie-soakreed
item_name: Nixie Soakreed
keywords:
    - Fey
might: -2
movement: Swim
name: Nixie Soakreed
organization: Minion
presence: 1
reason: 0
role: Controller
scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/nixie-soakreed
size: 1T
source: mcdm.summoner.v1
speed: 5
stability: 0
stamina: "1"
type: statblock
weaknesses: []
---

```ds-sb
agility: -1
cost: 1 essence per minion summoned
ev: ""
features:
    - effects:
        - effect: Once per turn during their move action, each nixie under your control can [teleport](../../../../../movement/teleport.md) to a body of water within 5. The soakreed can't [teleport](../../../../../movement/teleport.md) into water created by their own soaking bog.
      feature_type: trait
      icon: ⭐️
      name: Water Weird
      type: feature
    - effects:
        - effect: The area within 1 square of the soakreed is filled with swampy water. An enemy that starts their turn in the area is A < WEAK [slowed](../../../../../condition/slowed.md) ([EoT](../../../../../rule/combat/end-of-turn.md)). The [potency](../../../../../rule/character/potency.md) increases by 1 for each additional soaking bog the target occupies (maximum +2).
      feature_type: trait
      icon: ⭐️
      name: Soaking Bog
      type: feature
    - effects:
        - effect: The soakreed has [cover](../../../../../rule/combat/cover.md) while occupying a larger creature's space.
      feature_type: trait
      icon: ⭐️
      name: Minuscule
      type: feature
flavor: These nixies are especially tiny. Their hair grows longer than their bodies and curls into reeds. The water soakreeds swim in tends to turn thick and cling to surfaces.
free_strike: 1
immunities: []
intuition: 2
keywords:
    - Fey
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.fey.statblock/nixie-soakreed
    source: mcdm.summoner.v1
might: -2
movement: Swim
name: Nixie Soakreed
organization: Minion
presence: 1
reason: 0
role: Controller
size: 1T
speed: 5
stability: 0
stamina: "1"
type: statblock
weaknesses: []
```
