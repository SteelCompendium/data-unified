---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 3 + P damage
      tier2: 6 + P damage
      tier3: 9 + P damage
    - effect: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by you or a willing ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
flavor: I didn't do it! What?
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Instigator
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/instigator
subtype: signature
target: One creature
tier1: 3 + P damage
tier2: 6 + P damage
tier3: 9 + P damage
type: ability
---


*I didn't do it! What?*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon**             | **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------------------|----------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**                        | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence):**

- **≤11:** 3 + P damage
- **12-16:** 6 + P damage
- **17+:** 9 + P damage

**Effect:** The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) by you or a willing ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you until the end of the target's next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
