---
action_type: Main action
class: summoner
distance: 10 × 1 line within 1
feature_source: summoner
flavor: You rapidly summon and sacrifice minions in order to power a devastating blast of magic.
keywords:
    - Area
    - Magic
level: "3"
name: Essence Funnel
power_roll_characteristic: Reason
scc: mcdm.summoner.v1/feature.ability.summoner.level-3/essence-funnel
target: Each enemy and object in the area
tier1: 5 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier2: 9 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
tier3: 12 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6
type: ability
---

*You rapidly summon and sacrifice minions in order to power a devastating blast of magic.*

| **Area, Magic** | **Main action** |
|-----------------|----------------:|
| **📏 10 × 1 line within 1** | **🎯 Each enemy and object in the area** |

**Power Roll + Reason:**

- **≤11:** 5 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
- **12-16:** 9 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
- **17+:** 12 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6

**Special:** You can choose to kill any number of your [minions](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) within your Summoner's Range as a part of this ability, provided they haven't used a main action or maneuver during the [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each target takes an additional 1 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage), plus 1 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) for each [minion](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) killed this way. These [minions](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions) activate no effects upon death, and you gain no [essence](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/essence) from their deaths.
