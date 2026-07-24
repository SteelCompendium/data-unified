---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 2 damage
      tier2: 5 damage
      tier3: 7 damage
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares.
      name: Effect
    - cost: Spend 2+ Drama
      effect: You can target one additional creature or object for every 2 drama spent.
feature_type: ability
file_basename: artful-flourish
file_dpath: feature/ability/troubadour/level-1
flavor: And they said practicing fencing was a waste!
item_id: artful-flourish
item_name: Artful Flourish
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Artful Flourish
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/artful-flourish
source: mcdm.heroes.v1
subtype: signature
target: Two creatures or objects
tier1: 2 damage
tier2: 5 damage
tier3: 7 damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 2 damage
      tier2: 5 damage
      tier3: 7 damage
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares.
      name: Effect
    - cost: Spend 2+ Drama
      effect: You can target one additional creature or object for every 2 drama spent.
feature_type: ability
flavor: And they said practicing fencing was a waste!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 2 damage
          tier2: 5 damage
          tier3: 7 damage
        - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 3 squares.
          name: Effect
        - cost: Spend 2+ Drama
          effect: You can target one additional creature or object for every 2 drama spent.
    flavor: And they said practicing fencing was a waste!
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Artful Flourish
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/artful-flourish
    subtype: signature
    target: Two creatures or objects
    tier1: 2 damage
    tier2: 5 damage
    tier3: 7 damage
    type: ability
name: Artful Flourish
target: Two creatures or objects
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
