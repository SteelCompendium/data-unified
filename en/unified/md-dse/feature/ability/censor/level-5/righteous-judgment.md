---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 9 Wrath
cost_amount: "9"
cost_resource: Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: Until the end of the encounter, whenever any ally deals damage to a target judged by you, that ally gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
feature_type: ability
file_basename: righteous-judgment
file_dpath: feature/ability/censor/level-5
flavor: You amplify the power of your [judgment](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-1/judgment).
item_id: righteous-judgment
item_name: Righteous Judgment
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "5"
name: Righteous Judgment
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-5/righteous-judgment
source: mcdm.heroes.v1
target: One creature
tier1: 10 + M damage
tier2: 14 + M damage
tier3: 20 + M damage
type: ability
---

```ds-feature
cost: 9 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: Until the end of the encounter, whenever any ally deals damage to a target judged by you, that ally gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 10 + M damage
      tier2: 14 + M damage
      tier3: 20 + M damage
feature_type: ability
flavor: You amplify the power of your [judgment](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-1/judgment).
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 9 Wrath
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: Until the end of the encounter, whenever any ally deals damage to a target judged by you, that ally gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    flavor: You amplify the power of your [judgment](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-1/judgment).
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "5"
    name: Righteous Judgment
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-5/righteous-judgment
    target: One creature
    tier1: 10 + M damage
    tier2: 14 + M damage
    tier3: 20 + M damage
    type: ability
name: Righteous Judgment
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
