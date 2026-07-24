---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: '[Melee](../../../../rule/combat/melee.md) 2'
effects:
    - effect: The target has [damage weakness](../../../../rule/damage/damage-weakness.md) 5 until the end of your next [turn](../../../../rule/combat/turn.md). Whenever the target takes damage while they have this weakness, they are [knocked prone](../../../../condition/prone.md).
      name: Effect
    - effect: This ability gains the [Strike](../../../../rule/combat/strike.md) keyword as the vision hurts the target's psyche. You make a [power roll](../../../../rule/dice/power-roll.md), then are [weakened](../../../../condition/weakened.md) (save ends).
      name: Strained
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 8 + P psychic damage
      tier2: 13 + P psychic damage
      tier3: 17 + P psychic damage
feature_type: ability
file_basename: fate
file_dpath: feature/ability/talent/level-6
flavor: Your foe gets a glimpse of how it will end for them.
item_id: fate
item_name: Fate
keywords:
    - Chronopathy
    - Psionic
    - '[Melee](../../../../rule/combat/melee.md)'
level: "6"
name: Fate
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-6/fate
source: mcdm.heroes.v1
subclass: chronopathy
target: One enemy
tier1: 8 + P psychic damage
tier2: 13 + P psychic damage
tier3: 17 + P psychic damage
type: ability
---

```ds-feature
cost: 9 Clarity
distance: '[Melee](../../../../rule/combat/melee.md) 2'
effects:
    - effect: The target has [damage weakness](../../../../rule/damage/damage-weakness.md) 5 until the end of your next [turn](../../../../rule/combat/turn.md). Whenever the target takes damage while they have this weakness, they are [knocked prone](../../../../condition/prone.md).
      name: Effect
    - effect: This ability gains the [Strike](../../../../rule/combat/strike.md) keyword as the vision hurts the target's psyche. You make a [power roll](../../../../rule/dice/power-roll.md), then are [weakened](../../../../condition/weakened.md) (save ends).
      name: Strained
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 8 + P psychic damage
      tier2: 13 + P psychic damage
      tier3: 17 + P psychic damage
feature_type: ability
flavor: Your foe gets a glimpse of how it will end for them.
keywords:
    - Chronopathy
    - Psionic
    - '[Melee](../../../../rule/combat/melee.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: talent
    cost: 9 Clarity
    distance: '[Melee](../../../../rule/combat/melee.md) 2'
    effects:
        - effect: The target has [damage weakness](../../../../rule/damage/damage-weakness.md) 5 until the end of your next [turn](../../../../rule/combat/turn.md). Whenever the target takes damage while they have this weakness, they are [knocked prone](../../../../condition/prone.md).
          name: Effect
        - effect: This ability gains the [Strike](../../../../rule/combat/strike.md) keyword as the vision hurts the target's psyche. You make a [power roll](../../../../rule/dice/power-roll.md), then are [weakened](../../../../condition/weakened.md) (save ends).
          name: Strained
        - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
          tier1: 8 + P psychic damage
          tier2: 13 + P psychic damage
          tier3: 17 + P psychic damage
    flavor: Your foe gets a glimpse of how it will end for them.
    keywords:
        - Chronopathy
        - Psionic
        - '[Melee](../../../../rule/combat/melee.md)'
    level: "6"
    name: Fate
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-6/fate
    subclass: chronopathy
    target: One enemy
    tier1: 8 + P psychic damage
    tier2: 13 + P psychic damage
    tier3: 17 + P psychic damage
    type: ability
name: Fate
target: One enemy
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
