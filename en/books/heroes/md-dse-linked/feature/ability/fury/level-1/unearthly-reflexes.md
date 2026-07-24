---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: fury
distance: Self
effects:
    - effect: You take half the damage from the triggering effect and can [shift](../../../../movement/shifting.md) up to a number of squares equal to your [Agility](../../../../rule/character/agility.md) score.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: If the damage has any [potency](../../../../rule/character/potency.md) effects associated with it, the [potency](../../../../rule/character/potency.md) is reduced by 1 for you.
feature_type: ability
file_basename: unearthly-reflexes
file_dpath: feature/ability/fury/level-1
flavor: You are as elusive as a hummingbird.
item_id: unearthly-reflexes
item_name: Unearthly Reflexes
keywords: []
level: "1"
name: Unearthly Reflexes
scc: mcdm.heroes.v1/feature.ability.fury.level-1/unearthly-reflexes
source: mcdm.heroes.v1
subclass: reaver
subtype: triggered
target: Self
trigger: You take damage.
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You take half the damage from the triggering effect and can [shift](../../../../movement/shifting.md) up to a number of squares equal to your [Agility](../../../../rule/character/agility.md) score.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: If the damage has any [potency](../../../../rule/character/potency.md) effects associated with it, the [potency](../../../../rule/character/potency.md) is reduced by 1 for you.
feature_type: ability
flavor: You are as elusive as a hummingbird.
keywords: []
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: fury
    distance: Self
    effects:
        - effect: You take half the damage from the triggering effect and can [shift](../../../../movement/shifting.md) up to a number of squares equal to your [Agility](../../../../rule/character/agility.md) score.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: If the damage has any [potency](../../../../rule/character/potency.md) effects associated with it, the [potency](../../../../rule/character/potency.md) is reduced by 1 for you.
    flavor: You are as elusive as a hummingbird.
    keywords: []
    level: "1"
    name: Unearthly Reflexes
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/unearthly-reflexes
    subclass: reaver
    subtype: triggered
    target: Self
    trigger: You take damage.
    type: ability
name: Unearthly Reflexes
target: Self
trigger: You take damage.
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
