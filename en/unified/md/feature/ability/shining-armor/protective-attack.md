---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + M or A damage
      tier2: 8 + M or A damage
      tier3: 11 + M or A damage
    - effect: The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
flavor: The strength of your assault makes it impossible for your foe to ignore you.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: shining-armor
name: Protective Attack
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shining-armor/protective-attack
subtype: signature
target: One creature
tier1: 5 + M or A damage
tier2: 8 + M or A damage
tier3: 11 + M or A damage
type: ability
---

*The strength of your assault makes it impossible for your foe to ignore you.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 5 + M or A damage
- **12-16:** 8 + M or A damage
- **17+:** 11 + M or A damage

**Effect:** The target is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
