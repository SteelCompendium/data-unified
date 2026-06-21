---
action_type: Main action
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effect: If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before one or both chosen allies has made their [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the ally or allies can pick a different target.
feature_type: ability
file_basename: hammer-and-anvil
file_dpath: feature/ability/tactician/level-1
flavor: '"Let''s not argue about who''s the hammer and who''s the anvil!"'
item_id: hammer-and-anvil
item_name: Hammer and Anvil
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Hammer and Anvil
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/hammer-and-anvil
source: mcdm.heroes.v1
target: One creature or object
tier1: 5 + M damage; one ally within 10 squares of you can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
tier2: 9 + M damage; one ally within 10 squares of you can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
tier3: 12 + M damage; two allies within 10 squares of you can each use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
type: ability
---

```ds-feature
cost: 5 Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - effect: If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before one or both chosen allies has made their [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the ally or allies can pick a different target.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 5 + M damage; one ally within 10 squares of you can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
      tier2: 9 + M damage; one ally within 10 squares of you can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
      tier3: 12 + M damage; two allies within 10 squares of you can each use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
feature_type: ability
flavor: '"Let''s not argue about who''s the hammer and who''s the anvil!"'
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 5 Focus
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effect: If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before one or both chosen allies has made their [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the ally or allies can pick a different target.
    flavor: '"Let''s not argue about who''s the hammer and who''s the anvil!"'
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Hammer and Anvil
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/hammer-and-anvil
    target: One creature or object
    tier1: 5 + M damage; one ally within 10 squares of you can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
    tier2: 9 + M damage; one ally within 10 squares of you can use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
    tier3: 12 + M damage; two allies within 10 squares of you can each use a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against the target as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
    type: ability
name: Hammer and Anvil
target: One creature or object
type: feature
usage: Main action
```
