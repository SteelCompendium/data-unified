---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: 4 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), at the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) each creature in the area up to a number of squares equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score. This [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) for your allies.
feature_type: ability
file_basename: aura-of-souls
file_dpath: feature/ability/conduit/level-6
flavor: A whirlwind of souls of the dead flies around you at your command.
item_id: aura-of-souls
item_name: Aura of Souls
keywords:
    - Area
    - Magic
level: "6"
name: Aura of Souls
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/aura-of-souls
source: mcdm.heroes.v1
subclass: death
target: Each creature in the area
type: ability
---

```ds-feature
cost: 9 Piety
distance: 4 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
effects:
    - effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), at the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) each creature in the area up to a number of squares equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score. This [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) for your allies.
feature_type: ability
flavor: A whirlwind of souls of the dead flies around you at your command.
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 9 Piety
    distance: 4 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
    effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), at the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) each creature in the area up to a number of squares equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score. This [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) for your allies.
    flavor: A whirlwind of souls of the dead flies around you at your command.
    keywords:
        - Area
        - Magic
    level: "6"
    name: Aura of Souls
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/aura-of-souls
    subclass: death
    target: Each creature in the area
    type: ability
name: Aura of Souls
target: Each creature in the area
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
