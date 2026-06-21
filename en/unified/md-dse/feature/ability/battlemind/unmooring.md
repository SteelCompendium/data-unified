---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) that affects the target has its [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) increased by 2.
feature_type: ability
file_basename: unmooring
file_dpath: feature/ability/battlemind
flavor: Your weapon unleashes psionic energy that reduces your target's weight.
item_id: unmooring
item_name: Unmooring
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: battlemind
name: Unmooring
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.battlemind/unmooring
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 5 + M, R, I, or P damage
tier2: 8 + M, R, I, or P damage
tier3: 11 + M, R, I, or P damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) that affects the target has its [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) increased by 2.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 + M, R, I, or P damage
      tier2: 8 + M, R, I, or P damage
      tier3: 11 + M, R, I, or P damage
feature_type: ability
flavor: Your weapon unleashes psionic energy that reduces your target's weight.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: Until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) that affects the target has its [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) increased by 2.
    flavor: Your weapon unleashes psionic energy that reduces your target's weight.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: battlemind
    name: Unmooring
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.battlemind/unmooring
    subtype: signature
    target: One creature
    tier1: 5 + M, R, I, or P damage
    tier2: 8 + M, R, I, or P damage
    tier3: 11 + M, R, I, or P damage
    type: ability
name: Unmooring
target: One creature
type: feature
usage: Main action
```
