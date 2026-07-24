---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 11 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 9 + M damage; I < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 13 + M damage; I < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 18 + M damage; I < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    - effect: At the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), a target [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) this way deals holy damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score to each enemy within 2 squares of them. Additionally, a target [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) this way can't be targeted by their allies' abilities.
      name: Effect
flavor: You curse your foe to become a bane to their allies.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: Excommunication
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-8/excommunication
target: One creature
tier1: 9 + M damage; I < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 13 + M damage; I < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 18 + M damage; I < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---


*You curse your foe to become a bane to their allies.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 9 + M damage; I < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
- **12-16:** 13 + M damage; I < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
- **17+:** 18 + M damage; I < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)

**Effect:** At the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), a target [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) this way deals holy damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score to each enemy within 2 squares of them. Additionally, a target [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) this way can't be targeted by their allies' abilities.
