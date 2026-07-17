---
agility: 3
ev: "48"
file_basename: thorn-dragon
file_dpath: monster/dragon/statblock
free_strike: 5
immunities:
    - Poison 5
intuition: 1
item_id: thorn-dragon
item_name: Thorn Dragon
keywords:
    - Dragon
    - Elemental
level: 2
might: 2
movement: Fly
name: Thorn Dragon
organization: Solo
presence: 2
reason: -1
scc: mcdm.monsters.v1/monster.dragon.statblock/thorn-dragon
size: "3"
source: mcdm.monsters.v1
speed: 8
stability: 6
stamina: "250"
type: statblock
---

```ds-sb
agility: 3
ev: "48"
features:
    - effects:
        - effect: |-
            **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect):** At the end of each of their turns, the dragon can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
            **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.
      feature_type: trait
      icon: ☠️
      name: Solo Monster
      type: feature
    - effects:
        - effect: The dragon's scales create a 2 aura of withering green magic around them. Any creature other than the dragon who regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) in the area regains only half the expected amount. Any [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) creature who enters the area for the first time in a round or starts their turn there takes 1d3 corruption damage.
      feature_type: trait
      icon: ❇️
      name: Withering Wyrmscale Aura
      type: feature
    - ability_type: Signature Ability
      distance: 10 x 1 line within 1
      effects:
        - roll: ""
          tier1: 12 poison damage; the target is dragonsealed (save ends)
          tier2: 9 poison damage; the target is dragonsealed (save ends)
          tier3: 5 poison damage
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Virulent Breath
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 8 damage; push 2
          tier2: 12 damage; push 4
          tier3: 15 damage; push 8
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Spinous Tail Swing
      target: Two enemies or objects
      type: feature
      usage: Main action
    - effects:
        - effect: Once per turn, the dragon [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 5 squares and can move through enemies' spaces at their usual speed. The first time the dragon moves through an enemy's space during this movement, the enemy takes 3 damage.
      feature_type: trait
      icon: ⭐️
      name: Provoking Nettles
      type: feature
    - cost: 5 Malice
      distance: 10 burst
      effects:
        - effect: '**Effect:** Each target must be dragonsealed. Each target is pulled up to 5 squares toward the dragon, who gains 5 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) for each target pulled.'
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Investiture of Verdure
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** A dragonsealed creature within distance ends the dragonsealed effect.
            **Effect:** The target is pulled up to 5 squares toward the dragon, and if they have A < 2, they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the end of their next turn.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Prickly Situation
      target: The triggering creature
      type: feature
      usage: Free triggered action
    - cost: 1 Malice
      distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** A creature within distance deals damage to the dragon with a melee strike.
            **Effect:** The dragon makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target, and if the target has M < 2, they are [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) until the end of their next turn.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Thorny Scales
      target: The triggering creature
      type: feature
      usage: Free triggered action
    - cost: Villain Action 1
      distance: 4 burst
      effects:
        - roll: Power Roll + 3
          tier1: 5 damage; A < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier2: 9 damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier3: 12 damage; A < 3 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Briar Bindings
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: Self
      effects:
        - effect: '**Effect:** The thorns upon the dragon''s scales grow longer and sharper. Until the end of the encounter, any [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creature who targets the dragon with a melee strike takes 3 damage. The dragon then uses their Provoking Nettles ability.'
      feature_type: ability
      icon: ☠️
      keywords: []
      name: Thorned Armor
      target: Self
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: Special
      effects:
        - effect: |-
            **Effect:** Poisonous overgrowth and seeking vines cover all surfaces on the encounter map. The dragon uses their Bramble Barricade Malice feature twice at no cost. Until the end of the encounter, any creature [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) by the dragon takes 1d3 poison damage, and if they have M < 2, they are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends).
            **Special:** If the Thorn Dragon's Domain [trait](scc.v1:mcdm.monsters.v1/rule.monster/monster-trait) is in effect, any creature other than the dragon who starts their turn on the encounter map takes 1d3 poison damage.
      feature_type: ability
      icon: ☠️
      keywords: []
      name: Malign Thicket
      target: Special
      type: feature
      usage: '-'
free_strike: 5
immunities:
    - Poison 5
intuition: 1
keywords:
    - Dragon
    - Elemental
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.dragon.statblock/thorn-dragon
    source: mcdm.monsters.v1
might: 2
movement: Fly
name: Thorn Dragon
organization: Solo
presence: 2
reason: -1
role: ""
size: "3"
speed: 8
stability: 6
stamina: "250"
type: statblock
```
