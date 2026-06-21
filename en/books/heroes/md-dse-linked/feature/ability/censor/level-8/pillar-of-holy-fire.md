---
action_type: Main action
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: At the end of each of your [turns](../../../../rule/combat/turn.md), a target [dazed](../../../../condition/dazed.md) this way deals holy damage equal to twice your [Presence](../../../../rule/character/presence.md) score to each enemy within 2 squares of them.
feature_type: ability
file_basename: pillar-of-holy-fire
file_dpath: feature/ability/censor/level-8
flavor: Your enemy's guilt fuels a holy flame that burns your foes.
item_id: pillar-of-holy-fire
item_name: Pillar of Holy Fire
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "8"
name: Pillar of Holy Fire
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-8/pillar-of-holy-fire
source: mcdm.heroes.v1
target: One creature
tier1: 9 + M damage; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
tier2: 13 + M damage; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
tier3: 18 + M damage; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: At the end of each of your [turns](../../../../rule/combat/turn.md), a target [dazed](../../../../condition/dazed.md) this way deals holy damage equal to twice your [Presence](../../../../rule/character/presence.md) score to each enemy within 2 squares of them.
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 9 + M damage; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
      tier2: 13 + M damage; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
      tier3: 18 + M damage; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: Your enemy's guilt fuels a holy flame that burns your foes.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 11 Wrath
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: At the end of each of your [turns](../../../../rule/combat/turn.md), a target [dazed](../../../../condition/dazed.md) this way deals holy damage equal to twice your [Presence](../../../../rule/character/presence.md) score to each enemy within 2 squares of them.
    flavor: Your enemy's guilt fuels a holy flame that burns your foes.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "8"
    name: Pillar of Holy Fire
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-8/pillar-of-holy-fire
    target: One creature
    tier1: 9 + M damage; I < WEAK, [dazed](../../../../condition/dazed.md) (save ends)
    tier2: 13 + M damage; I < AVERAGE, [dazed](../../../../condition/dazed.md) (save ends)
    tier3: 18 + M damage; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: Pillar of Holy Fire
target: One creature
type: feature
usage: Main action
```
