---
action_type: Main action
class: shadow
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: As long as you have one or more allies within 5 squares of the target, you gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge). If you are [flanking](scc.v1:mcdm.heroes.v1/rule.combat/flanking) the target when you use this ability, choose one ally who is [flanking](scc.v1:mcdm.heroes.v1/rule.combat/flanking) with you. That ally also gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
feature_type: ability
file_basename: you-were-watching-the-wrong-one
file_dpath: feature/ability/shadow/level-1
flavor: They can't watch both of you at once.
item_id: you-were-watching-the-wrong-one
item_name: You Were Watching the Wrong One
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: You Were Watching the Wrong One
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/you-were-watching-the-wrong-one
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + A damage
tier2: 5 + A damage
tier3: 8 + A damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: As long as you have one or more allies within 5 squares of the target, you gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge). If you are [flanking](scc.v1:mcdm.heroes.v1/rule.combat/flanking) the target when you use this ability, choose one ally who is [flanking](scc.v1:mcdm.heroes.v1/rule.combat/flanking) with you. That ally also gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + A damage
      tier2: 5 + A damage
      tier3: 8 + A damage
feature_type: ability
flavor: They can't watch both of you at once.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: As long as you have one or more allies within 5 squares of the target, you gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge). If you are [flanking](scc.v1:mcdm.heroes.v1/rule.combat/flanking) the target when you use this ability, choose one ally who is [flanking](scc.v1:mcdm.heroes.v1/rule.combat/flanking) with you. That ally also gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
    flavor: They can't watch both of you at once.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: You Were Watching the Wrong One
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/you-were-watching-the-wrong-one
    subtype: signature
    target: One creature
    tier1: 3 + A damage
    tier2: 5 + A damage
    tier3: 8 + A damage
    type: ability
name: You Were Watching the Wrong One
target: One creature
type: feature
usage: Main action
```
