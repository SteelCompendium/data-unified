---
agility: 1
ev: "7"
file_basename: war-dog-war-doc
file_dpath: monster/war-dog/2nd-echelon/statblock
free_strike: 3
intuition: 2
item_id: war-dog-war-doc
item_name: War Dog War Doc
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 5
might: 0
name: War Dog War Doc
organization: Horde
presence: 0
reason: 3
role: Support
scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-war-doc
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "35"
type: statblock
---

```ds-sb
agility: 1
ev: "7"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 6 poison damage
          tier2: 8 poison damage
          tier3: 9 poison damage; M < 3 [weakened](../../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Syringe Crossbow
      target: One creature
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: '**Effect:** If the target has a loyalty collar, they are reduced to 0 [Stamina](../../../../rule/health/stamina.md).'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Posthumous Promotion
      target: One war dog
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Ranged 15
      effects:
        - effect: |-
            **Trigger:** One ally within distance dies.
            **Effect:** Each ally [adjacent](../../../../rule/combat/adjacent.md) to the dead ally deals an extra 6 damage on their next strike.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Sanguine Stimulants
      target: Special
      type: feature
      usage: Triggered action
    - effects:
        - effect: If the war doc uses the Reconstitute war dog [Malice](../../../../rule/monster/malice.md) feature, it costs 1 [Malice](../../../../rule/monster/malice.md) less. Additionally, allies can treat the living war doc as a corpse when using the Reconstitute feature (see Reconstitute).
      feature_type: trait
      icon: ⭐️
      name: Body Bank Branch Manager
      type: feature
free_strike: 3
intuition: 2
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-war-doc
    source: mcdm.monsters.v1
might: 0
name: War Dog War Doc
organization: Horde
presence: 0
reason: 3
role: Support
size: 1L
speed: 5
stability: 1
stamina: "35"
type: statblock
```
