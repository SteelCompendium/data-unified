---
action_type: Main action
ancestry: revenant
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The sigil disappears from the creature.
feature_type: ability
file_basename: detonate-sigil
file_dpath: feature/ability/revenant
flavor: A magic sigil you placed on a creature explodes with energy.
item_id: detonate-sigil
item_name: Detonate Sigil
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
name: Detonate Sigil
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.revenant/detonate-sigil
source: mcdm.heroes.v1
subtype: signature
target: One creature bearing your sigil
tier1: 3 + R, I, or P damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier2: 5 + R, I, or P damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
tier3: 7 + R, I, or P damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The sigil disappears from the creature.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 3 + R, I, or P damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier2: 5 + R, I, or P damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      tier3: 7 + R, I, or P damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
feature_type: ability
flavor: A magic sigil you placed on a creature explodes with energy.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    ancestry: revenant
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The sigil disappears from the creature.
    flavor: A magic sigil you placed on a creature explodes with energy.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    name: Detonate Sigil
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.revenant/detonate-sigil
    subtype: signature
    target: One creature bearing your sigil
    tier1: 3 + R, I, or P damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier2: 5 + R, I, or P damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    tier3: 7 + R, I, or P damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    type: ability
name: Detonate Sigil
target: One creature bearing your sigil
type: feature
usage: Main action
```
