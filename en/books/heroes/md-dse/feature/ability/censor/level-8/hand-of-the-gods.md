---
action_type: Main action
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: Until the end of the encounter, while the target is judged by you, you can choose to make them the source of any of your abilities. Additionally, the target counts as an ally for the purpose of [flanking](scc.v1:mcdm.heroes.v1/rule.combat/flanking).
feature_type: ability
file_basename: hand-of-the-gods
file_dpath: feature/ability/censor/level-8
flavor: You use your foe as a tool against your enemies.
item_id: hand-of-the-gods
item_name: Hand of the Gods
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: Hand of the Gods
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-8/hand-of-the-gods
source: mcdm.heroes.v1
target: One creature
tier1: 10 + M damage
tier2: 15 + M damage
tier3: 21 + M damage
type: ability
---

```ds-feature
cost: 11 Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Until the end of the encounter, while the target is judged by you, you can choose to make them the source of any of your abilities. Additionally, the target counts as an ally for the purpose of [flanking](scc.v1:mcdm.heroes.v1/rule.combat/flanking).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 10 + M damage
      tier2: 15 + M damage
      tier3: 21 + M damage
feature_type: ability
flavor: You use your foe as a tool against your enemies.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 11 Wrath
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: Until the end of the encounter, while the target is judged by you, you can choose to make them the source of any of your abilities. Additionally, the target counts as an ally for the purpose of [flanking](scc.v1:mcdm.heroes.v1/rule.combat/flanking).
    flavor: You use your foe as a tool against your enemies.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "8"
    name: Hand of the Gods
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-8/hand-of-the-gods
    target: One creature
    tier1: 10 + M damage
    tier2: 15 + M damage
    tier3: 21 + M damage
    type: ability
name: Hand of the Gods
target: One creature
type: feature
usage: Main action
```
