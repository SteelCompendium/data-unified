---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: While [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, the target takes 3 psychic damage for each square they willingly leave.
feature_type: ability
file_basename: mind-snare
file_dpath: feature/ability/talent/level-5
flavor: You latch onto your prey's brain and don't let go, like a song they can't get out of their head.
item_id: mind-snare
item_name: Mind Snare
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
level: "5"
name: Mind Snare
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-5/mind-snare
source: mcdm.heroes.v1
target: One creature
tier1: 10 + R psychic damage; R < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 14 + R psychic damage; R < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 20 + R psychic damage; R < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
type: ability
---

```ds-feature
cost: 9 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: While [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, the target takes 3 psychic damage for each square they willingly leave.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 10 + R psychic damage; R < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 14 + R psychic damage; R < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 20 + R psychic damage; R < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
feature_type: ability
flavor: You latch onto your prey's brain and don't let go, like a song they can't get out of their head.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 9 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: While [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, the target takes 3 psychic damage for each square they willingly leave.
    flavor: You latch onto your prey's brain and don't let go, like a song they can't get out of their head.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Telepathy
    level: "5"
    name: Mind Snare
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-5/mind-snare
    target: One creature
    tier1: 10 + R psychic damage; R < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier2: 14 + R psychic damage; R < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier3: 20 + R psychic damage; R < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    type: ability
name: Mind Snare
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
