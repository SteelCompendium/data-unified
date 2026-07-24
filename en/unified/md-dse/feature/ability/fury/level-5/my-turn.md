---
action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M damage
      tier2: 9 + M damage
      tier3: 13 + M damage
    - effect: You can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
feature_type: ability
file_basename: my-turn
file_dpath: feature/ability/fury/level-5
flavor: You quickly strike back at a foe.
item_id: my-turn
item_name: My Turn!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "5"
name: My Turn!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-5/my-turn
source: mcdm.heroes.v1
subtype: triggered
target: The triggering creature
tier1: 6 + M damage
tier2: 9 + M damage
tier3: 13 + M damage
trigger: A creature causes you to be [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) or [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or damages you while you are [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) or [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M damage
      tier2: 9 + M damage
      tier3: 13 + M damage
    - effect: You can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
      name: Effect
feature_type: ability
flavor: You quickly strike back at a foe.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 6 + M damage
          tier2: 9 + M damage
          tier3: 13 + M damage
        - effect: You can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
          name: Effect
    flavor: You quickly strike back at a foe.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "5"
    name: My Turn!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-5/my-turn
    subtype: triggered
    target: The triggering creature
    tier1: 6 + M damage
    tier2: 9 + M damage
    tier3: 13 + M damage
    trigger: A creature causes you to be [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) or [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or damages you while you are [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) or [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
    type: ability
name: My Turn!
target: The triggering creature
trigger: A creature causes you to be [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) or [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or damages you while you are [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) or [dying](scc.v1:mcdm.heroes.v1/rule.health/dying).
type: feature
usage: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
```
