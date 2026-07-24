---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 11 Clarity
cost_amount: "11"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 15 + R psychic damage
      tier2: 24 + R psychic damage
      tier3: 28 + R psychic damage
    - effect: This ability ignores [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover) and [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment).
      name: Effect
    - effect: The [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) scores a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit) on a natural 17 or higher. You take half the damage the target takes, and you can't reduce this damage in any way.
      name: Strained
feature_type: ability
file_basename: resonant-mind-spike
file_dpath: feature/ability/talent/level-9
flavor: You fire a telepathic bolt empowered by every consciousness within reach directly into your foe's mind.
item_id: resonant-mind-spike
item_name: Resonant Mind Spike
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
level: "9"
name: Resonant Mind Spike
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-9/resonant-mind-spike
source: mcdm.heroes.v1
subclass: telepathy
target: One creature
tier1: 15 + R psychic damage
tier2: 24 + R psychic damage
tier3: 28 + R psychic damage
type: ability
---

```ds-feature
cost: 11 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 15 + R psychic damage
      tier2: 24 + R psychic damage
      tier3: 28 + R psychic damage
    - effect: This ability ignores [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover) and [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment).
      name: Effect
    - effect: The [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) scores a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit) on a natural 17 or higher. You take half the damage the target takes, and you can't reduce this damage in any way.
      name: Strained
feature_type: ability
flavor: You fire a telepathic bolt empowered by every consciousness within reach directly into your foe's mind.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 11 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: 15 + R psychic damage
          tier2: 24 + R psychic damage
          tier3: 28 + R psychic damage
        - effect: This ability ignores [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover) and [concealment](scc.v1:mcdm.heroes.v1/rule.combat/concealment).
          name: Effect
        - effect: The [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) scores a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit) on a natural 17 or higher. You take half the damage the target takes, and you can't reduce this damage in any way.
          name: Strained
    flavor: You fire a telepathic bolt empowered by every consciousness within reach directly into your foe's mind.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Telepathy
    level: "9"
    name: Resonant Mind Spike
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-9/resonant-mind-spike
    subclass: telepathy
    target: One creature
    tier1: 15 + R psychic damage
    tier2: 24 + R psychic damage
    tier3: 28 + R psychic damage
    type: ability
name: Resonant Mind Spike
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
