---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 9 + M damage; I < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 13 + M damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 18 + M damage; I < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
    - effect: At the end of each of your [turns](../../../../rule/combat/turn.md), a target [weakened](../../../../condition/weakened.md) this way deals holy damage equal to twice your [Presence](../../../../rule/character/presence.md) score to each enemy within 2 squares of them. Additionally, a target [weakened](../../../../condition/weakened.md) this way can't be targeted by their allies' abilities.
      name: Effect
feature_type: ability
file_basename: excommunication
file_dpath: feature/ability/censor/level-8
flavor: You curse your foe to become a bane to their allies.
item_id: excommunication
item_name: Excommunication
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "8"
name: Excommunication
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-8/excommunication
source: mcdm.heroes.v1
target: One creature
tier1: 9 + M damage; I < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
tier2: 13 + M damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
tier3: 18 + M damage; I < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 9 + M damage; I < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 13 + M damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 18 + M damage; I < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
    - effect: At the end of each of your [turns](../../../../rule/combat/turn.md), a target [weakened](../../../../condition/weakened.md) this way deals holy damage equal to twice your [Presence](../../../../rule/character/presence.md) score to each enemy within 2 squares of them. Additionally, a target [weakened](../../../../condition/weakened.md) this way can't be targeted by their allies' abilities.
      name: Effect
feature_type: ability
flavor: You curse your foe to become a bane to their allies.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: censor
    cost: 11 Wrath
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../../../../rule/character/might.md)
          tier1: 9 + M damage; I < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
          tier2: 13 + M damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
          tier3: 18 + M damage; I < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
        - effect: At the end of each of your [turns](../../../../rule/combat/turn.md), a target [weakened](../../../../condition/weakened.md) this way deals holy damage equal to twice your [Presence](../../../../rule/character/presence.md) score to each enemy within 2 squares of them. Additionally, a target [weakened](../../../../condition/weakened.md) this way can't be targeted by their allies' abilities.
          name: Effect
    flavor: You curse your foe to become a bane to their allies.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "8"
    name: Excommunication
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-8/excommunication
    target: One creature
    tier1: 9 + M damage; I < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
    tier2: 13 + M damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
    tier3: 18 + M damage; I < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
    type: ability
name: Excommunication
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
