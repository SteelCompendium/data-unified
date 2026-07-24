---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 9 Wrath
cost_amount: "9"
cost_resource: Wrath
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: Each target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      tier2: Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      tier3: Each target gains 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    - effect: A target can end one effect on them that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), or a [prone target](scc.v1:mcdm.heroes.v1/condition/prone) can stand up.
      name: Effect
feature_type: ability
file_basename: orison-of-victory
file_dpath: feature/ability/censor/level-5
flavor: You channel your god's will to overcome hardship and inflict pain.
item_id: orison-of-victory
item_name: Orison of Victory
keywords:
    - Area
level: "5"
name: Orison of Victory
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.censor.level-5/orison-of-victory
source: mcdm.heroes.v1
target: Self and each ally in the area
tier1: Each target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
tier2: Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
tier3: Each target gains 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
type: ability
---

```ds-feature
cost: 9 Wrath
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: Each target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      tier2: Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      tier3: Each target gains 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    - effect: A target can end one effect on them that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), or a [prone target](scc.v1:mcdm.heroes.v1/condition/prone) can stand up.
      name: Effect
feature_type: ability
flavor: You channel your god's will to overcome hardship and inflict pain.
keywords:
    - Area
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 9 Wrath
    distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effects:
        - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
          tier1: Each target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
          tier2: Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
          tier3: Each target gains 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
        - effect: A target can end one effect on them that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), or a [prone target](scc.v1:mcdm.heroes.v1/condition/prone) can stand up.
          name: Effect
    flavor: You channel your god's will to overcome hardship and inflict pain.
    keywords:
        - Area
    level: "5"
    name: Orison of Victory
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-5/orison-of-victory
    target: Self and each ally in the area
    tier1: Each target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    tier2: Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    tier3: Each target gains 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    type: ability
name: Orison of Victory
target: Self and each ally in the area
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
