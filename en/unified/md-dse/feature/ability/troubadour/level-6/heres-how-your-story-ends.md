---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 9 Drama
cost_amount: "9"
cost_resource: Drama
distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
feature_type: ability
file_basename: heres-how-your-story-ends
file_dpath: feature/ability/troubadour/level-6
flavor: You give away the ending of this battle, and it's not great for them.
item_id: heres-how-your-story-ends
item_name: Here's How Your Story Ends
keywords:
    - Area
    - Magic
level: "6"
name: Here's How Your Story Ends
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/heres-how-your-story-ends
source: mcdm.heroes.v1
subclass: auteur
target: Each enemy in the area
tier1: 2 psychic damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 5 psychic damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 7 psychic damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---

```ds-feature
cost: 9 Drama
distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 2 psychic damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 5 psychic damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 7 psychic damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
feature_type: ability
flavor: You give away the ending of this battle, and it's not great for them.
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    cost: 9 Drama
    distance: 5 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    flavor: You give away the ending of this battle, and it's not great for them.
    keywords:
        - Area
        - Magic
    level: "6"
    name: Here's How Your Story Ends
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-6/heres-how-your-story-ends
    subclass: auteur
    target: Each enemy in the area
    tier1: 2 psychic damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier2: 5 psychic damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier3: 7 psychic damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    type: ability
name: Here's How Your Story Ends
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
