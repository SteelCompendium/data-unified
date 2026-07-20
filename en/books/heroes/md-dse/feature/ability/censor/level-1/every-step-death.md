---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: Each time the target willingly moves before the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they take 1 psychic damage for each square they move.
feature_type: ability
file_basename: every-step-death
file_dpath: feature/ability/censor/level-1
flavor: You show your foe a glimpse of their fate after death.
item_id: every-step-death
item_name: Every Step... Death!
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Every Step... Death!
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/every-step-death
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 5 + P psychic damage
tier2: 7 + P psychic damage
tier3: 10 + P psychic damage
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Each time the target willingly moves before the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they take 1 psychic damage for each square they move.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 + P psychic damage
      tier2: 7 + P psychic damage
      tier3: 10 + P psychic damage
feature_type: ability
flavor: You show your foe a glimpse of their fate after death.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: Each time the target willingly moves before the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), they take 1 psychic damage for each square they move.
    flavor: You show your foe a glimpse of their fate after death.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Every Step... Death!
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/every-step-death
    subtype: signature
    target: One creature
    tier1: 5 + P psychic damage
    tier2: 7 + P psychic damage
    tier3: 10 + P psychic damage
    type: ability
name: Every Step... Death!
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
