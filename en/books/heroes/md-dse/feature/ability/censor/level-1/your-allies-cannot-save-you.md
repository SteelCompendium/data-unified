---
action_type: Main action
class: censor
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: Each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) away from the target up to a number of squares equal to your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
feature_type: ability
file_basename: your-allies-cannot-save-you
file_dpath: feature/ability/censor/level-1
flavor: Your magic [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) your foe's guilt into a burst of holy power.
item_id: your-allies-cannot-save-you
item_name: Your Allies Cannot Save You!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Your Allies Cannot Save You!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
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
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: Each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) away from the target up to a number of squares equal to your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M holy damage
      tier2: 5 + M holy damage
      tier3: 8 + M holy damage
feature_type: ability
flavor: Your magic [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) your foe's guilt into a burst of holy power.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: Each enemy [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) away from the target up to a number of squares equal to your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
    flavor: Your magic [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) your foe's guilt into a burst of holy power.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Your Allies Cannot Save You!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
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
