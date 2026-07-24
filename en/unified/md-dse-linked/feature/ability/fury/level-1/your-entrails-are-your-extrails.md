---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: fury
cost: 3 Ferocity
cost_amount: "3"
cost_resource: Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 3 + M damage; M < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier2: 5 + M damage; M < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier3: 8 + M damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    - effect: While [bleeding](../../../../condition/bleeding.md) this way, the target takes damage equal to your [Might](../../../../rule/character/might.md) score at the end of each of your [turns](../../../../rule/combat/turn.md).
      name: Effect
feature_type: ability
file_basename: your-entrails-are-your-extrails
file_dpath: feature/ability/fury/level-1
flavor: Hard for them to fight when they're busy holding in their giblets.
item_id: your-entrails-are-your-extrails
item_name: Your Entrails Are Your Extrails!
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Your Entrails Are Your Extrails!
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/your-entrails-are-your-extrails
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + M damage; M < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
tier2: 5 + M damage; M < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
tier3: 8 + M damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
type: ability
---

```ds-feature
cost: 3 Ferocity
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 3 + M damage; M < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier2: 5 + M damage; M < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier3: 8 + M damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    - effect: While [bleeding](../../../../condition/bleeding.md) this way, the target takes damage equal to your [Might](../../../../rule/character/might.md) score at the end of each of your [turns](../../../../rule/combat/turn.md).
      name: Effect
feature_type: ability
flavor: Hard for them to fight when they're busy holding in their giblets.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: fury
    cost: 3 Ferocity
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../../../../rule/character/might.md)
          tier1: 3 + M damage; M < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
          tier2: 5 + M damage; M < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
          tier3: 8 + M damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
        - effect: While [bleeding](../../../../condition/bleeding.md) this way, the target takes damage equal to your [Might](../../../../rule/character/might.md) score at the end of each of your [turns](../../../../rule/combat/turn.md).
          name: Effect
    flavor: Hard for them to fight when they're busy holding in their giblets.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Your Entrails Are Your Extrails!
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/your-entrails-are-your-extrails
    target: One creature or object
    tier1: 3 + M damage; M < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
    tier2: 5 + M damage; M < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
    tier3: 8 + M damage; M < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    type: ability
name: Your Entrails Are Your Extrails!
target: One creature or object
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
