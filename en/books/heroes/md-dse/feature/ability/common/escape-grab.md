---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
distance: Self
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: No effect.
      tier2: You can escape the grab, but if you do, a creature who has you [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against you before you are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
      tier3: You are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
    - effect: You take a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on this maneuver if your [size](scc.v1:mcdm.heroes.v1/rule.character/size) is smaller than the size of the creature, object, or effect that has you [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
      name: Effect
feature_type: ability
file_basename: escape-grab
file_dpath: feature/ability/common
item_id: escape-grab
item_name: Escape Grab
keywords: []
name: Escape Grab
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.common/escape-grab
source: mcdm.heroes.v1
target: Self
tier1: No effect.
tier2: You can escape the grab, but if you do, a creature who has you [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against you before you are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
tier3: You are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
type: ability
---

```ds-feature
distance: Self
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: No effect.
      tier2: You can escape the grab, but if you do, a creature who has you [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against you before you are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
      tier3: You are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
    - effect: You take a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on this maneuver if your [size](scc.v1:mcdm.heroes.v1/rule.character/size) is smaller than the size of the creature, object, or effect that has you [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
      name: Effect
feature_type: ability
keywords: []
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    distance: Self
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: No effect.
          tier2: You can escape the grab, but if you do, a creature who has you [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against you before you are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
          tier3: You are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
        - effect: You take a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on this maneuver if your [size](scc.v1:mcdm.heroes.v1/rule.character/size) is smaller than the size of the creature, object, or effect that has you [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
          name: Effect
    keywords: []
    name: Escape Grab
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.common/escape-grab
    target: Self
    tier1: No effect.
    tier2: You can escape the grab, but if you do, a creature who has you [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) can make a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against you before you are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
    tier3: You are no longer [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed).
    type: ability
name: Escape Grab
target: Self
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
