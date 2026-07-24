---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: talent
cost: 3 Clarity
cost_amount: "3"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: If you target an ally, they gain [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to three times your [Presence](../../../../rule/character/presence.md) score, and they can end one effect on them that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md). If you target an enemy, you make a [power roll](../../../../rule/dice/power-roll.md).
      name: Effect
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 3 + P psychic damage; I < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 6 + P psychic damage; I < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 9 + P psychic damage; I < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
feature_type: ability
file_basename: awe
file_dpath: feature/ability/talent/level-1
flavor: You project psionic energy out to a creature and take on a new visage in their mind.
item_id: awe
item_name: Awe
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telepathy
level: "1"
name: Awe
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/awe
source: mcdm.heroes.v1
target: One creature
tier1: 3 + P psychic damage; I < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
tier2: 6 + P psychic damage; I < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
tier3: 9 + P psychic damage; I < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
type: ability
---

```ds-feature
cost: 3 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: If you target an ally, they gain [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to three times your [Presence](../../../../rule/character/presence.md) score, and they can end one effect on them that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md). If you target an enemy, you make a [power roll](../../../../rule/dice/power-roll.md).
      name: Effect
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 3 + P psychic damage; I < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
      tier2: 6 + P psychic damage; I < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
      tier3: 9 + P psychic damage; I < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
feature_type: ability
flavor: You project psionic energy out to a creature and take on a new visage in their mind.
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telepathy
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: talent
    cost: 3 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - effect: If you target an ally, they gain [temporary Stamina](../../../../rule/health/temporary-stamina.md) equal to three times your [Presence](../../../../rule/character/presence.md) score, and they can end one effect on them that is ended by a [saving throw](../../../../rule/general/saving-throw.md) or that ends at the end of their [turn](../../../../rule/combat/turn.md). If you target an enemy, you make a [power roll](../../../../rule/dice/power-roll.md).
          name: Effect
        - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
          tier1: 3 + P psychic damage; I < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
          tier2: 6 + P psychic damage; I < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
          tier3: 9 + P psychic damage; I < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
    flavor: You project psionic energy out to a creature and take on a new visage in their mind.
    keywords:
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Telepathy
    level: "1"
    name: Awe
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/awe
    target: One creature
    tier1: 3 + P psychic damage; I < WEAK, [frightened](../../../../condition/frightened.md) (save ends)
    tier2: 6 + P psychic damage; I < AVERAGE, [frightened](../../../../condition/frightened.md) (save ends)
    tier3: 9 + P psychic damage; I < STRONG, [frightened](../../../../condition/frightened.md) (save ends)
    type: ability
name: Awe
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
