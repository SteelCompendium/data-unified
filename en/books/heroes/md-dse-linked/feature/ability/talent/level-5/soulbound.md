---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: If any target becomes stitched to the other, both targets are stitched together. While stitched together, a target takes a [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) while not [adjacent](../../../../rule/combat/adjacent.md) to a creature they're stitched to. Whenever a stitched target takes damage that wasn't dealt by or also taken by another stitched target, each other stitched target takes half the damage the initial target took.
feature_type: ability
file_basename: soulbound
file_dpath: feature/ability/talent/level-5
flavor: You fire a piercing bolt of psychic energy that lances through two foes and leaves a faint intangible thread between them.
item_id: soulbound
item_name: Soulbound
keywords:
    - Animapathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "5"
name: Soulbound
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
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
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: If any target becomes stitched to the other, both targets are stitched together. While stitched together, a target takes a [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) while not [adjacent](../../../../rule/combat/adjacent.md) to a creature they're stitched to. Whenever a stitched target takes damage that wasn't dealt by or also taken by another stitched target, each other stitched target takes half the damage the initial target took.
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 8 damage; A < WEAK, the target is stitched to the other target (save ends)
      tier2: 13 damage; A < AVERAGE, the target is stitched to the other target (save ends)
      tier3: 17 damage; A < STRONG, the target is stitched to the other target (save ends)
feature_type: ability
flavor: You fire a piercing bolt of psychic energy that lances through two foes and leaves a faint intangible thread between them.
keywords:
    - Animapathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: talent
    cost: 9 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: If any target becomes stitched to the other, both targets are stitched together. While stitched together, a target takes a [bane](../../../../rule/dice/bane.md) on [power rolls](../../../../rule/dice/power-roll.md) while not [adjacent](../../../../rule/combat/adjacent.md) to a creature they're stitched to. Whenever a stitched target takes damage that wasn't dealt by or also taken by another stitched target, each other stitched target takes half the damage the initial target took.
    flavor: You fire a piercing bolt of psychic energy that lances through two foes and leaves a faint intangible thread between them.
    keywords:
        - Animapathy
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "5"
    name: Soulbound
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-5/soulbound
    target: Two enemies
    tier1: 8 damage; A < WEAK, the target is stitched to the other target (save ends)
    tier2: 13 damage; A < AVERAGE, the target is stitched to the other target (save ends)
    tier3: 17 damage; A < STRONG, the target is stitched to the other target (save ends)
    type: ability
name: Soulbound
target: Two enemies
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
