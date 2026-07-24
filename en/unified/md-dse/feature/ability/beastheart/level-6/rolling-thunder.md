---
action_type: Main action
class: beastheart
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Self
effects:
    - effect: Your companion [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and makes one power roll that targets each enemy they come adjacent to during the shift. If your companion targets only one enemy with this ability, the power roll gains an edge.
      name: Effect
    - roll: Power Roll + Might
      tier1: 9 sonic damage; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 13 sonic damage; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 18 sonic damage; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    - cost: Spend 2 Ferocity
      effect: You can move up to your speed. The power roll also targets each enemy you come adjacent to during the move.
feature_type: ability
file_basename: rolling-thunder
file_dpath: feature/ability/beastheart/level-6
flavor: The rumble of your companion's dash is a rolling thunderclap, their impact an earthquake.
item_id: rolling-thunder
item_name: Rolling Thunder
keywords:
    - Companion
    - Magic
    - Melee
    - Strike
level: "6"
name: Rolling Thunder
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/rolling-thunder
source: mcdm.beastheart.v1
subclass: punisher
target: Self
tier1: 9 sonic damage; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier2: 13 sonic damage; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier3: 18 sonic damage; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Self
effects:
    - effect: Your companion [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and makes one power roll that targets each enemy they come adjacent to during the shift. If your companion targets only one enemy with this ability, the power roll gains an edge.
      name: Effect
    - roll: Power Roll + Might
      tier1: 9 sonic damage; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 13 sonic damage; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 18 sonic damage; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    - cost: Spend 2 Ferocity
      effect: You can move up to your speed. The power roll also targets each enemy you come adjacent to during the move.
feature_type: ability
flavor: The rumble of your companion's dash is a rolling thunderclap, their impact an earthquake.
keywords:
    - Companion
    - Magic
    - Melee
    - Strike
metadata:
    action_type: Main action
    class: beastheart
    cost: 9 Ferocity
    distance: Self
    effects:
        - effect: Your companion [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed and makes one power roll that targets each enemy they come adjacent to during the shift. If your companion targets only one enemy with this ability, the power roll gains an edge.
          name: Effect
        - roll: Power Roll + Might
          tier1: 9 sonic damage; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier2: 13 sonic damage; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier3: 18 sonic damage; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
        - cost: Spend 2 Ferocity
          effect: You can move up to your speed. The power roll also targets each enemy you come adjacent to during the move.
    flavor: The rumble of your companion's dash is a rolling thunderclap, their impact an earthquake.
    keywords:
        - Companion
        - Magic
        - Melee
        - Strike
    level: "6"
    name: Rolling Thunder
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/rolling-thunder
    subclass: punisher
    target: Self
    tier1: 9 sonic damage; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier2: 13 sonic damage; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier3: 18 sonic damage; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: Rolling Thunder
target: Self
type: feature
usage: Main action
```
