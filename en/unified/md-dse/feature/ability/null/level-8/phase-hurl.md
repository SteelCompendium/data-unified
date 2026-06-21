---
action_type: Main action
class: "null"
cost: 11 Discipline
cost_amount: "11"
cost_resource: Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: The target and each creature or object they collide with from this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) takes psychic damage equal to the total number of squares the target was force moved. While the target is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) this way, they see glimpses of creatures from other parts of the timescape.
feature_type: ability
file_basename: phase-hurl
file_dpath: feature/ability/null/level-8
flavor: You throw your foe out of phase with this manifold, causing them to harm other enemies as they return.
item_id: phase-hurl
item_name: Phase Hurl
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: Phase Hurl
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-8/phase-hurl
source: mcdm.heroes.v1
target: One creature
tier1: 9 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier2: 13 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier3: 18 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---

```ds-feature
cost: 11 Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: The target and each creature or object they collide with from this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) takes psychic damage equal to the total number of squares the target was force moved. While the target is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) this way, they see glimpses of creatures from other parts of the timescape.
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 9 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 13 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 18 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
feature_type: ability
flavor: You throw your foe out of phase with this manifold, causing them to harm other enemies as they return.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 11 Discipline
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: The target and each creature or object they collide with from this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) takes psychic damage equal to the total number of squares the target was force moved. While the target is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) this way, they see glimpses of creatures from other parts of the timescape.
    flavor: You throw your foe out of phase with this manifold, causing them to harm other enemies as they return.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "8"
    name: Phase Hurl
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-8/phase-hurl
    target: One creature
    tier1: 9 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier2: 13 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier3: 18 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 10; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    type: ability
name: Phase Hurl
target: One creature
type: feature
usage: Main action
```
