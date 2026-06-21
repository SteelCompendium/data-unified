---
action_type: Main action
class: troubadour
cost: 11 Drama
cost_amount: "11"
cost_resource: Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: Add your current [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) to your target's current [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), then you have half that total [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and the target has the remainder. If either of you would gain more [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) this way than their [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) maximum, the difference in [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) between what that creature would gain and their maximum is gained by the other creature. Neither of you can gain more [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) than your maximum this way. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
file_basename: renegotiated-contract
file_dpath: feature/ability/troubadour/level-9
flavor: No, no. You don't die until the sequel.
item_id: renegotiated-contract
item_name: Renegotiated Contract
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: Renegotiated Contract
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/renegotiated-contract
source: mcdm.heroes.v1
target: One creature
tier1: You and the target can each end one effect on yourselves that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
tier2: You and the target can end any effects on yourselves that are ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that end at the end of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
tier3: You can choose any of the current effects on you and the target that are ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that end at the end of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), apply the chosen effects to the target, and end the rest.
type: ability
---

```ds-feature
cost: 11 Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: Add your current [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) to your target's current [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), then you have half that total [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and the target has the remainder. If either of you would gain more [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) this way than their [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) maximum, the difference in [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) between what that creature would gain and their maximum is gained by the other creature. Neither of you can gain more [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) than your maximum this way. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: You and the target can each end one effect on yourselves that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      tier2: You and the target can end any effects on yourselves that are ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that end at the end of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      tier3: You can choose any of the current effects on you and the target that are ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that end at the end of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), apply the chosen effects to the target, and end the rest.
feature_type: ability
flavor: No, no. You don't die until the sequel.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    cost: 11 Drama
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: Add your current [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) to your target's current [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), then you have half that total [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and the target has the remainder. If either of you would gain more [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) this way than their [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) maximum, the difference in [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) between what that creature would gain and their maximum is gained by the other creature. Neither of you can gain more [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) than your maximum this way. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: No, no. You don't die until the sequel.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "9"
    name: Renegotiated Contract
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/renegotiated-contract
    target: One creature
    tier1: You and the target can each end one effect on yourselves that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    tier2: You and the target can end any effects on yourselves that are ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that end at the end of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    tier3: You can choose any of the current effects on you and the target that are ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that end at the end of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), apply the chosen effects to the target, and end the rest.
    type: ability
name: Renegotiated Contract
target: One creature
type: feature
usage: Main action
```
