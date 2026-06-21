---
action_type: Maneuver
class: troubadour
cost: 3 Drama
cost_amount: "3"
cost_resource: Drama
distance: Self; see below
effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). You make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting).
feature_type: ability
file_basename: upstage
file_dpath: feature/ability/troubadour/level-1
flavor: As you bob and weave through the crowd, you can't help but leave the audience wanting more.
item_id: upstage
item_name: Upstage
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Upstage
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/upstage
source: mcdm.heroes.v1
target: Self
tier1: '[Taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); A < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)'
tier2: '[Taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); A < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)'
tier3: '[Taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); A < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can''t stand ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))'
type: ability
---

```ds-feature
cost: 3 Drama
distance: Self; see below
effects:
    - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). You make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting).
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: '[Taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); A < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)'
      tier2: '[Taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); A < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)'
      tier3: '[Taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); A < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can''t stand ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))'
feature_type: ability
flavor: As you bob and weave through the crowd, you can't help but leave the audience wanting more.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Maneuver
    class: troubadour
    cost: 3 Drama
    distance: Self; see below
    effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). You make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting).
    flavor: As you bob and weave through the crowd, you can't help but leave the audience wanting more.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Upstage
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/upstage
    target: Self
    tier1: '[Taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); A < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)'
    tier2: '[Taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); A < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)'
    tier3: '[Taunted](scc.v1:mcdm.heroes.v1/condition/taunted) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)); A < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) can''t stand ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))'
    type: ability
name: Upstage
target: Self
type: feature
usage: Maneuver
```
