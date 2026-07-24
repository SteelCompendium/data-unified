---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
cost: 7 Essence
cost_amount: "7"
cost_resource: Essence
distance: 3 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 damage
      tier2: 6 damage
      tier3: 9 damage
    - effect: Until the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each ally in the area has each of their [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) scores treated as 1 higher for the purpose of resisting [potencies](scc.v1:mcdm.heroes.v1/rule.character/potency), and has a +1 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [saving throws](scc.v1:mcdm.heroes.v1/rule.general/saving-throw).
      name: Effect
    - effect: You make the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) again to target each enemy in the area without spending essence, and the effect lasts until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Persistent 1
feature_type: ability
file_basename: swarm-of-spirits
file_dpath: feature/ability/elementalist/level-3
flavor: Guardian animal spirits surround you to harry your foes and bolster your allies.
item_id: swarm-of-spirits
item_name: Swarm of Spirits
keywords:
    - Area
    - Green
    - Magic
level: "3"
name: Swarm of Spirits
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-3/swarm-of-spirits
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 3 damage
tier2: 6 damage
tier3: 9 damage
type: ability
---

```ds-feature
cost: 7 Essence
distance: 3 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 damage
      tier2: 6 damage
      tier3: 9 damage
    - effect: Until the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each ally in the area has each of their [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) scores treated as 1 higher for the purpose of resisting [potencies](scc.v1:mcdm.heroes.v1/rule.character/potency), and has a +1 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [saving throws](scc.v1:mcdm.heroes.v1/rule.general/saving-throw).
      name: Effect
    - effect: You make the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) again to target each enemy in the area without spending essence, and the effect lasts until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Persistent 1
feature_type: ability
flavor: Guardian animal spirits surround you to harry your foes and bolster your allies.
keywords:
    - Area
    - Green
    - Magic
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    cost: 7 Essence
    distance: 3 [aura](scc.v1:mcdm.heroes.v1/rule.combat/aura)
    effects:
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: 3 damage
          tier2: 6 damage
          tier3: 9 damage
        - effect: Until the end of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each ally in the area has each of their [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) scores treated as 1 higher for the purpose of resisting [potencies](scc.v1:mcdm.heroes.v1/rule.character/potency), and has a +1 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [saving throws](scc.v1:mcdm.heroes.v1/rule.general/saving-throw).
          name: Effect
        - effect: You make the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) again to target each enemy in the area without spending essence, and the effect lasts until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
          name: Persistent 1
    flavor: Guardian animal spirits surround you to harry your foes and bolster your allies.
    keywords:
        - Area
        - Green
        - Magic
    level: "3"
    name: Swarm of Spirits
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-3/swarm-of-spirits
    target: Each enemy in the area
    tier1: 3 damage
    tier2: 6 damage
    tier3: 9 damage
    type: ability
name: Swarm of Spirits
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
