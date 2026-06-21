---
action_type: Main action
class: talent
cost: 7 Clarity
cost_amount: "7"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: The target takes a [bane](../../../../rule/dice/bane.md) on [Presence](../../../../rule/character/presence.md) [tests](../../../../rule/test/test.md) until the end of the encounter.
feature_type: ability
file_basename: soul-burn
file_dpath: feature/ability/talent/level-3
flavor: You blast their soul out of their body, leaving it to helplessly float back to a weakened husk.
item_id: soul-burn
item_name: Soul Burn
keywords:
    - Animapathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
level: "3"
name: Soul Burn
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-3/soul-burn
source: mcdm.heroes.v1
target: One creature
tier1: 6 + P damage; P < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
tier2: 10 + P damage; P < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
tier3: 14 + P damage; P < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
cost: 7 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The target takes a [bane](../../../../rule/dice/bane.md) on [Presence](../../../../rule/character/presence.md) [tests](../../../../rule/test/test.md) until the end of the encounter.
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 6 + P damage; P < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
      tier2: 10 + P damage; P < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
      tier3: 14 + P damage; P < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: You blast their soul out of their body, leaving it to helplessly float back to a weakened husk.
keywords:
    - Animapathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
metadata:
    action_type: Main action
    class: talent
    cost: 7 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: The target takes a [bane](../../../../rule/dice/bane.md) on [Presence](../../../../rule/character/presence.md) [tests](../../../../rule/test/test.md) until the end of the encounter.
    flavor: You blast their soul out of their body, leaving it to helplessly float back to a weakened husk.
    keywords:
        - Animapathy
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - Strike
    level: "3"
    name: Soul Burn
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-3/soul-burn
    target: One creature
    tier1: 6 + P damage; P < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
    tier2: 10 + P damage; P < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
    tier3: 14 + P damage; P < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: Soul Burn
target: One creature
type: feature
usage: Main action
```
