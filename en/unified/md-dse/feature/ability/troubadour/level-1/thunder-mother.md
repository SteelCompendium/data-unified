---
action_type: No action
class: troubadour
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: At the end of each [combat round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) while this performance is active, you can make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the target that ignores [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover). You can't target the same creature twice with this effect.
feature_type: ability
file_basename: thunder-mother
file_dpath: feature/ability/troubadour/level-1
flavor: All for thunder motherrr! ♪ Run and hide for coverrr!♪
item_id: thunder-mother
item_name: '"Thunder Mother"'
keywords:
    - Magic
    - Performance
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: '"Thunder Mother"'
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/thunder-mother
source: mcdm.heroes.v1
subclass: virtuoso
target: One creature
tier1: Lightning damage equal to your level
tier2: Lightning damage equal to 5 + your level
tier3: Lightning damage equal to 10 + your level
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: At the end of each [combat round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) while this performance is active, you can make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the target that ignores [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover). You can't target the same creature twice with this effect.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: Lightning damage equal to your level
      tier2: Lightning damage equal to 5 + your level
      tier3: Lightning damage equal to 10 + your level
feature_type: ability
flavor: All for thunder motherrr! ♪ Run and hide for coverrr!♪
keywords:
    - Magic
    - Performance
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: No action
    class: troubadour
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: At the end of each [combat round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) while this performance is active, you can make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the target that ignores [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover). You can't target the same creature twice with this effect.
    flavor: All for thunder motherrr! ♪ Run and hide for coverrr!♪
    keywords:
        - Magic
        - Performance
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: '"Thunder Mother"'
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/thunder-mother
    subclass: virtuoso
    target: One creature
    tier1: Lightning damage equal to your level
    tier2: Lightning damage equal to 5 + your level
    tier3: Lightning damage equal to 10 + your level
    type: ability
name: '"Thunder Mother"'
target: One creature
type: feature
usage: No action
```
