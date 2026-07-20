---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: While [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, the target takes damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score at the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
file_basename: your-entrails-are-your-extrails
file_dpath: feature/ability/fury/level-1
flavor: Hard for them to fight when they're busy holding in their giblets.
item_id: your-entrails-are-your-extrails
item_name: Your Entrails Are Your Extrails!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Your Entrails Are Your Extrails!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/your-entrails-are-your-extrails
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + M damage; M < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier2: 5 + M damage; M < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier3: 8 + M damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: While [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, the target takes damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score at the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M damage; M < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier2: 5 + M damage; M < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier3: 8 + M damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
feature_type: ability
flavor: Hard for them to fight when they're busy holding in their giblets.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 3 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: While [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, the target takes damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score at the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    flavor: Hard for them to fight when they're busy holding in their giblets.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Your Entrails Are Your Extrails!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/your-entrails-are-your-extrails
    target: One creature or object
    tier1: 3 + M damage; M < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    tier2: 5 + M damage; M < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    tier3: 8 + M damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    type: ability
name: Your Entrails Are Your Extrails!
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
