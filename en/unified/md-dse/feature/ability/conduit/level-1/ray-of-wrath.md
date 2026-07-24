---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 2 + I damage
      tier2: 4 + I damage
      tier3: 6 + I damage
    - effect: You can have this ability deal holy damage.
      name: Effect
feature_type: ability
file_basename: ray-of-wrath
file_dpath: feature/ability/conduit/level-1
flavor: You unleash a blast of holy light upon your foe.
item_id: ray-of-wrath
item_name: Ray of Wrath
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Ray of Wrath
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/ray-of-wrath
source: mcdm.heroes.v1
target: One creature or object
tier1: 2 + I damage
tier2: 4 + I damage
tier3: 6 + I damage
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 2 + I damage
      tier2: 4 + I damage
      tier3: 6 + I damage
    - effect: You can have this ability deal holy damage.
      name: Effect
feature_type: ability
flavor: You unleash a blast of holy light upon your foe.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
          tier1: 2 + I damage
          tier2: 4 + I damage
          tier3: 6 + I damage
        - effect: You can have this ability deal holy damage.
          name: Effect
    flavor: You unleash a blast of holy light upon your foe.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Ray of Wrath
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/ray-of-wrath
    target: One creature or object
    tier1: 2 + I damage
    tier2: 4 + I damage
    tier3: 6 + I damage
    type: ability
name: Ray of Wrath
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
