---
action_type: Main action
class: censor
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: Each enemy [adjacent](../../../../rule/combat/adjacent.md) to the target is [pushed](../../../../movement/forced-movement.md) away from the target up to a number of squares equal to your [Presence](../../../../rule/character/presence.md) score.
feature_type: ability
file_basename: your-allies-cannot-save-you
file_dpath: feature/ability/censor/level-1
flavor: Your magic [strike](../../../../rule/combat/strike.md) [turns](../../../../rule/combat/turn.md) your foe's guilt into a burst of holy power.
item_id: your-allies-cannot-save-you
item_name: Your Allies Cannot Save You!
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Your Allies Cannot Save You!
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/your-allies-cannot-save-you
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + M holy damage
tier2: 5 + M holy damage
tier3: 8 + M holy damage
type: ability
---

```ds-feature
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: Each enemy [adjacent](../../../../rule/combat/adjacent.md) to the target is [pushed](../../../../movement/forced-movement.md) away from the target up to a number of squares equal to your [Presence](../../../../rule/character/presence.md) score.
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 3 + M holy damage
      tier2: 5 + M holy damage
      tier3: 8 + M holy damage
feature_type: ability
flavor: Your magic [strike](../../../../rule/combat/strike.md) [turns](../../../../rule/combat/turn.md) your foe's guilt into a burst of holy power.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: Each enemy [adjacent](../../../../rule/combat/adjacent.md) to the target is [pushed](../../../../movement/forced-movement.md) away from the target up to a number of squares equal to your [Presence](../../../../rule/character/presence.md) score.
    flavor: Your magic [strike](../../../../rule/combat/strike.md) [turns](../../../../rule/combat/turn.md) your foe's guilt into a burst of holy power.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Your Allies Cannot Save You!
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/your-allies-cannot-save-you
    subtype: signature
    target: One creature or object
    tier1: 3 + M holy damage
    tier2: 5 + M holy damage
    tier3: 8 + M holy damage
    type: ability
name: Your Allies Cannot Save You!
target: One creature or object
type: feature
usage: Main action
```
