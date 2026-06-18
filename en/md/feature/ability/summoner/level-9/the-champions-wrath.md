---
action_type: Main action
class: summoner
distance: 4 burst
effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
flavor: Your champion appears and goes into a rampage, clearing the way for your minions to march forth.
keywords:
    - Area
    - Champion
    - Magic
    - Weapon
level: "9"
name: The Champion's Wrath
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.summoner.v1/feature.ability.summoner.level-9/the-champions-wrath
target: Each enemy in the area
tier1: 6 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4 M < WEAK push is vertical
tier2: 10 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 M < AVERAGE push is vertical
tier3: 14 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6 M < STRONG push is vertical
type: ability
---

*Your champion appears and goes into a rampage, clearing the way for your minions to march forth.*

| **Area, Champion, Magic, Weapon** | **Main action** |
|-----------------------------------|----------------:|
| **📏 4 burst** | **🎯 Each enemy in the area** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason):**

- **≤11:** 6 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4 M < WEAK push is vertical
- **12-16:** 10 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 M < AVERAGE push is vertical
- **17+:** 14 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6 M < STRONG push is vertical

**Effect:** You can use this ability as if in the space of one of your minions within your Summoner's Range.

You can change the [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) to be a type that your champion deals on their stat block (see [Portfolio Champion](scc.v1:mcdm.summoner.v1/feature.summoner.level-8/portfolio-champion)). For each enemy reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) by this ability, an ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can move up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed).
