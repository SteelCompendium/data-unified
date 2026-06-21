---
action_type: Main action
class: fury
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can deal 1d6 damage to yourself to deal an extra 1d6 damage to the target.
feature_type: ability
file_basename: blood-for-blood
file_dpath: feature/ability/fury/level-1
flavor: See how well they fight after you've bled them dry.
item_id: blood-for-blood
item_name: Blood for Blood!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Blood for Blood!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/blood-for-blood
source: mcdm.heroes.v1
target: One creature or object
tier1: 4 + M damage; M < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 6 + M damage; M < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 10 + M damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can deal 1d6 damage to yourself to deal an extra 1d6 damage to the target.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 4 + M damage; M < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 6 + M damage; M < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 10 + M damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
feature_type: ability
flavor: See how well they fight after you've bled them dry.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 5 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can deal 1d6 damage to yourself to deal an extra 1d6 damage to the target.
    flavor: See how well they fight after you've bled them dry.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Blood for Blood!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/blood-for-blood
    target: One creature or object
    tier1: 4 + M damage; M < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier2: 6 + M damage; M < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier3: 10 + M damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    type: ability
name: Blood for Blood!
target: One creature or object
type: feature
usage: Main action
```
