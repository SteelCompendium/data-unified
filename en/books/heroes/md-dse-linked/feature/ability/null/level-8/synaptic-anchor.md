---
action_type: Free [triggered](../../../../rule/combat/triggered-action.md)
class: "null"
cost: 11 Discipline
cost_amount: "11"
cost_resource: Discipline
distance: Self; see below
effect: The target takes half the damage, and if the triggering creature has I < AVERAGE, they are [dazed](../../../../condition/dazed.md) (save ends). While the triggering creature is [dazed](../../../../condition/dazed.md) this way, they take psychic damage equal to your [Intuition](../../../../rule/character/intuition.md) score whenever they use a main action.
feature_type: ability
file_basename: synaptic-anchor
file_dpath: feature/ability/null/level-8
flavor: You disrupt an enemy's strike and create a [feedback loop](../../talent/level-1/feedback-loop.md) in their mind, preventing them from focusing on future attacks.
item_id: synaptic-anchor
item_name: Synaptic Anchor
keywords:
    - Psionic
level: "8"
name: Synaptic Anchor
scc: mcdm.heroes.v1/feature.ability.null.level-8/synaptic-anchor
source: mcdm.heroes.v1
subtype: triggered
target: Self or one creature
trigger: The target takes damage from another creature's ability while in the area of your [Null Field](../../../null/level-1/null-field.md) ability.
type: ability
---

```ds-feature
cost: 11 Discipline
distance: Self; see below
effects:
    - effect: The target takes half the damage, and if the triggering creature has I < AVERAGE, they are [dazed](../../../../condition/dazed.md) (save ends). While the triggering creature is [dazed](../../../../condition/dazed.md) this way, they take psychic damage equal to your [Intuition](../../../../rule/character/intuition.md) score whenever they use a main action.
feature_type: ability
flavor: You disrupt an enemy's strike and create a [feedback loop](../../talent/level-1/feedback-loop.md) in their mind, preventing them from focusing on future attacks.
keywords:
    - Psionic
metadata:
    action_type: Free [triggered](../../../../rule/combat/triggered-action.md)
    class: "null"
    cost: 11 Discipline
    distance: Self; see below
    effect: The target takes half the damage, and if the triggering creature has I < AVERAGE, they are [dazed](../../../../condition/dazed.md) (save ends). While the triggering creature is [dazed](../../../../condition/dazed.md) this way, they take psychic damage equal to your [Intuition](../../../../rule/character/intuition.md) score whenever they use a main action.
    flavor: You disrupt an enemy's strike and create a [feedback loop](../../talent/level-1/feedback-loop.md) in their mind, preventing them from focusing on future attacks.
    keywords:
        - Psionic
    level: "8"
    name: Synaptic Anchor
    scc: mcdm.heroes.v1/feature.ability.null.level-8/synaptic-anchor
    subtype: triggered
    target: Self or one creature
    trigger: The target takes damage from another creature's ability while in the area of your [Null Field](../../../null/level-1/null-field.md) ability.
    type: ability
name: Synaptic Anchor
target: Self or one creature
trigger: The target takes damage from another creature's ability while in the area of your [Null Field](../../../null/level-1/null-field.md) ability.
type: feature
usage: Free [triggered](../../../../rule/combat/triggered-action.md)
```
