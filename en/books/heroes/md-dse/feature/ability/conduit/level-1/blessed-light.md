---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: One ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a number of [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) equal to the [tier outcome](scc.v1:mcdm.heroes.v1/rule.dice/tier-outcome) of your [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
file_basename: blessed-light
file_dpath: feature/ability/conduit/level-1
flavor: Burning radiance falls upon your foe, transferring some of their energy to a nearby ally.
item_id: blessed-light
item_name: Blessed Light
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Blessed Light
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/blessed-light
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + I holy damage
tier2: 5 + I holy damage
tier3: 8 + I holy damage
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: One ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a number of [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) equal to the [tier outcome](scc.v1:mcdm.heroes.v1/rule.dice/tier-outcome) of your [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 + I holy damage
      tier2: 5 + I holy damage
      tier3: 8 + I holy damage
feature_type: ability
flavor: Burning radiance falls upon your foe, transferring some of their energy to a nearby ally.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: One ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a number of [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) equal to the [tier outcome](scc.v1:mcdm.heroes.v1/rule.dice/tier-outcome) of your [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: Burning radiance falls upon your foe, transferring some of their energy to a nearby ally.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Blessed Light
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/blessed-light
    subtype: signature
    target: One creature or object
    tier1: 3 + I holy damage
    tier2: 5 + I holy damage
    tier3: 8 + I holy damage
    type: ability
name: Blessed Light
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
