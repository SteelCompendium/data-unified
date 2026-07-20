---
file_basename: raden
file_dpath: kit
flavor: With this stormwight kit, you channel your primordial ferocity into the form of a rat, becoming mobile and elusive. Raden are associated with the wild nature of the rat, before cities became their habitat. This aspect is associated with the rat flood—a surge of corrupted water that draws forth hordes of rats.
item_id: raden
item_name: Raden
name: Raden
scc: mcdm.heroes.v1/kit/raden
source: mcdm.heroes.v1
type: kit
---

With this stormwight kit, you channel your [primordial ferocity](../feature/fury/level-10/primordial-ferocity.md) into the form of a rat, becoming mobile and elusive. [Raden](raden.md) are associated with the wild nature of the rat, before cities became their habitat. This aspect is associated with the rat flood—a surge of corrupted water that draws forth hordes of rats.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - effect: You can [shift](../movement/shifting.md) up to the same number of squares that you [pushed](../movement/forced-movement.md) the target.
    - roll: Power Roll + [Agility](../rule/character/agility.md)
      tier1: 4 + A damage
      tier2: 7 + A damage; [push](../movement/forced-movement.md) 1
      tier3: 9 + A damage; [push](../movement/forced-movement.md) 2
feature_type: ability
flavor: Your enemies try in vain to fall back from your pouncing attack.
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 1'
    effect: You can [shift](../movement/shifting.md) up to the same number of squares that you [pushed](../movement/forced-movement.md) the target.
    flavor: Your enemies try in vain to fall back from your pouncing attack.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Driving Pounce
    power_roll_characteristic: '[Agility](../rule/character/agility.md)'
    subtype: signature
    target: One creature or object
    tier1: 4 + A damage
    tier2: 7 + A damage; [push](../movement/forced-movement.md) 1
    tier3: 9 + A damage; [push](../movement/forced-movement.md) 2
    type: ability
name: Driving Pounce
target: One creature or object
type: feature
usage: Main action
```
