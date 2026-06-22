---
action_type: Triggered
class: talent
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The target takes psychic damage equal to half the triggering damage.
feature_type: ability
file_basename: feedback-loop
file_dpath: feature/ability/talent/level-1
flavor: Creating a brief psychic link between an enemy and their target gives that foe a taste of their own medicine.
item_id: feedback-loop
item_name: Feedback Loop
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Feedback Loop
scc: mcdm.heroes.v1/feature.ability.talent.level-1/feedback-loop
source: mcdm.heroes.v1
subclass: telepathy
subtype: triggered
target: One creature
trigger: The target deals damage to an ally.
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target takes psychic damage equal to half the triggering damage.
feature_type: ability
flavor: Creating a brief psychic link between an enemy and their target gives that foe a taste of their own medicine.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Triggered
    class: talent
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The target takes psychic damage equal to half the triggering damage.
    flavor: Creating a brief psychic link between an enemy and their target gives that foe a taste of their own medicine.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Feedback Loop
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/feedback-loop
    subclass: telepathy
    subtype: triggered
    target: One creature
    trigger: The target deals damage to an ally.
    type: ability
name: Feedback Loop
target: One creature
trigger: The target deals damage to an ally.
type: feature
usage: Triggered
```
