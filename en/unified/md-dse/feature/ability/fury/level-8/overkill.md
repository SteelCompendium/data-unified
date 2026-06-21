---
action_type: Main action
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: If the target is a minion or is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) but isn't a leader or solo creature, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before this ability's damage is dealt. If the target is killed by this damage, you can deal any damage over what was required to kill them to another creature within 5 squares of the target.
feature_type: ability
file_basename: overkill
file_dpath: feature/ability/fury/level-8
flavor: You strike so no damage is wasted.
item_id: overkill
item_name: Overkill
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: Overkill
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-8/overkill
source: mcdm.heroes.v1
target: One creature
tier1: 6 + M damage
tier2: 10 + M damage
tier3: 14 + M damage
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: If the target is a minion or is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) but isn't a leader or solo creature, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before this ability's damage is dealt. If the target is killed by this damage, you can deal any damage over what was required to kill them to another creature within 5 squares of the target.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M damage
      tier2: 10 + M damage
      tier3: 14 + M damage
feature_type: ability
flavor: You strike so no damage is wasted.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 11 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: If the target is a minion or is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) but isn't a leader or solo creature, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before this ability's damage is dealt. If the target is killed by this damage, you can deal any damage over what was required to kill them to another creature within 5 squares of the target.
    flavor: You strike so no damage is wasted.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "8"
    name: Overkill
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-8/overkill
    target: One creature
    tier1: 6 + M damage
    tier2: 10 + M damage
    tier3: 14 + M damage
    type: ability
name: Overkill
target: One creature
type: feature
usage: Main action
```
