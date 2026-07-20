---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 3'
effect: This ability can't obtain better than a tier 2 outcome unless the target is at maximum [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). If you obtain a tier 3 outcome with a natural 17 or higher, you gain 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) that you can use immediately.
feature_type: ability
file_basename: expert-fencer
file_dpath: feature/ability/troubadour/level-9
flavor: If you can land the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the crowd goes wild.
item_id: expert-fencer
item_name: Expert Fencer
keywords:
    - Charge
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: Expert Fencer
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/expert-fencer
source: mcdm.heroes.v1
subclass: duelist
target: One creature or object
tier1: 15 + A damage
tier2: 21 + A damage
tier3: 28 + A damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
type: ability
---

```ds-feature
cost: 11 Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 3'
effects:
    - effect: This ability can't obtain better than a tier 2 outcome unless the target is at maximum [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). If you obtain a tier 3 outcome with a natural 17 or higher, you gain 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) that you can use immediately.
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 15 + A damage
      tier2: 21 + A damage
      tier3: 28 + A damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
feature_type: ability
flavor: If you can land the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the crowd goes wild.
keywords:
    - Charge
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    cost: 11 Drama
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 3'
    effect: This ability can't obtain better than a tier 2 outcome unless the target is at maximum [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). If you obtain a tier 3 outcome with a natural 17 or higher, you gain 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) that you can use immediately.
    flavor: If you can land the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the crowd goes wild.
    keywords:
        - Charge
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "9"
    name: Expert Fencer
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/expert-fencer
    subclass: duelist
    target: One creature or object
    tier1: 15 + A damage
    tier2: 21 + A damage
    tier3: 28 + A damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    type: ability
name: Expert Fencer
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
