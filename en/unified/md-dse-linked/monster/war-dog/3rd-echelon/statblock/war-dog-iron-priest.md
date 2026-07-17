---
agility: 1
ev: "10"
file_basename: war-dog-iron-priest
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 3
intuition: 4
item_id: war-dog-iron-priest
item_name: War Dog Iron Priest
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 8
might: 2
name: War Dog Iron Priest
organization: Horde
presence: 4
reason: 1
role: Support
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-iron-priest
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "50"
type: statblock
---

```ds-sb
agility: 1
ev: "10"
features:
    - ability_type: Signature Ability
      distance: 7 x 1 line within 1
      effects:
        - roll: Power Roll + 4
          tier1: 3 damage
          tier2: 6 damage; P < 3 [bleeding](../../../../condition/bleeding.md) (save ends)
          tier3: 8 damage; P < 4 the target loses 1 Recovery and is [bleeding](../../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: Houndcannon
      target: Each enemy in the area
      type: feature
      usage: Main action
    - cost: 2+ Malice
      distance: 4 aura
      effects:
        - effect: |-
            **Effect:** For every 2 [Malice](../../../../rule/monster/malice.md) spent, each target gains one of the following effects until the start of the iron priest's next turn.
            - The target has damage immunity 2.
            - The target's strikes deal an extra 3 holy damage.
            - The target has a +3 bonus to speed.
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Iron Banner
      target: Each war dog in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: The Director gains 1 [Malice](../../../../rule/monster/malice.md) whenever an ally within 3 squares of the iron priest obtains a tier 3 outcome on a power roll.
      feature_type: trait
      icon: ⭐️
      name: Chosen of the Iron Saint
      type: feature
free_strike: 3
intuition: 4
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-iron-priest
    source: mcdm.monsters.v1
might: 2
name: War Dog Iron Priest
organization: Horde
presence: 4
reason: 1
role: Support
size: 1M
speed: 5
stability: 0
stamina: "50"
type: statblock
```
