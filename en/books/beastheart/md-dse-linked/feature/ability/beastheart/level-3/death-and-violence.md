---
action_type: Triggered Action
class: beastheart
cost: 7 Ferocity
cost_amount: "7"
cost_resource: Ferocity
distance: Ranged 10
effect: 'The target dies. You [teleport](../../../../movement/teleport.md) to the target''s space, [shift](../../../../movement/shifting.md) up to a number of squares equal to your Might score, and can then make a melee free strike. You then make the following power roll, targeting each enemy within 5 squares of the target:'
feature_type: ability
file_basename: death-and-violence
file_dpath: feature/ability/beastheart/level-3
flavor: You leap from your foe's corpse.
item_id: death-and-violence
item_name: Death and Violence
keywords:
    - Beastheart
    - Magic
    - Ranged
level: "3"
name: Death and Violence
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-3/death-and-violence
source: mcdm.beastheart.v1
target: One creature
tier1: P < WEAK [frightened](../../../../condition/frightened.md) (save ends)
tier2: 4 psychic damage; P < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
tier3: 8 psychic damage; P < STRONG [frightened](../../../../condition/frightened.md) (save ends)
trigger: Your companion uses an ability that reduces the target to 0 Stamina.
type: ability
---

```ds-feature
cost: 7 Ferocity
distance: Ranged 10
effects:
    - effect: 'The target dies. You [teleport](../../../../movement/teleport.md) to the target''s space, [shift](../../../../movement/shifting.md) up to a number of squares equal to your Might score, and can then make a melee free strike. You then make the following power roll, targeting each enemy within 5 squares of the target:'
    - roll: Power Roll + Might
      tier1: P < WEAK [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 4 psychic damage; P < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 8 psychic damage; P < STRONG [frightened](../../../../condition/frightened.md) (save ends)
feature_type: ability
flavor: You leap from your foe's corpse.
keywords:
    - Beastheart
    - Magic
    - Ranged
metadata:
    action_type: Triggered Action
    class: beastheart
    cost: 7 Ferocity
    distance: Ranged 10
    effect: 'The target dies. You [teleport](../../../../movement/teleport.md) to the target''s space, [shift](../../../../movement/shifting.md) up to a number of squares equal to your Might score, and can then make a melee free strike. You then make the following power roll, targeting each enemy within 5 squares of the target:'
    flavor: You leap from your foe's corpse.
    keywords:
        - Beastheart
        - Magic
        - Ranged
    level: "3"
    name: Death and Violence
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-3/death-and-violence
    target: One creature
    tier1: P < WEAK [frightened](../../../../condition/frightened.md) (save ends)
    tier2: 4 psychic damage; P < AVERAGE [frightened](../../../../condition/frightened.md) (save ends)
    tier3: 8 psychic damage; P < STRONG [frightened](../../../../condition/frightened.md) (save ends)
    trigger: Your companion uses an ability that reduces the target to 0 Stamina.
    type: ability
name: Death and Violence
target: One creature
trigger: Your companion uses an ability that reduces the target to 0 Stamina.
type: feature
usage: Triggered Action
```
