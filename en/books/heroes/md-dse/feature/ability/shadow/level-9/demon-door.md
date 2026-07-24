---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
cost: 11 Insight
cost_amount: "11"
cost_resource: Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 3'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 13 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 18 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 25 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    - effect: On a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit), the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the demon and [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) through the portal before it closes, never to be seen again.
      name: Effect
feature_type: ability
file_basename: demon-door
file_dpath: feature/ability/shadow/level-9
flavor: You create a temporary portal to allow a massive demonic hand to reach through.
item_id: demon-door
item_name: Demon Door
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: Demon Door
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-9/demon-door
source: mcdm.heroes.v1
subclass: black-ash
target: One creature
tier1: 13 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
tier2: 18 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
tier3: 25 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
type: ability
---

```ds-feature
cost: 11 Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 3'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 13 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      tier2: 18 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      tier3: 25 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    - effect: On a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit), the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the demon and [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) through the portal before it closes, never to be seen again.
      name: Effect
feature_type: ability
flavor: You create a temporary portal to allow a massive demonic hand to reach through.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: shadow
    cost: 11 Insight
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 3'
    effects:
        - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 13 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier2: 18 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
          tier3: 25 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
        - effect: On a [critical hit](scc.v1:mcdm.heroes.v1/rule.combat/critical-hit), the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the demon and [pulled](scc.v1:mcdm.heroes.v1/movement/forced-movement) through the portal before it closes, never to be seen again.
          name: Effect
    flavor: You create a temporary portal to allow a massive demonic hand to reach through.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "9"
    name: Demon Door
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-9/demon-door
    subclass: black-ash
    target: One creature
    tier1: 13 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
    tier2: 18 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
    tier3: 25 + A corruption damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 7
    type: ability
name: Demon Door
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
