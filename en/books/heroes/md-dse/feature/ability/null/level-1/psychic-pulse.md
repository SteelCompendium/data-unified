---
action_type: Maneuver
class: "null"
cost: 3 Discipline
cost_amount: "3"
cost_resource: Discipline
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: Each target takes psychic damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score. Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the size of your [Null Field](scc.v1:mcdm.heroes.v1/feature.null.level-1/null-field) ability increases by 1. At the end of your current [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each enemy in the area of your [Null Field](scc.v1:mcdm.heroes.v1/feature.null.level-1/null-field) ability takes psychic damage equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
feature_type: ability
file_basename: psychic-pulse
file_dpath: feature/ability/null/level-1
flavor: A burst of psionic energy interferes with your enemy's synapses.
item_id: psychic-pulse
item_name: Psychic Pulse
keywords:
    - Area
    - Psionic
level: "1"
name: Psychic Pulse
scc: mcdm.heroes.v1/feature.ability.null.level-1/psychic-pulse
source: mcdm.heroes.v1
target: Each enemy in the area
type: ability
---

```ds-feature
cost: 3 Discipline
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each target takes psychic damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score. Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the size of your [Null Field](scc.v1:mcdm.heroes.v1/feature.null.level-1/null-field) ability increases by 1. At the end of your current [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each enemy in the area of your [Null Field](scc.v1:mcdm.heroes.v1/feature.null.level-1/null-field) ability takes psychic damage equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
feature_type: ability
flavor: A burst of psionic energy interferes with your enemy's synapses.
keywords:
    - Area
    - Psionic
metadata:
    action_type: Maneuver
    class: "null"
    cost: 3 Discipline
    distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: Each target takes psychic damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score. Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), the size of your [Null Field](scc.v1:mcdm.heroes.v1/feature.null.level-1/null-field) ability increases by 1. At the end of your current [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each enemy in the area of your [Null Field](scc.v1:mcdm.heroes.v1/feature.null.level-1/null-field) ability takes psychic damage equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.
    flavor: A burst of psionic energy interferes with your enemy's synapses.
    keywords:
        - Area
        - Psionic
    level: "1"
    name: Psychic Pulse
    scc: mcdm.heroes.v1/feature.ability.null.level-1/psychic-pulse
    target: Each enemy in the area
    type: ability
name: Psychic Pulse
target: Each enemy in the area
type: feature
usage: Maneuver
```
