---
action_type: Main action
class: elementalist
cost: 9 Essence
cost_amount: "9"
cost_resource: Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: If the target is [teleport](scc.v1:mcdm.heroes.v1/movement/teleport)ed to a space where they would fall, they immediately do so, treating the fall as if their [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score were 0. The target takes fire damage from the fall, and each enemy within 3 squares of where they land takes the same amount of fire damage. The ground within 3 squares of where the target lands is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
feature_type: ability
file_basename: meteor
file_dpath: feature/ability/elementalist/level-6
flavor: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target into the air and let the ground and the elemental force of fire do the rest.
item_id: meteor
item_name: Meteor
keywords:
    - Earth
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Void
level: "6"
name: Meteor
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-6/meteor
source: mcdm.heroes.v1
target: One creature or object
tier1: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target up to 4 squares.
tier2: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target up to 6 squares.
tier3: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target up to 8 squares.
type: ability
---

```ds-feature
cost: 9 Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: If the target is [teleport](scc.v1:mcdm.heroes.v1/movement/teleport)ed to a space where they would fall, they immediately do so, treating the fall as if their [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score were 0. The target takes fire damage from the fall, and each enemy within 3 squares of where they land takes the same amount of fire damage. The ground within 3 squares of where the target lands is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target up to 4 squares.
      tier2: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target up to 6 squares.
      tier3: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target up to 8 squares.
feature_type: ability
flavor: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target into the air and let the ground and the elemental force of fire do the rest.
keywords:
    - Earth
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Void
metadata:
    action_type: Main action
    class: elementalist
    cost: 9 Essence
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: If the target is [teleport](scc.v1:mcdm.heroes.v1/movement/teleport)ed to a space where they would fall, they immediately do so, treating the fall as if their [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score were 0. The target takes fire damage from the fall, and each enemy within 3 squares of where they land takes the same amount of fire damage. The ground within 3 squares of where the target lands is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).
    flavor: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target into the air and let the ground and the elemental force of fire do the rest.
    keywords:
        - Earth
        - Fire
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Void
    level: "6"
    name: Meteor
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-6/meteor
    target: One creature or object
    tier1: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target up to 4 squares.
    tier2: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target up to 6 squares.
    tier3: You [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) the target up to 8 squares.
    type: ability
name: Meteor
target: One creature or object
type: feature
usage: Main action
```
