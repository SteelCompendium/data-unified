---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 5 + P damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 9 + P damage; I < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 12 + P damage; I < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
    - effect: While the target is [slowed](../../../../condition/slowed.md) this way, each of their allies who starts their [turn](../../../../rule/combat/turn.md) within 5 squares of them must use a [free maneuver](../../../../rule/combat/free-maneuver.md) to make a [free strike](../../../common/main-actions/free-strike.md) against the target. Additionally, while the target is [slowed](../../../../condition/slowed.md) this way, each of their allies within 5 squares of them who can make a triggered [free strike](../../../common/main-actions/free-strike.md) against a different creature must make the [free strike](../../../common/main-actions/free-strike.md) against the target instead.
      name: Effect
feature_type: ability
file_basename: your-allies-turn-on-you
file_dpath: feature/ability/censor/level-8
flavor: You [turn](../../../../rule/combat/turn.md) your enemies' ire to the target.
item_id: your-allies-turn-on-you
item_name: Your Allies Turn on You!
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "8"
name: Your Allies Turn on You!
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-8/your-allies-turn-on-you
source: mcdm.heroes.v1
target: One creature
tier1: 5 + P damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
tier2: 9 + P damage; I < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
tier3: 12 + P damage; I < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Wrath
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 5 + P damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 9 + P damage; I < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 12 + P damage; I < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
    - effect: While the target is [slowed](../../../../condition/slowed.md) this way, each of their allies who starts their [turn](../../../../rule/combat/turn.md) within 5 squares of them must use a [free maneuver](../../../../rule/combat/free-maneuver.md) to make a [free strike](../../../common/main-actions/free-strike.md) against the target. Additionally, while the target is [slowed](../../../../condition/slowed.md) this way, each of their allies within 5 squares of them who can make a triggered [free strike](../../../common/main-actions/free-strike.md) against a different creature must make the [free strike](../../../common/main-actions/free-strike.md) against the target instead.
      name: Effect
feature_type: ability
flavor: You [turn](../../../../rule/combat/turn.md) your enemies' ire to the target.
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: censor
    cost: 11 Wrath
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
          tier1: 5 + P damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
          tier2: 9 + P damage; I < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
          tier3: 12 + P damage; I < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
        - effect: While the target is [slowed](../../../../condition/slowed.md) this way, each of their allies who starts their [turn](../../../../rule/combat/turn.md) within 5 squares of them must use a [free maneuver](../../../../rule/combat/free-maneuver.md) to make a [free strike](../../../common/main-actions/free-strike.md) against the target. Additionally, while the target is [slowed](../../../../condition/slowed.md) this way, each of their allies within 5 squares of them who can make a triggered [free strike](../../../common/main-actions/free-strike.md) against a different creature must make the [free strike](../../../common/main-actions/free-strike.md) against the target instead.
          name: Effect
    flavor: You [turn](../../../../rule/combat/turn.md) your enemies' ire to the target.
    keywords:
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "8"
    name: Your Allies Turn on You!
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-8/your-allies-turn-on-you
    target: One creature
    tier1: 5 + P damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 9 + P damage; I < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
    tier3: 12 + P damage; I < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
    type: ability
name: Your Allies Turn on You!
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
