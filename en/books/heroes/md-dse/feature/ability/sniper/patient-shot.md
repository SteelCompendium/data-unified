---
action_type: Main action
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 15'
effect: If you don't take a move action this [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) deals extra damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score (your choice).
feature_type: ability
file_basename: patient-shot
file_dpath: feature/ability/sniper
flavor: Breathe... aim... wait... then strike!
item_id: patient-shot
item_name: Patient Shot
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: sniper
name: Patient Shot
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.sniper/patient-shot
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + M or A damage
tier2: 6 + M or A damage
tier3: 13 + M or A damage
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 15'
effects:
    - effect: If you don't take a move action this [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) deals extra damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score (your choice).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + M or A damage
      tier2: 6 + M or A damage
      tier3: 13 + M or A damage
feature_type: ability
flavor: Breathe... aim... wait... then strike!
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 15'
    effect: If you don't take a move action this [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) deals extra damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score (your choice).
    flavor: Breathe... aim... wait... then strike!
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: sniper
    name: Patient Shot
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.sniper/patient-shot
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage
    tier2: 6 + M or A damage
    tier3: 13 + M or A damage
    type: ability
name: Patient Shot
target: One creature
type: feature
usage: Main action
```
