---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 9 Wrath
cost_amount: "9"
cost_resource: Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 8 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), one ally within 10 squares of the target can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the target
      tier2: 12 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), one ally within 10 squares of the target can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target
      tier3: 16 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), two allies within 10 squares of the target can each use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target
    - effect: Each ally can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares and gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) before making the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
      name: Effect
feature_type: ability
file_basename: congregation
file_dpath: feature/ability/censor/level-6
flavor: You focus your allies' wrath on a chosen foe.
item_id: congregation
item_name: Congregation
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Congregation
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-6/congregation
source: mcdm.heroes.v1
subclass: paragon
target: One creature
tier1: 8 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), one ally within 10 squares of the target can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the target
tier2: 12 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), one ally within 10 squares of the target can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target
tier3: 16 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), two allies within 10 squares of the target can each use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target
type: ability
---

```ds-feature
cost: 9 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 8 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), one ally within 10 squares of the target can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the target
      tier2: 12 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), one ally within 10 squares of the target can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target
      tier3: 16 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), two allies within 10 squares of the target can each use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target
    - effect: Each ally can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares and gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) before making the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
      name: Effect
feature_type: ability
flavor: You focus your allies' wrath on a chosen foe.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 9 Wrath
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 8 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), one ally within 10 squares of the target can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the target
          tier2: 12 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), one ally within 10 squares of the target can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target
          tier3: 16 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), two allies within 10 squares of the target can each use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target
        - effect: Each ally can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares and gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) before making the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
          name: Effect
    flavor: You focus your allies' wrath on a chosen foe.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "6"
    name: Congregation
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-6/congregation
    subclass: paragon
    target: One creature
    tier1: 8 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), one ally within 10 squares of the target can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the target
    tier2: 12 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), one ally within 10 squares of the target can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target
    tier3: 16 + M damage; as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), two allies within 10 squares of the target can each use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target
    type: ability
name: Congregation
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
