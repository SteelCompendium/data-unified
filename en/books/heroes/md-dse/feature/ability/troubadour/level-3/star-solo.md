---
action_type: Main action
class: troubadour
cost: 7 Drama
cost_amount: "7"
cost_resource: Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: You can choose to have this ability deal sonic damage. Additionally, you can use this ability against the same target for the next 2 [combat rounds](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) without spending drama.
feature_type: ability
file_basename: star-solo
file_dpath: feature/ability/troubadour/level-3
flavor: Your performance travels and doesn't stop moving until your audience is completely rocked.
item_id: star-solo
item_name: Star Solo
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "3"
name: Star Solo
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/star-solo
source: mcdm.heroes.v1
target: One creature or object
tier1: 5 + P damage
tier2: 8 + P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier3: 11 + P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
type: ability
---

```ds-feature
cost: 7 Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You can choose to have this ability deal sonic damage. Additionally, you can use this ability against the same target for the next 2 [combat rounds](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) without spending drama.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 + P damage
      tier2: 8 + P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier3: 11 + P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
feature_type: ability
flavor: Your performance travels and doesn't stop moving until your audience is completely rocked.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 7 Drama
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: You can choose to have this ability deal sonic damage. Additionally, you can use this ability against the same target for the next 2 [combat rounds](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) without spending drama.
    flavor: Your performance travels and doesn't stop moving until your audience is completely rocked.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "3"
    name: Star Solo
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-3/star-solo
    target: One creature or object
    tier1: 5 + P damage
    tier2: 8 + P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier3: 11 + P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    type: ability
name: Star Solo
target: One creature or object
type: feature
usage: Main action
```
