---
action_type: Main action
class: beastheart
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: 2 burst
effect: Your companion can forgo dealing damage to targets of your choice.
feature_type: ability
file_basename: juggernaut
file_dpath: feature/ability/beastheart/level-9
flavor: Your companion plows through the front lines, tossing enemies—and allies—this way and that.
item_id: juggernaut
item_name: Juggernaut
keywords:
    - Area
    - Charge
    - Companion
level: "9"
name: Juggernaut
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/juggernaut
source: mcdm.beastheart.v1
subclass: punisher
target: Each creature
tier1: 9 damage; vertical slide 2; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier2: 13 damage; vertical slide 4; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier3: 18 damage; vertical slide 6; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: 2 burst
effects:
    - effect: Your companion can forgo dealing damage to targets of your choice.
    - roll: Power Roll + Intuition
      tier1: 9 damage; vertical slide 2; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 13 damage; vertical slide 4; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 18 damage; vertical slide 6; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
feature_type: ability
flavor: Your companion plows through the front lines, tossing enemies—and allies—this way and that.
keywords:
    - Area
    - Charge
    - Companion
metadata:
    action_type: Main action
    class: beastheart
    cost: 11 Ferocity
    distance: 2 burst
    effect: Your companion can forgo dealing damage to targets of your choice.
    flavor: Your companion plows through the front lines, tossing enemies—and allies—this way and that.
    keywords:
        - Area
        - Charge
        - Companion
    level: "9"
    name: Juggernaut
    power_roll_characteristic: Intuition
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/juggernaut
    subclass: punisher
    target: Each creature
    tier1: 9 damage; vertical slide 2; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier2: 13 damage; vertical slide 4; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier3: 18 damage; vertical slide 6; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: Juggernaut
target: Each creature
type: feature
usage: Main action
```
