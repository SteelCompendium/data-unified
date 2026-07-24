---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 5 + M damage; P < WEAK, the target is banished (save ends)
      tier2: 8 + M damage; P < AVERAGE, the target is banished (save ends)
      tier3: 11 + M damage; P < STRONG, the target is banished (save ends)
    - effect: This ability gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against demons, [devils](scc.v1:mcdm.heroes.v1/ancestry/devil), undead, and creatures not native to your current world. If you know the target's true name, this ability has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge). While banished, the target is sent to another manifold in the timescape and removed from the encounter map. A banished target can do nothing but make [saving throws](scc.v1:mcdm.heroes.v1/rule.general/saving-throw), and takes 10 holy damage each time they do so. If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) while banished, they are lost to the timescape.
      name: Effect
feature_type: ability
file_basename: banish
file_dpath: feature/ability/censor/level-9
flavor: You sever the target's tenuous connection to the world.
item_id: banish
item_name: Banish
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: Banish
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-9/banish
source: mcdm.heroes.v1
subclass: exorcist
target: One creature
tier1: 5 + M damage; P < WEAK, the target is banished (save ends)
tier2: 8 + M damage; P < AVERAGE, the target is banished (save ends)
tier3: 11 + M damage; P < STRONG, the target is banished (save ends)
type: ability
---

```ds-feature
cost: 11 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 5 + M damage; P < WEAK, the target is banished (save ends)
      tier2: 8 + M damage; P < AVERAGE, the target is banished (save ends)
      tier3: 11 + M damage; P < STRONG, the target is banished (save ends)
    - effect: This ability gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against demons, [devils](scc.v1:mcdm.heroes.v1/ancestry/devil), undead, and creatures not native to your current world. If you know the target's true name, this ability has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge). While banished, the target is sent to another manifold in the timescape and removed from the encounter map. A banished target can do nothing but make [saving throws](scc.v1:mcdm.heroes.v1/rule.general/saving-throw), and takes 10 holy damage each time they do so. If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) while banished, they are lost to the timescape.
      name: Effect
feature_type: ability
flavor: You sever the target's tenuous connection to the world.
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
          tier1: 5 + M damage; P < WEAK, the target is banished (save ends)
          tier2: 8 + M damage; P < AVERAGE, the target is banished (save ends)
          tier3: 11 + M damage; P < STRONG, the target is banished (save ends)
        - effect: This ability gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against demons, [devils](scc.v1:mcdm.heroes.v1/ancestry/devil), undead, and creatures not native to your current world. If you know the target's true name, this ability has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge). While banished, the target is sent to another manifold in the timescape and removed from the encounter map. A banished target can do nothing but make [saving throws](scc.v1:mcdm.heroes.v1/rule.general/saving-throw), and takes 10 holy damage each time they do so. If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) while banished, they are lost to the timescape.
          name: Effect
    flavor: You sever the target's tenuous connection to the world.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "9"
    name: Banish
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-9/banish
    subclass: exorcist
    target: One creature
    tier1: 5 + M damage; P < WEAK, the target is banished (save ends)
    tier2: 8 + M damage; P < AVERAGE, the target is banished (save ends)
    tier3: 11 + M damage; P < STRONG, the target is banished (save ends)
    type: ability
name: Banish
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
