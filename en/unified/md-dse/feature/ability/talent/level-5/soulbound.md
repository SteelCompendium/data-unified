---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 8 damage; A < WEAK, the target is stitched to the other target (save ends)
      tier2: 13 damage; A < AVERAGE, the target is stitched to the other target (save ends)
      tier3: 17 damage; A < STRONG, the target is stitched to the other target (save ends)
    - effect: If any target becomes stitched to the other, both targets are stitched together. While stitched together, a target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) while not [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a creature they're stitched to. Whenever a stitched target takes damage that wasn't dealt by or also taken by another stitched target, each other stitched target takes half the damage the initial target took.
      name: Effect
    - effect: You target yourself and three enemies instead.
      name: Strained
feature_type: ability
file_basename: soulbound
file_dpath: feature/ability/talent/level-5
flavor: You fire a piercing bolt of psychic energy that lances through two foes and leaves a faint intangible thread between them.
item_id: soulbound
item_name: Soulbound
keywords:
    - Animapathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "5"
name: Soulbound
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.talent.level-5/soulbound
source: mcdm.heroes.v1
target: Two enemies
tier1: 8 damage; A < WEAK, the target is stitched to the other target (save ends)
tier2: 13 damage; A < AVERAGE, the target is stitched to the other target (save ends)
tier3: 17 damage; A < STRONG, the target is stitched to the other target (save ends)
type: ability
---

```ds-feature
cost: 9 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 8 damage; A < WEAK, the target is stitched to the other target (save ends)
      tier2: 13 damage; A < AVERAGE, the target is stitched to the other target (save ends)
      tier3: 17 damage; A < STRONG, the target is stitched to the other target (save ends)
    - effect: If any target becomes stitched to the other, both targets are stitched together. While stitched together, a target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) while not [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a creature they're stitched to. Whenever a stitched target takes damage that wasn't dealt by or also taken by another stitched target, each other stitched target takes half the damage the initial target took.
      name: Effect
    - effect: You target yourself and three enemies instead.
      name: Strained
feature_type: ability
flavor: You fire a piercing bolt of psychic energy that lances through two foes and leaves a faint intangible thread between them.
keywords:
    - Animapathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 9 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
          tier1: 8 damage; A < WEAK, the target is stitched to the other target (save ends)
          tier2: 13 damage; A < AVERAGE, the target is stitched to the other target (save ends)
          tier3: 17 damage; A < STRONG, the target is stitched to the other target (save ends)
        - effect: If any target becomes stitched to the other, both targets are stitched together. While stitched together, a target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) while not [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to a creature they're stitched to. Whenever a stitched target takes damage that wasn't dealt by or also taken by another stitched target, each other stitched target takes half the damage the initial target took.
          name: Effect
        - effect: You target yourself and three enemies instead.
          name: Strained
    flavor: You fire a piercing bolt of psychic energy that lances through two foes and leaves a faint intangible thread between them.
    keywords:
        - Animapathy
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "5"
    name: Soulbound
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-5/soulbound
    target: Two enemies
    tier1: 8 damage; A < WEAK, the target is stitched to the other target (save ends)
    tier2: 13 damage; A < AVERAGE, the target is stitched to the other target (save ends)
    tier3: 17 damage; A < STRONG, the target is stitched to the other target (save ends)
    type: ability
name: Soulbound
target: Two enemies
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
