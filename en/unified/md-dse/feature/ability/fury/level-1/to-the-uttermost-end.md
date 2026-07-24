---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 7 + M damage
      tier2: 11 + M damage
      tier3: 16 + M damage
    - cost: Spend 1+ Ferocity
      effect: While you are [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), this ability deals an extra 1d6 damage for each ferocity spent. While you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), it deals an extra 1d10 damage for each ferocity spent. In either case, you lose 1d6 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) after making this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
feature_type: ability
file_basename: to-the-uttermost-end
file_dpath: feature/ability/fury/level-1
flavor: You gut your life force to ensure a foe's demise.
item_id: to-the-uttermost-end
item_name: To the Uttermost End
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: To the Uttermost End
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/to-the-uttermost-end
source: mcdm.heroes.v1
target: One creature
tier1: 7 + M damage
tier2: 11 + M damage
tier3: 16 + M damage
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 7 + M damage
      tier2: 11 + M damage
      tier3: 16 + M damage
    - cost: Spend 1+ Ferocity
      effect: While you are [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), this ability deals an extra 1d6 damage for each ferocity spent. While you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), it deals an extra 1d10 damage for each ferocity spent. In either case, you lose 1d6 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) after making this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
feature_type: ability
flavor: You gut your life force to ensure a foe's demise.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 5 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 7 + M damage
          tier2: 11 + M damage
          tier3: 16 + M damage
        - cost: Spend 1+ Ferocity
          effect: While you are [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), this ability deals an extra 1d6 damage for each ferocity spent. While you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), it deals an extra 1d10 damage for each ferocity spent. In either case, you lose 1d6 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) after making this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
    flavor: You gut your life force to ensure a foe's demise.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: To the Uttermost End
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/to-the-uttermost-end
    target: One creature
    tier1: 7 + M damage
    tier2: 11 + M damage
    tier3: 16 + M damage
    type: ability
name: To the Uttermost End
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
