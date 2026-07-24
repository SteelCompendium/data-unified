---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - effect: The target has [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 until the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Whenever the target takes damage while they have this weakness, they are [knocked prone](scc.v1:mcdm.heroes.v1/condition/prone).
      name: Effect
    - effect: This ability gains the [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) keyword as the vision hurts the target's psyche. You make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll), then are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends).
      name: Strained
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
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
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
level: "6"
name: Fate
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
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
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - effect: The target has [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 until the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Whenever the target takes damage while they have this weakness, they are [knocked prone](scc.v1:mcdm.heroes.v1/condition/prone).
      name: Effect
    - effect: This ability gains the [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) keyword as the vision hurts the target's psyche. You make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll), then are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends).
      name: Strained
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 8 + P psychic damage
      tier2: 13 + P psychic damage
      tier3: 17 + P psychic damage
feature_type: ability
flavor: Your foe gets a glimpse of how it will end for them.
keywords:
    - Chronopathy
    - Psionic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 9 Clarity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
    effects:
        - effect: The target has [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 until the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Whenever the target takes damage while they have this weakness, they are [knocked prone](scc.v1:mcdm.heroes.v1/condition/prone).
          name: Effect
        - effect: This ability gains the [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) keyword as the vision hurts the target's psyche. You make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll), then are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends).
          name: Strained
        - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
          tier1: 8 + P psychic damage
          tier2: 13 + P psychic damage
          tier3: 17 + P psychic damage
    flavor: Your foe gets a glimpse of how it will end for them.
    keywords:
        - Chronopathy
        - Psionic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    level: "6"
    name: Fate
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
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
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
