---
action_type: Main action
class: elementalist
cost: 3 Essence
cost_amount: "3"
cost_resource: Essence
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: You must be touching the ground to use this ability. Additionally, you can choose a square of ground in the area that is unoccupied or is occupied by you or any ally. A pillar of earth rises out of the ground in that square, with a height in squares up to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score. The pillar can't collide with any creatures or objects, nor can it force creatures raised by it to collide with other creatures or objects.
feature_type: ability
file_basename: ripples-in-the-earth
file_dpath: feature/ability/elementalist/level-1
flavor: Like a stone was dropped into a pond, waves in the earth radiate from you.
item_id: ripples-in-the-earth
item_name: Ripples in the Earth
keywords:
    - Area
    - Earth
    - Magic
level: "1"
name: Ripples in the Earth
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/ripples-in-the-earth
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 3 damage
tier2: 5 damage
tier3: 8 damage; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---

```ds-feature
cost: 3 Essence
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: You must be touching the ground to use this ability. Additionally, you can choose a square of ground in the area that is unoccupied or is occupied by you or any ally. A pillar of earth rises out of the ground in that square, with a height in squares up to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score. The pillar can't collide with any creatures or objects, nor can it force creatures raised by it to collide with other creatures or objects.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 damage
      tier2: 5 damage
      tier3: 8 damage; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
feature_type: ability
flavor: Like a stone was dropped into a pond, waves in the earth radiate from you.
keywords:
    - Area
    - Earth
    - Magic
metadata:
    action_type: Main action
    class: elementalist
    cost: 3 Essence
    distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: You must be touching the ground to use this ability. Additionally, you can choose a square of ground in the area that is unoccupied or is occupied by you or any ally. A pillar of earth rises out of the ground in that square, with a height in squares up to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score. The pillar can't collide with any creatures or objects, nor can it force creatures raised by it to collide with other creatures or objects.
    flavor: Like a stone was dropped into a pond, waves in the earth radiate from you.
    keywords:
        - Area
        - Earth
        - Magic
    level: "1"
    name: Ripples in the Earth
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/ripples-in-the-earth
    target: Each enemy in the area
    tier1: 3 damage
    tier2: 5 damage
    tier3: 8 damage; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: Ripples in the Earth
target: Each enemy in the area
type: feature
usage: Main action
```
