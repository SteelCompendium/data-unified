---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: talent
cost: 7 Clarity
cost_amount: "7"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 3 + P corruption damage; P < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 5 + P corruption damage; the target is flung through time, and if P < AVERAGE, they are [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 8 + P corruption damage; the target is flung through time, and if P < STRONG, they are [weakened](../../../../condition/weakened.md) (save ends)
    - effect: A target who is flung through time is removed from the encounter map until the end of their next [turn](../../../../rule/combat/turn.md), reappearing in their original space or the nearest unoccupied space.
      name: Effect
    - effect: You take 2d6 damage and permanently grow visibly older (the equivalent of 10 years for a [human](../../../../ancestry/human.md)). If you obtain a tier 3 outcome on the [power roll](../../../../rule/dice/power-roll.md), you gain 2 clarity.
      name: Strained
feature_type: ability
file_basename: fling-through-time
file_dpath: feature/ability/talent/level-3
flavor: You hurl the target through the annals of time, forcing them to witness every moment of their existence all at once.
item_id: fling-through-time
item_name: Fling Through Time
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
level: "3"
name: Fling Through Time
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-3/fling-through-time
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + P corruption damage; P < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
tier2: 5 + P corruption damage; the target is flung through time, and if P < AVERAGE, they are [weakened](../../../../condition/weakened.md) (save ends)
tier3: 8 + P corruption damage; the target is flung through time, and if P < STRONG, they are [weakened](../../../../condition/weakened.md) (save ends)
type: ability
---

```ds-feature
cost: 7 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 3 + P corruption damage; P < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 5 + P corruption damage; the target is flung through time, and if P < AVERAGE, they are [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 8 + P corruption damage; the target is flung through time, and if P < STRONG, they are [weakened](../../../../condition/weakened.md) (save ends)
    - effect: A target who is flung through time is removed from the encounter map until the end of their next [turn](../../../../rule/combat/turn.md), reappearing in their original space or the nearest unoccupied space.
      name: Effect
    - effect: You take 2d6 damage and permanently grow visibly older (the equivalent of 10 years for a [human](../../../../ancestry/human.md)). If you obtain a tier 3 outcome on the [power roll](../../../../rule/dice/power-roll.md), you gain 2 clarity.
      name: Strained
feature_type: ability
flavor: You hurl the target through the annals of time, forcing them to witness every moment of their existence all at once.
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: talent
    cost: 7 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
          tier1: 3 + P corruption damage; P < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
          tier2: 5 + P corruption damage; the target is flung through time, and if P < AVERAGE, they are [weakened](../../../../condition/weakened.md) (save ends)
          tier3: 8 + P corruption damage; the target is flung through time, and if P < STRONG, they are [weakened](../../../../condition/weakened.md) (save ends)
        - effect: A target who is flung through time is removed from the encounter map until the end of their next [turn](../../../../rule/combat/turn.md), reappearing in their original space or the nearest unoccupied space.
          name: Effect
        - effect: You take 2d6 damage and permanently grow visibly older (the equivalent of 10 years for a [human](../../../../ancestry/human.md)). If you obtain a tier 3 outcome on the [power roll](../../../../rule/dice/power-roll.md), you gain 2 clarity.
          name: Strained
    flavor: You hurl the target through the annals of time, forcing them to witness every moment of their existence all at once.
    keywords:
        - Chronopathy
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - Strike
    level: "3"
    name: Fling Through Time
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-3/fling-through-time
    target: One creature or object
    tier1: 3 + P corruption damage; P < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
    tier2: 5 + P corruption damage; the target is flung through time, and if P < AVERAGE, they are [weakened](../../../../condition/weakened.md) (save ends)
    tier3: 8 + P corruption damage; the target is flung through time, and if P < STRONG, they are [weakened](../../../../condition/weakened.md) (save ends)
    type: ability
name: Fling Through Time
target: One creature or object
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
