---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
cost: 9 Insight
cost_amount: "9"
cost_resource: Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 2 damage; if the target has R < WEAK, before the damage is resolved, they make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
      tier2: 5 damage; if the target has R < AVERAGE, before the damage is resolved, they use a main action ability of your choice.
      tier3: 7 damage; if the target has R < STRONG, before the damage is resolved, they can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and use a main action ability of your choice.
    - effect: You choose the new targets for the original target's [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) or ability. Additionally, if you are hidden or disguised, using this ability doesn't cause you to be revealed.
      name: Effect
feature_type: ability
file_basename: puppet-strings
file_dpath: feature/ability/shadow/level-6
flavor: You prick little needles on the tips of your fingers into the nerves of your enemies and cause them to lose control.
item_id: puppet-strings
item_name: Puppet Strings
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Strike
    - Weapon
level: "6"
name: Puppet Strings
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-6/puppet-strings
source: mcdm.heroes.v1
subclass: harlequin-mask
target: Two enemies
tier1: 2 damage; if the target has R < WEAK, before the damage is resolved, they make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
tier2: 5 damage; if the target has R < AVERAGE, before the damage is resolved, they use a main action ability of your choice.
tier3: 7 damage; if the target has R < STRONG, before the damage is resolved, they can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and use a main action ability of your choice.
type: ability
---

```ds-feature
cost: 9 Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 2 damage; if the target has R < WEAK, before the damage is resolved, they make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
      tier2: 5 damage; if the target has R < AVERAGE, before the damage is resolved, they use a main action ability of your choice.
      tier3: 7 damage; if the target has R < STRONG, before the damage is resolved, they can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and use a main action ability of your choice.
    - effect: You choose the new targets for the original target's [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) or ability. Additionally, if you are hidden or disguised, using this ability doesn't cause you to be revealed.
      name: Effect
feature_type: ability
flavor: You prick little needles on the tips of your fingers into the nerves of your enemies and cause them to lose control.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Strike
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: shadow
    cost: 9 Insight
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 2 damage; if the target has R < WEAK, before the damage is resolved, they make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
          tier2: 5 damage; if the target has R < AVERAGE, before the damage is resolved, they use a main action ability of your choice.
          tier3: 7 damage; if the target has R < STRONG, before the damage is resolved, they can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and use a main action ability of your choice.
        - effect: You choose the new targets for the original target's [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) or ability. Additionally, if you are hidden or disguised, using this ability doesn't cause you to be revealed.
          name: Effect
    flavor: You prick little needles on the tips of your fingers into the nerves of your enemies and cause them to lose control.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Strike
        - Weapon
    level: "6"
    name: Puppet Strings
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-6/puppet-strings
    subclass: harlequin-mask
    target: Two enemies
    tier1: 2 damage; if the target has R < WEAK, before the damage is resolved, they make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike).
    tier2: 5 damage; if the target has R < AVERAGE, before the damage is resolved, they use a main action ability of your choice.
    tier3: 7 damage; if the target has R < STRONG, before the damage is resolved, they can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and use a main action ability of your choice.
    type: ability
name: Puppet Strings
target: Two enemies
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
