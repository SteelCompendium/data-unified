---
action_type: Main action
class: beastheart
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Melee 1 or ranged 5
effect: If the target is killed by this damage, or is winded or [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) after taking this damage, you gain 2 surges.
feature_type: ability
file_basename: i-feed-on-your-pain
file_dpath: feature/ability/beastheart/level-1
flavor: Invigorated by the smell of blood, you strike a savage blow.
item_id: i-feed-on-your-pain
item_name: I Feed On Your Pain!
keywords:
    - Beastheart
    - Melee
    - Ranged
    - Strike
    - Weapon
level: "1"
name: I Feed On Your Pain!
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/i-feed-on-your-pain
source: mcdm.beastheart.v1
target: One creature
tier1: 8 + M damage
tier2: 12 + M damage
tier3: 16 + M damage; M < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Melee 1 or ranged 5
effects:
    - effect: If the target is killed by this damage, or is winded or [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) after taking this damage, you gain 2 surges.
    - roll: Power Roll + Might
      tier1: 8 + M damage
      tier2: 12 + M damage
      tier3: 16 + M damage; M < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
feature_type: ability
flavor: Invigorated by the smell of blood, you strike a savage blow.
keywords:
    - Beastheart
    - Melee
    - Ranged
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 5 Ferocity
    distance: Melee 1 or ranged 5
    effect: If the target is killed by this damage, or is winded or [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) after taking this damage, you gain 2 surges.
    flavor: Invigorated by the smell of blood, you strike a savage blow.
    keywords:
        - Beastheart
        - Melee
        - Ranged
        - Strike
        - Weapon
    level: "1"
    name: I Feed On Your Pain!
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/i-feed-on-your-pain
    target: One creature
    tier1: 8 + M damage
    tier2: 12 + M damage
    tier3: 16 + M damage; M < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    type: ability
name: I Feed On Your Pain!
target: One creature
type: feature
usage: Main action
```
