---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
cost: 11 Essence
cost_amount: "11"
cost_resource: Essence
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: '7 fire damage; the Director loses 2 Malice (see *Draw Steel: Monsters*)'
      tier2: 10 fire damage; the Director loses 3 Malice
      tier3: 15 fire damage; the Director loses 4 Malice
    - effect: The Director's Malice can become negative as a result of this ability.
      name: Effect
feature_type: ability
file_basename: muse-of-fire
file_dpath: feature/ability/elementalist/level-8
flavor: The fire burns hot enough to sear the face of any god watching.
item_id: muse-of-fire
item_name: Muse of Fire
keywords:
    - Area
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "8"
name: Muse of Fire
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-8/muse-of-fire
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: '7 fire damage; the Director loses 2 Malice (see *Draw Steel: Monsters*)'
tier2: 10 fire damage; the Director loses 3 Malice
tier3: 15 fire damage; the Director loses 4 Malice
type: ability
---

```ds-feature
cost: 11 Essence
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: '7 fire damage; the Director loses 2 Malice (see *Draw Steel: Monsters*)'
      tier2: 10 fire damage; the Director loses 3 Malice
      tier3: 15 fire damage; the Director loses 4 Malice
    - effect: The Director's Malice can become negative as a result of this ability.
      name: Effect
feature_type: ability
flavor: The fire burns hot enough to sear the face of any god watching.
keywords:
    - Area
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    cost: 11 Essence
    distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effects:
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: '7 fire damage; the Director loses 2 Malice (see *Draw Steel: Monsters*)'
          tier2: 10 fire damage; the Director loses 3 Malice
          tier3: 15 fire damage; the Director loses 4 Malice
        - effect: The Director's Malice can become negative as a result of this ability.
          name: Effect
    flavor: The fire burns hot enough to sear the face of any god watching.
    keywords:
        - Area
        - Fire
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "8"
    name: Muse of Fire
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-8/muse-of-fire
    target: Each enemy in the area
    tier1: '7 fire damage; the Director loses 2 Malice (see *Draw Steel: Monsters*)'
    tier2: 10 fire damage; the Director loses 3 Malice
    tier3: 15 fire damage; the Director loses 4 Malice
    type: ability
name: Muse of Fire
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
