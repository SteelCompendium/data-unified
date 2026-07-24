---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
cost: 11 Essence
cost_amount: "11"
cost_resource: Essence
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 6 damage
      tier2: 9 damage
      tier3: 13 damage
    - effect: At the start of your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can use a maneuver to use this ability again without spending essence.
      name: Persistent 2
feature_type: ability
file_basename: earth-rejects-you
file_dpath: feature/ability/elementalist/level-9
flavor: Everyone and everything gets blown away in an eruption of rocks and debris.
item_id: earth-rejects-you
item_name: Earth Rejects You
keywords:
    - Area
    - Earth
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "9"
name: Earth Rejects You
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-9/earth-rejects-you
source: mcdm.heroes.v1
target: Each enemy and object in the area
tier1: 6 damage
tier2: 9 damage
tier3: 13 damage
type: ability
---

```ds-feature
cost: 11 Essence
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 6 damage
      tier2: 9 damage
      tier3: 13 damage
    - effect: At the start of your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can use a maneuver to use this ability again without spending essence.
      name: Persistent 2
feature_type: ability
flavor: Everyone and everything gets blown away in an eruption of rocks and debris.
keywords:
    - Area
    - Earth
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    cost: 11 Essence
    distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effects:
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: 6 damage
          tier2: 9 damage
          tier3: 13 damage
        - effect: At the start of your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can use a maneuver to use this ability again without spending essence.
          name: Persistent 2
    flavor: Everyone and everything gets blown away in an eruption of rocks and debris.
    keywords:
        - Area
        - Earth
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "9"
    name: Earth Rejects You
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-9/earth-rejects-you
    target: Each enemy and object in the area
    tier1: 6 damage
    tier2: 9 damage
    tier3: 13 damage
    type: ability
name: Earth Rejects You
target: Each enemy and object in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
