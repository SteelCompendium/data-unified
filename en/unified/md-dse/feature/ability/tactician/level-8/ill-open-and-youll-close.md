---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 11 Focus
cost_amount: "11"
cost_resource: Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M damage
      tier2: 10 + M damage
      tier3: 14 + M damage
    - effect: One ally within 10 squares of you can use a [heroic ability](scc.v1:mcdm.heroes.v1/rule.general/heroic-ability) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) without spending any of their [Heroic Resource](scc.v1:mcdm.heroes.v1/rule.resource/heroic-resource), as long as they have enough [Heroic Resource](scc.v1:mcdm.heroes.v1/rule.resource/heroic-resource) to pay for the ability. If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before the chosen ally has used their ability, the ally can pick a different target.
      name: Effect
feature_type: ability
file_basename: ill-open-and-youll-close
file_dpath: feature/ability/tactician/level-8
flavor: You create an opening for an ally.
item_id: ill-open-and-youll-close
item_name: I'll Open and You'll Close
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: I'll Open and You'll Close
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-8/ill-open-and-youll-close
source: mcdm.heroes.v1
target: One creature
tier1: 6 + M damage
tier2: 10 + M damage
tier3: 14 + M damage
type: ability
---

```ds-feature
cost: 11 Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M damage
      tier2: 10 + M damage
      tier3: 14 + M damage
    - effect: One ally within 10 squares of you can use a [heroic ability](scc.v1:mcdm.heroes.v1/rule.general/heroic-ability) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) without spending any of their [Heroic Resource](scc.v1:mcdm.heroes.v1/rule.resource/heroic-resource), as long as they have enough [Heroic Resource](scc.v1:mcdm.heroes.v1/rule.resource/heroic-resource) to pay for the ability. If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before the chosen ally has used their ability, the ally can pick a different target.
      name: Effect
feature_type: ability
flavor: You create an opening for an ally.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    cost: 11 Focus
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 6 + M damage
          tier2: 10 + M damage
          tier3: 14 + M damage
        - effect: One ally within 10 squares of you can use a [heroic ability](scc.v1:mcdm.heroes.v1/rule.general/heroic-ability) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) without spending any of their [Heroic Resource](scc.v1:mcdm.heroes.v1/rule.resource/heroic-resource), as long as they have enough [Heroic Resource](scc.v1:mcdm.heroes.v1/rule.resource/heroic-resource) to pay for the ability. If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before the chosen ally has used their ability, the ally can pick a different target.
          name: Effect
    flavor: You create an opening for an ally.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "8"
    name: I'll Open and You'll Close
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-8/ill-open-and-youll-close
    target: One creature
    tier1: 6 + M damage
    tier2: 10 + M damage
    tier3: 14 + M damage
    type: ability
name: I'll Open and You'll Close
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
