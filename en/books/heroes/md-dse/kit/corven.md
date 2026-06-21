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

With this stormwight kit, you channel your [primordial ferocity](scc.v1:mcdm.heroes.v1/feature.fury.level-10/primordial-ferocity) into the form of a crow, becoming stealthy and quick. [Corven](scc.v1:mcdm.heroes.v1/kit/corven) are tied to the mountain passes and the hot winds that flow through them. This aspect is associated with the warm and fast-rising anabatic wind.

##### Signature Ability

###### Wing Buffet

*Foes who try to close in around you do so at their peril.*

| **Area, [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), Weapon** |               **Main action** |
|-------------------------|------------------------------:|
| **📏 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)**          | **🎯 Each enemy in the area** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 3 damage
- **12-16:** 6 damage
- **17+:** 8 damage

**Effect:** You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).

```ds-feature
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 damage
      tier2: 6 damage
      tier3: 8 damage
feature_type: ability
flavor: Foes who try to close in around you do so at their peril.
keywords:
    - Area
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: Main action
    distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares before or after making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: Foes who try to close in around you do so at their peril.
    keywords:
        - Area
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    name: Wing Buffet
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
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
