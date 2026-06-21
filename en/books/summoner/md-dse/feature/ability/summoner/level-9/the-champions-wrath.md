---
action_type: Main action
class: summoner
distance: 4 burst
effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
feature_source: summoner
feature_type: ability
file_basename: the-champions-wrath
file_dpath: feature/ability/summoner/level-9
flavor: Your champion appears and goes into a rampage, clearing the way for your minions to march forth.
item_id: the-champions-wrath
item_name: The Champion's Wrath
keywords:
    - Area
    - Champion
    - Magic
    - Weapon
level: "9"
name: The Champion's Wrath
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.summoner.v1/feature.ability.summoner.level-9/the-champions-wrath
source: mcdm.summoner.v1
target: Each enemy in the area
tier1: 6 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4 M < WEAK push is vertical
tier2: 10 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 M < AVERAGE push is vertical
tier3: 14 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6 M < STRONG push is vertical
type: ability
---

```ds-feature
distance: 4 burst
effects:
    - effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 6 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4 M < WEAK push is vertical
      tier2: 10 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5 M < AVERAGE push is vertical
      tier3: 14 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6 M < STRONG push is vertical
feature_type: ability
flavor: Your champion appears and goes into a rampage, clearing the way for your minions to march forth.
keywords:
    - Area
    - Champion
    - Magic
    - Weapon
metadata:
    action_type: Main action
    class: summoner
    distance: 4 burst
    effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
    feature_source: summoner
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
name: The Champion's Wrath
target: Each enemy in the area
type: feature
usage: Main action
```
