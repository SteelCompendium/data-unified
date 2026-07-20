---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 7 Piety
cost_amount: "7"
cost_resource: Piety
distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: Each ally in the area can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: words-of-wrath-and-grace
file_dpath: feature/ability/conduit/level-3
flavor: Your [saint](scc.v1:mcdm.heroes.v1/rule.world/saint) grants your enemies a vision of pain and fills your allies with healing energy.
item_id: words-of-wrath-and-grace
item_name: Words of Wrath and Grace
keywords:
    - Area
    - Magic
level: "3"
name: Words of Wrath and Grace
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-3/words-of-wrath-and-grace
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 2 holy damage
tier2: 5 holy damage
tier3: 7 holy damage
type: ability
---

```ds-feature
cost: 7 Piety
distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each ally in the area can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 2 holy damage
      tier2: 5 holy damage
      tier3: 7 holy damage
feature_type: ability
flavor: Your [saint](scc.v1:mcdm.heroes.v1/rule.world/saint) grants your enemies a vision of pain and fills your allies with healing energy.
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 7 Piety
    distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: Each ally in the area can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: Your [saint](scc.v1:mcdm.heroes.v1/rule.world/saint) grants your enemies a vision of pain and fills your allies with healing energy.
    keywords:
        - Area
        - Magic
    level: "3"
    name: Words of Wrath and Grace
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-3/words-of-wrath-and-grace
    target: Each enemy in the area
    tier1: 2 holy damage
    tier2: 5 holy damage
    tier3: 7 holy damage
    type: ability
name: Words of Wrath and Grace
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
