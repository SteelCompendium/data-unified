---
action_type: Main action
class: talent
cost: 7 Clarity
cost_amount: "7"
cost_resource: Clarity
distance: Self; see below
effect: You create three [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1T orbs that orbit your body. Each orb gives you a cumulative [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) 1. Each time you take damage, you lose 1 orb.
feature_type: ability
file_basename: force-orbs
file_dpath: feature/ability/talent/level-3
flavor: Spheres of solid psionic energy float around you.
item_id: force-orbs
item_name: Force Orbs
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telekinesis
level: "3"
name: Force Orbs
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-3/force-orbs
source: mcdm.heroes.v1
target: Self
tier1: 2 damage
tier2: 3 damage
tier3: 5 damage
type: ability
---

```ds-feature
cost: 7 Clarity
distance: Self; see below
effects:
    - effect: You create three [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1T orbs that orbit your body. Each orb gives you a cumulative [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) 1. Each time you take damage, you lose 1 orb.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 damage
      tier2: 3 damage
      tier3: 5 damage
feature_type: ability
flavor: Spheres of solid psionic energy float around you.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telekinesis
metadata:
    action_type: Main action
    class: talent
    cost: 7 Clarity
    distance: Self; see below
    effect: You create three [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1T orbs that orbit your body. Each orb gives you a cumulative [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) 1. Each time you take damage, you lose 1 orb.
    flavor: Spheres of solid psionic energy float around you.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Telekinesis
    level: "3"
    name: Force Orbs
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-3/force-orbs
    target: Self
    tier1: 2 damage
    tier2: 3 damage
    tier3: 5 damage
    type: ability
name: Force Orbs
target: Self
type: feature
usage: Main action
```
