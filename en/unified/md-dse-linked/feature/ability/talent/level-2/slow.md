---
action_type: '[Maneuver](../../../../rule/combat/turn.md)'
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: The target's [speed](../../../../rule/character/speed.md) is halved (save ends), or if P < WEAK, the target is [slowed](../../../../condition/slowed.md) (save ends).
      tier2: The target is [slowed](../../../../condition/slowed.md) (save ends), or if P < AVERAGE, the target's [speed](../../../../rule/character/speed.md) is 0 (save ends).
      tier3: The target is [slowed](../../../../condition/slowed.md) (save ends), or if P < STRONG, the target's [speed](../../../../rule/character/speed.md) is 0 (save ends).
    - effect: A target can't use [triggered actions](../../../../rule/combat/triggered-action.md) while their [speed](../../../../rule/character/speed.md) is reduced this way.
      name: Effect
    - effect: The [potency](../../../../rule/character/potency.md) of this ability increases by 1 and you take 1d6 damage. At the start of each [combat round](../../../../rule/combat/combat-round.md) while any target is affected by this ability, you take 1d6 damage. You can end the effect on all affected targets at any time (no action required).
      name: Strained
feature_type: ability
file_basename: slow
file_dpath: feature/ability/talent/level-2
flavor: Perhaps they wonder why everyone else is moving so quickly?
item_id: slow
item_name: Slow
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "2"
name: Slow
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-2/slow
source: mcdm.heroes.v1
subclass: chronopathy
target: Three creatures or objects
tier1: The target's [speed](../../../../rule/character/speed.md) is halved (save ends), or if P < WEAK, the target is [slowed](../../../../condition/slowed.md) (save ends).
tier2: The target is [slowed](../../../../condition/slowed.md) (save ends), or if P < AVERAGE, the target's [speed](../../../../rule/character/speed.md) is 0 (save ends).
tier3: The target is [slowed](../../../../condition/slowed.md) (save ends), or if P < STRONG, the target's [speed](../../../../rule/character/speed.md) is 0 (save ends).
type: ability
---

```ds-feature
cost: 5 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: The target's [speed](../../../../rule/character/speed.md) is halved (save ends), or if P < WEAK, the target is [slowed](../../../../condition/slowed.md) (save ends).
      tier2: The target is [slowed](../../../../condition/slowed.md) (save ends), or if P < AVERAGE, the target's [speed](../../../../rule/character/speed.md) is 0 (save ends).
      tier3: The target is [slowed](../../../../condition/slowed.md) (save ends), or if P < STRONG, the target's [speed](../../../../rule/character/speed.md) is 0 (save ends).
    - effect: A target can't use [triggered actions](../../../../rule/combat/triggered-action.md) while their [speed](../../../../rule/character/speed.md) is reduced this way.
      name: Effect
    - effect: The [potency](../../../../rule/character/potency.md) of this ability increases by 1 and you take 1d6 damage. At the start of each [combat round](../../../../rule/combat/combat-round.md) while any target is affected by this ability, you take 1d6 damage. You can end the effect on all affected targets at any time (no action required).
      name: Strained
feature_type: ability
flavor: Perhaps they wonder why everyone else is moving so quickly?
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Maneuver](../../../../rule/combat/turn.md)'
    class: talent
    cost: 5 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
          tier1: The target's [speed](../../../../rule/character/speed.md) is halved (save ends), or if P < WEAK, the target is [slowed](../../../../condition/slowed.md) (save ends).
          tier2: The target is [slowed](../../../../condition/slowed.md) (save ends), or if P < AVERAGE, the target's [speed](../../../../rule/character/speed.md) is 0 (save ends).
          tier3: The target is [slowed](../../../../condition/slowed.md) (save ends), or if P < STRONG, the target's [speed](../../../../rule/character/speed.md) is 0 (save ends).
        - effect: A target can't use [triggered actions](../../../../rule/combat/triggered-action.md) while their [speed](../../../../rule/character/speed.md) is reduced this way.
          name: Effect
        - effect: The [potency](../../../../rule/character/potency.md) of this ability increases by 1 and you take 1d6 damage. At the start of each [combat round](../../../../rule/combat/combat-round.md) while any target is affected by this ability, you take 1d6 damage. You can end the effect on all affected targets at any time (no action required).
          name: Strained
    flavor: Perhaps they wonder why everyone else is moving so quickly?
    keywords:
        - Chronopathy
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "2"
    name: Slow
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/slow
    subclass: chronopathy
    target: Three creatures or objects
    tier1: The target's [speed](../../../../rule/character/speed.md) is halved (save ends), or if P < WEAK, the target is [slowed](../../../../condition/slowed.md) (save ends).
    tier2: The target is [slowed](../../../../condition/slowed.md) (save ends), or if P < AVERAGE, the target's [speed](../../../../rule/character/speed.md) is 0 (save ends).
    tier3: The target is [slowed](../../../../condition/slowed.md) (save ends), or if P < STRONG, the target's [speed](../../../../rule/character/speed.md) is 0 (save ends).
    type: ability
name: Slow
target: Three creatures or objects
type: feature
usage: '[Maneuver](../../../../rule/combat/turn.md)'
```
