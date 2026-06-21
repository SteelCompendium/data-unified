---
action_type: Main action
distance: '[Melee](../../../rule/combat/melee.md) 1'
feature_type: ability
file_basename: unbalancing-attack
file_dpath: feature/ability/vuken
flavor: A wild assault forces your foe onto their back.
item_id: unbalancing-attack
item_name: Unbalancing Attack
keywords:
    - '[Melee](../../../rule/combat/melee.md)'
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
kit: vuken
name: Unbalancing Attack
power_roll_characteristic: '[Might](../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.vuken/unbalancing-attack
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 4 + M damage; A < WEAK[, prone](../../../condition/prone.md)
tier2: 7 + M damage; A < AVERAGE[, prone](../../../condition/prone.md)
tier3: 9 + M damage; A < STRONG[, prone](../../../condition/prone.md)
type: ability
---

```ds-feature
distance: '[Melee](../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../rule/character/might.md)
      tier1: 4 + M damage; A < WEAK[, prone](../../../condition/prone.md)
      tier2: 7 + M damage; A < AVERAGE[, prone](../../../condition/prone.md)
      tier3: 9 + M damage; A < STRONG[, prone](../../../condition/prone.md)
feature_type: ability
flavor: A wild assault forces your foe onto their back.
keywords:
    - '[Melee](../../../rule/combat/melee.md)'
    - '[Strike](../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../../../rule/combat/melee.md) 1'
    flavor: A wild assault forces your foe onto their back.
    keywords:
        - '[Melee](../../../rule/combat/melee.md)'
        - '[Strike](../../../rule/combat/strike.md)'
        - Weapon
    kit: vuken
    name: Unbalancing Attack
    power_roll_characteristic: '[Might](../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.vuken/unbalancing-attack
    subtype: signature
    target: One creature or object
    tier1: 4 + M damage; A < WEAK[, prone](../../../condition/prone.md)
    tier2: 7 + M damage; A < AVERAGE[, prone](../../../condition/prone.md)
    tier3: 9 + M damage; A < STRONG[, prone](../../../condition/prone.md)
    type: ability
name: Unbalancing Attack
target: One creature or object
type: feature
usage: Main action
```
