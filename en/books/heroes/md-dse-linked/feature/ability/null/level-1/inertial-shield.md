---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: "null"
distance: Self
effects:
    - effect: You take half the damage.
      name: Effect
    - cost: Spend 1 Discipline
      effect: The [potency](../../../../rule/character/potency.md) of one effect associated with the damage is reduced by 1 for you.
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
subtype: triggered
target: Self
trigger: You take damage.
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You take half the damage.
      name: Effect
    - cost: Spend 1 Discipline
      effect: The [potency](../../../../rule/character/potency.md) of one effect associated with the damage is reduced by 1 for you.
feature_type: ability
flavor: You intuit the course of an incoming attack, reducing its effects.
keywords:
    - Psionic
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: "null"
    distance: Self
    effects:
        - effect: You take half the damage.
          name: Effect
        - cost: Spend 1 Discipline
          effect: The [potency](../../../../rule/character/potency.md) of one effect associated with the damage is reduced by 1 for you.
    flavor: You intuit the course of an incoming attack, reducing its effects.
    keywords:
        - Psionic
    level: "1"
    name: Inertial Shield
    scc: mcdm.heroes.v1/feature.ability.null.level-1/inertial-shield
    subtype: triggered
    target: Self
    trigger: You take damage.
    type: ability
name: Inertial Shield
target: Self
trigger: You take damage.
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
