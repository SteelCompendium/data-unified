---
action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: The target takes half the damage. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the triggering creature.
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: A < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: A < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: A < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
feature_type: ability
file_basename: instant-retaliation
file_dpath: feature/ability/tactician/level-6
flavor: You [parry](scc.v1:mcdm.heroes.v1/feature.ability.tactician.level-1/parry) with almost [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) [speed](scc.v1:mcdm.heroes.v1/rule.character/speed).
item_id: instant-retaliation
item_name: Instant Retaliation
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "6"
name: Instant Retaliation
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/instant-retaliation
source: mcdm.heroes.v1
subclass: vanguard
subtype: triggered
target: One ally
tier1: A < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier2: A < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier3: A < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
trigger: A creature deals damage to the target.
type: ability
---

```ds-feature
cost: 9 Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: The target takes half the damage. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the triggering creature.
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: A < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: A < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: A < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
feature_type: ability
flavor: You [parry](scc.v1:mcdm.heroes.v1/feature.ability.tactician.level-1/parry) with almost [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) [speed](scc.v1:mcdm.heroes.v1/rule.character/speed).
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
    class: tactician
    cost: 9 Focus
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - effect: The target takes half the damage. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the triggering creature.
          name: Effect
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: A < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier2: A < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier3: A < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    flavor: You [parry](scc.v1:mcdm.heroes.v1/feature.ability.tactician.level-1/parry) with almost [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) [speed](scc.v1:mcdm.heroes.v1/rule.character/speed).
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "6"
    name: Instant Retaliation
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/instant-retaliation
    subclass: vanguard
    subtype: triggered
    target: One ally
    tier1: A < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier2: A < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier3: A < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    trigger: A creature deals damage to the target.
    type: ability
name: Instant Retaliation
target: One ally
trigger: A creature deals damage to the target.
type: feature
usage: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
```
