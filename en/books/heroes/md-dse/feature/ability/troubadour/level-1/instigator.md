---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by you or a willing ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
file_basename: instigator
file_dpath: feature/ability/troubadour/level-1
flavor: I didn't do it! What?
item_id: instigator
item_name: Instigator
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Instigator
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/instigator
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + P damage
tier2: 6 + P damage
tier3: 9 + P damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by you or a willing ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 3 + P damage
      tier2: 6 + P damage
      tier3: 9 + P damage
feature_type: ability
flavor: I didn't do it! What?
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by you or a willing ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    flavor: I didn't do it! What?
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Instigator
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/instigator
    subtype: signature
    target: One creature
    tier1: 3 + P damage
    tier2: 6 + P damage
    tier3: 9 + P damage
    type: ability
name: Instigator
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
