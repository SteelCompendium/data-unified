---
action_type: Main action
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effect: Each enemy [frightened](../../../../condition/frightened.md) this way is [pushed](../../../../movement/forced-movement.md) up to 2 squares away from the target and takes psychic damage equal to your [Presence](../../../../rule/character/presence.md) score.
feature_type: ability
file_basename: behold-the-face-of-justice
file_dpath: feature/ability/censor/level-1
flavor: You attack a foe and your enemies behold a vision of the true nature of your resolve.
item_id: behold-the-face-of-justice
item_name: Behold the Face of Justice!
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Behold the Face of Justice!
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/behold-the-face-of-justice
source: mcdm.heroes.v1
target: One creature
tier1: 3 + M holy damage; if the target has P < WEAK, each enemy within 2 squares of them is [frightened](../../../../condition/frightened.md) of you (save ends)
tier2: 5 + M holy damage; if the target has P < AVERAGE, each enemy within 2 squares of them is [frightened](../../../../condition/frightened.md) of you (save ends)
tier3: 8 + M holy damage; if the target has P < STRONG, each enemy within 2 squares of them is [frightened](../../../../condition/frightened.md) of you (save ends)
type: ability
---

```ds-feature
cost: 5 Wrath
distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: Each enemy [frightened](../../../../condition/frightened.md) this way is [pushed](../../../../movement/forced-movement.md) up to 2 squares away from the target and takes psychic damage equal to your [Presence](../../../../rule/character/presence.md) score.
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 3 + M holy damage; if the target has P < WEAK, each enemy within 2 squares of them is [frightened](../../../../condition/frightened.md) of you (save ends)
      tier2: 5 + M holy damage; if the target has P < AVERAGE, each enemy within 2 squares of them is [frightened](../../../../condition/frightened.md) of you (save ends)
      tier3: 8 + M holy damage; if the target has P < STRONG, each enemy within 2 squares of them is [frightened](../../../../condition/frightened.md) of you (save ends)
feature_type: ability
flavor: You attack a foe and your enemies behold a vision of the true nature of your resolve.
keywords:
    - Magic
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    cost: 5 Wrath
    distance: '[Melee](../../../../rule/combat/melee.md) 1 or [ranged](../../../../rule/combat/ranged.md) 5'
    effect: Each enemy [frightened](../../../../condition/frightened.md) this way is [pushed](../../../../movement/forced-movement.md) up to 2 squares away from the target and takes psychic damage equal to your [Presence](../../../../rule/character/presence.md) score.
    flavor: You attack a foe and your enemies behold a vision of the true nature of your resolve.
    keywords:
        - Magic
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Behold the Face of Justice!
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/behold-the-face-of-justice
    target: One creature
    tier1: 3 + M holy damage; if the target has P < WEAK, each enemy within 2 squares of them is [frightened](../../../../condition/frightened.md) of you (save ends)
    tier2: 5 + M holy damage; if the target has P < AVERAGE, each enemy within 2 squares of them is [frightened](../../../../condition/frightened.md) of you (save ends)
    tier3: 8 + M holy damage; if the target has P < STRONG, each enemy within 2 squares of them is [frightened](../../../../condition/frightened.md) of you (save ends)
    type: ability
name: Behold the Face of Justice!
target: One creature
type: feature
usage: Main action
```
