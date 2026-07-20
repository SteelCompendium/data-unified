---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: "null"
distance: Self
effect: You take half the damage.
feature_type: ability
file_basename: inertial-shield
file_dpath: feature/ability/null/level-1
flavor: You intuit the course of an incoming attack, reducing its effects.
item_id: inertial-shield
item_name: Inertial Shield
keywords:
    - Psionic
level: "1"
name: Inertial Shield
scc: mcdm.heroes.v1/feature.ability.null.level-1/inertial-shield
source: mcdm.heroes.v1
spend: '1 Discipline: The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of one effect associated with the damage is reduced by 1 for you.'
subtype: triggered
target: Self
trigger: You take damage.
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You take half the damage.
    - effect: '1 Discipline: The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of one effect associated with the damage is reduced by 1 for you.'
      name: Spend
feature_type: ability
flavor: You intuit the course of an incoming attack, reducing its effects.
keywords:
    - Psionic
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: "null"
    distance: Self
    effect: You take half the damage.
    flavor: You intuit the course of an incoming attack, reducing its effects.
    keywords:
        - Psionic
    level: "1"
    name: Inertial Shield
    scc: mcdm.heroes.v1/feature.ability.null.level-1/inertial-shield
    spend: '1 Discipline: The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of one effect associated with the damage is reduced by 1 for you.'
    subtype: triggered
    target: Self
    trigger: You take damage.
    type: ability
name: Inertial Shield
target: Self
trigger: You take damage.
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
