---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 13 + M holy damage
      tier2: 19 + M holy damage
      tier3: 26 + M holy damage
    - effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), the target has [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 10.
      name: Effect
feature_type: ability
file_basename: apostate
file_dpath: feature/ability/censor/level-9
flavor: You channel holy energy to seal an enemy's fate.
item_id: apostate
item_name: Apostate
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: Apostate
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-9/apostate
source: mcdm.heroes.v1
subclass: paragon
target: One creature
tier1: 13 + M holy damage
tier2: 19 + M holy damage
tier3: 26 + M holy damage
type: ability
---

```ds-feature
cost: 11 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 13 + M holy damage
      tier2: 19 + M holy damage
      tier3: 26 + M holy damage
    - effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), the target has [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 10.
      name: Effect
feature_type: ability
flavor: You channel holy energy to seal an enemy's fate.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 11 Wrath
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 13 + M holy damage
          tier2: 19 + M holy damage
          tier3: 26 + M holy damage
        - effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), the target has [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 10.
          name: Effect
    flavor: You channel holy energy to seal an enemy's fate.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "9"
    name: Apostate
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-9/apostate
    subclass: paragon
    target: One creature
    tier1: 13 + M holy damage
    tier2: 19 + M holy damage
    tier3: 26 + M holy damage
    type: ability
name: Apostate
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
