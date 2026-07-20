---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: One ally within 5 squares of the target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
feature_type: ability
file_basename: gasping-in-pain
file_dpath: feature/ability/shadow/level-1
flavor: Your precise strikes let your allies take advantage of a target's agony.
item_id: gasping-in-pain
item_name: Gasping in Pain
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Gasping in Pain
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/gasping-in-pain
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + A damage
tier2: 5 + A damage
tier3: 8 + A damage; I < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: One ally within 5 squares of the target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + A damage
      tier2: 5 + A damage
      tier3: 8 + A damage; I < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
feature_type: ability
flavor: Your precise strikes let your allies take advantage of a target's agony.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: shadow
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: One ally within 5 squares of the target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    flavor: Your precise strikes let your allies take advantage of a target's agony.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Gasping in Pain
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/gasping-in-pain
    subtype: signature
    target: One creature
    tier1: 3 + A damage
    tier2: 5 + A damage
    tier3: 8 + A damage; I < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: Gasping in Pain
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
