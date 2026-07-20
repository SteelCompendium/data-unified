---
file_basename: corven
file_dpath: kit
flavor: With this stormwight kit, you channel your primordial ferocity into the form of a crow, becoming stealthy and quick. Corven are tied to the mountain passes and the hot winds that flow through them. This aspect is associated with the warm and fast-rising anabatic wind.
item_id: corven
item_name: Corven
name: Corven
scc: mcdm.heroes.v1/kit/corven
source: mcdm.heroes.v1
type: kit
---

With this stormwight kit, you channel your [primordial ferocity](../feature/fury/level-10/primordial-ferocity.md) into the form of a crow, becoming stealthy and quick. [Corven](corven.md) are tied to the mountain passes and the hot winds that flow through them. This aspect is associated with the warm and fast-rising anabatic wind.

```ds-feature
distance: 1 [burst](../rule/combat/burst.md)
effects:
    - effect: You can [shift](../movement/shifting.md) up to 2 squares before or after making the [power roll](../rule/dice/power-roll.md).
    - roll: Power Roll + [Agility](../rule/character/agility.md)
      tier1: 3 damage
      tier2: 6 damage
      tier3: 8 damage
feature_type: ability
flavor: Foes who try to close in around you do so at their peril.
keywords:
    - Area
    - '[Melee](../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: 1 [burst](../rule/combat/burst.md)
    effect: You can [shift](../movement/shifting.md) up to 2 squares before or after making the [power roll](../rule/dice/power-roll.md).
    flavor: Foes who try to close in around you do so at their peril.
    keywords:
        - Area
        - '[Melee](../rule/combat/melee.md)'
        - Weapon
    name: Wing Buffet
    power_roll_characteristic: '[Agility](../rule/character/agility.md)'
    subtype: signature
    target: Each enemy in the area
    tier1: 3 damage
    tier2: 6 damage
    tier3: 8 damage
    type: ability
name: Wing Buffet
target: Each enemy in the area
type: feature
usage: Main action
```
