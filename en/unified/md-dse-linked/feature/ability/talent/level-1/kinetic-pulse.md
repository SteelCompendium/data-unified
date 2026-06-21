---
action_type: Main action
class: talent
distance: 1 [burst](../../../../rule/combat/burst.md)
feature_type: ability
file_basename: kinetic-pulse
file_dpath: feature/ability/talent/level-1
flavor: The force of your mind hurls enemies backward.
item_id: kinetic-pulse
item_name: Kinetic Pulse
keywords:
    - Area
    - Psionic
    - Telepathy
level: "1"
name: Kinetic Pulse
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/kinetic-pulse
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 2 psychic damage
tier2: 5 psychic damage; [push](../../../../movement/forced-movement.md) 1
tier3: 7 psychic damage; [push](../../../../movement/forced-movement.md) 2
type: ability
---

```ds-feature
distance: 1 [burst](../../../../rule/combat/burst.md)
effects:
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 2 psychic damage
      tier2: 5 psychic damage; [push](../../../../movement/forced-movement.md) 1
      tier3: 7 psychic damage; [push](../../../../movement/forced-movement.md) 2
feature_type: ability
flavor: The force of your mind hurls enemies backward.
keywords:
    - Area
    - Psionic
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    distance: 1 [burst](../../../../rule/combat/burst.md)
    flavor: The force of your mind hurls enemies backward.
    keywords:
        - Area
        - Psionic
        - Telepathy
    level: "1"
    name: Kinetic Pulse
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/kinetic-pulse
    subtype: signature
    target: Each enemy in the area
    tier1: 2 psychic damage
    tier2: 5 psychic damage; [push](../../../../movement/forced-movement.md) 1
    tier3: 7 psychic damage; [push](../../../../movement/forced-movement.md) 2
    type: ability
name: Kinetic Pulse
target: Each enemy in the area
type: feature
usage: Main action
```
