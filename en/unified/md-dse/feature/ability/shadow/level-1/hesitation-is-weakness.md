---
action_type: Free triggered
class: shadow
cost: 1 Insight
cost_amount: "1"
cost_resource: Insight
distance: Self
effect: You take your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) after the triggering hero.
feature_type: ability
file_basename: hesitation-is-weakness
file_dpath: feature/ability/shadow/level-1
flavor: Keep up the attack. Never give them a moment's grace.
item_id: hesitation-is-weakness
item_name: Hesitation Is Weakness
keywords: []
level: "1"
name: Hesitation Is Weakness
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/hesitation-is-weakness
source: mcdm.heroes.v1
subtype: triggered
target: Self
trigger: Another hero ends their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). That hero can't have used this ability to start their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
type: ability
---

```ds-feature
cost: 1 Insight
distance: Self
effects:
    - effect: You take your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) after the triggering hero.
feature_type: ability
flavor: Keep up the attack. Never give them a moment's grace.
keywords: []
metadata:
    action_type: Free triggered
    class: shadow
    cost: 1 Insight
    distance: Self
    effect: You take your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) after the triggering hero.
    flavor: Keep up the attack. Never give them a moment's grace.
    keywords: []
    level: "1"
    name: Hesitation Is Weakness
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/hesitation-is-weakness
    subtype: triggered
    target: Self
    trigger: Another hero ends their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). That hero can't have used this ability to start their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    type: ability
name: Hesitation Is Weakness
target: Self
trigger: Another hero ends their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). That hero can't have used this ability to start their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
type: feature
usage: Free triggered
```
