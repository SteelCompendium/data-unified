---
action_type: Main action
class: beastheart
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: 3 burst
effect: While [frightened](../../../../condition/frightened.md) this way, a creature takes 10 psychic damage at the start of each of your turns.
feature_type: ability
file_basename: banshee-howl
file_dpath: feature/ability/beastheart/level-9
flavor: Your companion's howl, screech, roar, or psychic emanation presages death to those who hear it.
item_id: banshee-howl
item_name: Banshee Howl
keywords:
    - Area
    - Companion
    - Magic
level: "9"
name: Banshee Howl
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/banshee-howl
source: mcdm.beastheart.v1
spend: '1 Ferocity: This ability also affects a 3 burst originating from you. An enemy in both areas is only affected once.'
subclass: guardian
target: Each enemy in the area
tier1: 5 sonic damage; I < WEAK [frightened](../../../../condition/frightened.md) (save ends)
tier2: 10 sonic damage; I < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
tier3: 15 sonic damage; I < STRONG [frightened](../../../../condition/frightened.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: 3 burst
effects:
    - effect: While [frightened](../../../../condition/frightened.md) this way, a creature takes 10 psychic damage at the start of each of your turns.
    - roll: Power Roll + Intuition
      tier1: 5 sonic damage; I < WEAK [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 10 sonic damage; I < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 15 sonic damage; I < STRONG [frightened](../../../../condition/frightened.md) (save ends)
    - effect: '1 Ferocity: This ability also affects a 3 burst originating from you. An enemy in both areas is only affected once.'
      name: Spend
feature_type: ability
flavor: Your companion's howl, screech, roar, or psychic emanation presages death to those who hear it.
keywords:
    - Area
    - Companion
    - Magic
metadata:
    action_type: Main action
    class: beastheart
    cost: 11 Ferocity
    distance: 3 burst
    effect: While [frightened](../../../../condition/frightened.md) this way, a creature takes 10 psychic damage at the start of each of your turns.
    flavor: Your companion's howl, screech, roar, or psychic emanation presages death to those who hear it.
    keywords:
        - Area
        - Companion
        - Magic
    level: "9"
    name: Banshee Howl
    power_roll_characteristic: Intuition
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/banshee-howl
    spend: '1 Ferocity: This ability also affects a 3 burst originating from you. An enemy in both areas is only affected once.'
    subclass: guardian
    target: Each enemy in the area
    tier1: 5 sonic damage; I < WEAK [frightened](../../../../condition/frightened.md) (save ends)
    tier2: 10 sonic damage; I < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
    tier3: 15 sonic damage; I < STRONG [frightened](../../../../condition/frightened.md) (save ends)
    type: ability
name: Banshee Howl
target: Each enemy in the area
type: feature
usage: Main action
```
