---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 3 Wrath
cost_amount: "3"
cost_resource: Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) to allow yourself or one ally within 10 squares to regain [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
feature_type: ability
file_basename: the-gods-punish-and-defend
file_dpath: feature/ability/censor/level-1
flavor: You channel holy energy to smite a foe and heal an ally.
item_id: the-gods-punish-and-defend
item_name: The Gods Punish and Defend
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: The Gods Punish and Defend
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/the-gods-punish-and-defend
source: mcdm.heroes.v1
target: One creature or object
tier1: 5 + M holy damage
tier2: 8 + M holy damage
tier3: 11 + M holy damage
type: ability
---

```ds-feature
cost: 3 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) to allow yourself or one ally within 10 squares to regain [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 5 + M holy damage
      tier2: 8 + M holy damage
      tier3: 11 + M holy damage
feature_type: ability
flavor: You channel holy energy to smite a foe and heal an ally.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 3 Wrath
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) to allow yourself or one ally within 10 squares to regain [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc.v1:mcdm.heroes.v1/rule.health/recoveries).
    flavor: You channel holy energy to smite a foe and heal an ally.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: The Gods Punish and Defend
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/the-gods-punish-and-defend
    target: One creature or object
    tier1: 5 + M holy damage
    tier2: 8 + M holy damage
    tier3: 11 + M holy damage
    type: ability
name: The Gods Punish and Defend
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
