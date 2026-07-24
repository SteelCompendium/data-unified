---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + M or A damage
      tier2: 8 + M or A damage; you can swap places with the target
      tier3: 11 + M or A damage; you can swap places with the target
    - effect: If you obtain a tier 2 or tier 3 outcome and can't swap places with the target because one or both of you is too big to fit into the swapped space, you both remain in your original spaces and the target takes 1 extra damage.
      name: Effect
feature_type: ability
file_basename: battle-grace
file_dpath: feature/ability/martial-artist
flavor: You feint to move your enemies into perfect position.
item_id: battle-grace
item_name: Battle Grace
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: martial-artist
name: Battle Grace
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.martial-artist/battle-grace
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 5 + M or A damage
tier2: 8 + M or A damage; you can swap places with the target
tier3: 11 + M or A damage; you can swap places with the target
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 5 + M or A damage
      tier2: 8 + M or A damage; you can swap places with the target
      tier3: 11 + M or A damage; you can swap places with the target
    - effect: If you obtain a tier 2 or tier 3 outcome and can't swap places with the target because one or both of you is too big to fit into the swapped space, you both remain in your original spaces and the target takes 1 extra damage.
      name: Effect
feature_type: ability
flavor: You feint to move your enemies into perfect position.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 5 + M or A damage
          tier2: 8 + M or A damage; you can swap places with the target
          tier3: 11 + M or A damage; you can swap places with the target
        - effect: If you obtain a tier 2 or tier 3 outcome and can't swap places with the target because one or both of you is too big to fit into the swapped space, you both remain in your original spaces and the target takes 1 extra damage.
          name: Effect
    flavor: You feint to move your enemies into perfect position.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: martial-artist
    name: Battle Grace
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.martial-artist/battle-grace
    subtype: signature
    target: One creature
    tier1: 5 + M or A damage
    tier2: 8 + M or A damage; you can swap places with the target
    tier3: 11 + M or A damage; you can swap places with the target
    type: ability
name: Battle Grace
target: One creature
type: feature
usage: Main action
```
