---
action_type: Maneuver
class: beastheart
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Self
effect: 'Your companion transforms into a creature made of elemental energy. Choose a damage type from cold, fire, lightning, or sonic damage. While transformed, your companion gains the following benefits:'
feature_type: ability
file_basename: elements-unleashed
file_dpath: feature/ability/beastheart/level-6
flavor: Your companion's body becomes a bank of glowing coals, a web of arcing lightning, a cloud of rumbling thunder, or a flurry of dancing ice crystals.
item_id: elements-unleashed
item_name: Elements Unleashed
keywords:
    - Companion
    - Magic
level: "6"
name: Elements Unleashed
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/elements-unleashed
source: mcdm.beastheart.v1
spend: '2 Ferocity: You also transform.'
subclass: spark
target: Self
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Self
effects:
    - effect: 'Your companion transforms into a creature made of elemental energy. Choose a damage type from cold, fire, lightning, or sonic damage. While transformed, your companion gains the following benefits:'
    - effect: '2 Ferocity: You also transform.'
      name: Spend
feature_type: ability
flavor: Your companion's body becomes a bank of glowing coals, a web of arcing lightning, a cloud of rumbling thunder, or a flurry of dancing ice crystals.
keywords:
    - Companion
    - Magic
metadata:
    action_type: Maneuver
    class: beastheart
    cost: 9 Ferocity
    distance: Self
    effect: 'Your companion transforms into a creature made of elemental energy. Choose a damage type from cold, fire, lightning, or sonic damage. While transformed, your companion gains the following benefits:'
    flavor: Your companion's body becomes a bank of glowing coals, a web of arcing lightning, a cloud of rumbling thunder, or a flurry of dancing ice crystals.
    keywords:
        - Companion
        - Magic
    level: "6"
    name: Elements Unleashed
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/elements-unleashed
    spend: '2 Ferocity: You also transform.'
    subclass: spark
    target: Self
    type: ability
name: Elements Unleashed
target: Self
type: feature
usage: Maneuver
```
