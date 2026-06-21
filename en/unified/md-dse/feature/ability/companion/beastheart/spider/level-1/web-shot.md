---
action_type: Maneuver
class: beastheart
companion: spider
distance: Ranged 5
effect: If the target has M < AVERAGE, they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the end of their next turn.
feature_type: ability
file_basename: web-shot
file_dpath: feature/ability/companion/beastheart/spider/level-1
flavor: The spider fires a ball of sticky silk.
item_id: web-shot
item_name: Web Shot
keywords:
    - Companion
    - Ranged
    - Weapon
level: "1"
name: Web Shot
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.spider.level-1/web-shot
source: mcdm.beastheart.v1
spend: '1 Ferocity: If the target has M < STRONG, they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).'
subtype: signature
target: One enemy
type: ability
---

```ds-feature
distance: Ranged 5
effects:
    - effect: If the target has M < AVERAGE, they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the end of their next turn.
    - effect: '1 Ferocity: If the target has M < STRONG, they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).'
      name: Spend
feature_type: ability
flavor: The spider fires a ball of sticky silk.
keywords:
    - Companion
    - Ranged
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    companion: spider
    distance: Ranged 5
    effect: If the target has M < AVERAGE, they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the end of their next turn.
    flavor: The spider fires a ball of sticky silk.
    keywords:
        - Companion
        - Ranged
        - Weapon
    level: "1"
    name: Web Shot
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.spider.level-1/web-shot
    spend: '1 Ferocity: If the target has M < STRONG, they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends).'
    subtype: signature
    target: One enemy
    type: ability
name: Web Shot
target: One enemy
type: feature
usage: Maneuver
```
