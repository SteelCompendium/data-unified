---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: fury
distance: Self
effect: You take half the damage from the triggering effect and can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to a number of squares equal to your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score.
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
spend: '1 Ferocity: If the damage has any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effects associated with it, the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) is reduced by 1 for you.'
subclass: reaver
subtype: triggered
target: Self
trigger: You take damage.
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You take half the damage from the triggering effect and can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to a number of squares equal to your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score.
    - effect: '1 Ferocity: If the damage has any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effects associated with it, the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) is reduced by 1 for you.'
      name: Spend
feature_type: ability
flavor: You are as elusive as a hummingbird.
keywords: []
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: fury
    distance: Self
    effect: You take half the damage from the triggering effect and can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to a number of squares equal to your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score.
    flavor: You are as elusive as a hummingbird.
    keywords: []
    level: "1"
    name: Unearthly Reflexes
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/unearthly-reflexes
    spend: '1 Ferocity: If the damage has any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effects associated with it, the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) is reduced by 1 for you.'
    subclass: reaver
    subtype: triggered
    target: Self
    trigger: You take damage.
    type: ability
name: Unearthly Reflexes
target: Self
trigger: You take damage.
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
