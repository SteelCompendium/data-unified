---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You or one ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: drain
file_dpath: feature/ability/conduit/level-1
flavor: You drain the energy from your target to revitalize yourself or an ally.
item_id: drain
item_name: Drain
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Drain
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/drain
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + I corruption damage
tier2: 5 + I corruption damage
tier3: 7 + I corruption damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You or one ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 2 + I corruption damage
      tier2: 5 + I corruption damage
      tier3: 7 + I corruption damage
feature_type: ability
flavor: You drain the energy from your target to revitalize yourself or an ally.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You or one ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: You drain the energy from your target to revitalize yourself or an ally.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Drain
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/drain
    subtype: signature
    target: One creature
    tier1: 2 + I corruption damage
    tier2: 5 + I corruption damage
    tier3: 7 + I corruption damage
    type: ability
name: Drain
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
