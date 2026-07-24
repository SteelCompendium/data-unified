---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 9 + M damage; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 13 + M damage; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 18 + M damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    - effect: At the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), a target [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) this way deals holy damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score to each enemy within 2 squares of them.
      name: Effect
feature_type: ability
file_basename: pillar-of-holy-fire
file_dpath: feature/ability/censor/level-8
flavor: Your enemy's guilt fuels a holy flame that burns your foes.
item_id: pillar-of-holy-fire
item_name: Pillar of Holy Fire
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: Pillar of Holy Fire
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-8/pillar-of-holy-fire
source: mcdm.heroes.v1
target: One creature
tier1: 9 + M damage; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier2: 13 + M damage; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier3: 18 + M damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---

```ds-feature
cost: 11 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 9 + M damage; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 13 + M damage; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 18 + M damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    - effect: At the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), a target [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) this way deals holy damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score to each enemy within 2 squares of them.
      name: Effect
feature_type: ability
flavor: Your enemy's guilt fuels a holy flame that burns your foes.
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
          tier1: 9 + M damage; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier2: 13 + M damage; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
          tier3: 18 + M damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
        - effect: At the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), a target [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) this way deals holy damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score to each enemy within 2 squares of them.
          name: Effect
    flavor: Your enemy's guilt fuels a holy flame that burns your foes.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "8"
    name: Pillar of Holy Fire
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-8/pillar-of-holy-fire
    target: One creature
    tier1: 9 + M damage; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier2: 13 + M damage; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier3: 18 + M damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    type: ability
name: Pillar of Holy Fire
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
