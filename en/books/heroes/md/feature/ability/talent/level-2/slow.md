---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 5 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: The target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is halved (save ends), or if P < WEAK, the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends).
      tier2: The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < AVERAGE, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).
      tier3: The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < STRONG, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).
    - effect: A target can't use [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) while their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is reduced this way.
      name: Effect
    - effect: The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of this ability increases by 1 and you take 1d6 damage. At the start of each [combat round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) while any target is affected by this ability, you take 1d6 damage. You can end the effect on all affected targets at any time (no action required).
      name: Strained
flavor: Perhaps they wonder why everyone else is moving so quickly?
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Slow
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.talent.level-2/slow
subclass: chronopathy
target: Three creatures or objects
tier1: The target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is halved (save ends), or if P < WEAK, the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends).
tier2: The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < AVERAGE, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).
tier3: The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < STRONG, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).
type: ability
---


*Perhaps they wonder why everyone else is moving so quickly?*

| **Chronopathy, Psionic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)** |                      **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------------|----------------------------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**                 | **🎯 Three creatures or objects** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** The target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is halved (save ends), or if P < WEAK, the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends).
- **12-16:** The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < AVERAGE, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).
- **17+:** The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < STRONG, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).

**Effect:** A target can't use [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) while their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is reduced this way.

**Strained:** The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of this ability increases by 1 and you take 1d6 damage. At the start of each [combat round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) while any target is affected by this ability, you take 1d6 damage. You can end the effect on all affected targets at any time (no action required).
