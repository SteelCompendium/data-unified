---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: If the target makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against a creature while [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, you can spend 3 wrath to deal holy damage to them equal to your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score, then change the target of the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) to another target within the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'s [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
feature_type: ability
file_basename: arrest
file_dpath: feature/ability/censor/level-1
flavor: '"I got you, you son of a bitch."'
item_id: arrest
item_name: Arrest
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Arrest
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/arrest
source: mcdm.heroes.v1
target: One creature
tier1: 6 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier2: 9 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier3: 13 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
type: ability
---

```ds-feature
cost: 5 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: If the target makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against a creature while [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, you can spend 3 wrath to deal holy damage to them equal to your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score, then change the target of the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) to another target within the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'s [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier2: 9 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier3: 13 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
feature_type: ability
flavor: '"I got you, you son of a bitch."'
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 5 Wrath
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: If the target makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against a creature while [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, you can spend 3 wrath to deal holy damage to them equal to your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score, then change the target of the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) to another target within the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'s [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
    flavor: '"I got you, you son of a bitch."'
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Arrest
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/arrest
    target: One creature
    tier1: 6 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier2: 9 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier3: 13 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    type: ability
name: Arrest
target: One creature
type: feature
usage: Main action
```
