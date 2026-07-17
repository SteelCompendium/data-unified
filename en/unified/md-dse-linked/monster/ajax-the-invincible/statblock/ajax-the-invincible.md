---
agility: 4
ev: "156"
file_basename: ajax-the-invincible
file_dpath: monster/ajax-the-invincible/statblock
free_strike: 11
intuition: 5
item_id: ajax-the-invincible
item_name: Ajax the Invincible
keywords:
    - Human
    - Humanoid
level: 11
might: 5
movement: Fly, hover
name: Ajax the Invincible
organization: Solo
presence: 4
reason: 5
scc: mcdm.monsters.v1/monster.ajax-the-invincible.statblock/ajax-the-invincible
size: 1L
source: mcdm.monsters.v1
speed: 7
stability: 2
stamina: "700"
type: statblock
---

```ds-sb
agility: 4
ev: "156"
features:
    - effects:
        - effect: |-
            **Ajax Turns:** Ajax takes up to three turns each round. He can't take turns consecutively. Additionally, he can use three [triggered actions](../../../rule/combat/triggered-action.md) in a round while he isn't [dazed](../../../condition/dazed.md).
            **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of his turns, Ajax can take 20 damage to end up to two effects on him that can be ended by a [saving throw](../../../rule/general/saving-throw.md). This damage can't be reduced in any way.
      feature_type: trait
      icon: ☠️
      name: Ajax
      type: feature
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 16 damage; M < 4 the target loses 1d3 [Recoveries](../../../rule/health/recoveries.md)
          tier2: 22 damage; M < 5 the target loses 1d3 [Recoveries](../../../rule/health/recoveries.md)
          tier3: 26 damage; M < 6 [prone](../../../condition/prone.md) and the target loses 1d3 [Recoveries](../../../rule/health/recoveries.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Magic
        - Melee
        - Strike
        - Weapon
      name: Blade of the Gol King
      target: Two creatures or objects
      type: feature
      usage: Main Action
    - distance: 3 cube within 10
      effects:
        - roll: Power Roll + 5
          tier1: 11 holy damage; [slide](../../../movement/forced-movement.md) 2; P < 4 the target is hexed (save ends)
          tier2: 17 holy damage; [slide](../../../movement/forced-movement.md) 5; P < 5 the target is hexed (save ends)
          tier3: 21 holy damage; [slide](../../../movement/forced-movement.md) 8; P < 6 the target is hexed (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Decree by the Jade Hand
      target: Each enemy and object in the area
      type: feature
      usage: Main Action
    - distance: Ranged 5
      effects:
        - roll: Power Roll + 5
          tier1: No effect.
          tier2: The target is [grabbed](../../../condition/grabbed.md).
          tier3: 11 damage; the target is [grabbed](../../../condition/grabbed.md).
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Weapon
      name: Divine Vine
      target: One creature or object
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: 5 cube within 20
      effects:
        - effect: '**Effect:** Ajax throws a glowing bead to a square within distance, which ignites at the start of Ajax''s next turn and creates an area around it that lasts until the start of Ajax''s following turn. Each enemy in the area when the bead ignites takes 20 fire damage, and if they have A < 5, they are [dazed](../../../condition/dazed.md) (save ends). Any enemy who starts their turn in the area takes 10 fire damage.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Bead of Hell
      target: Special
      type: feature
      usage: Maneuver
    - effects:
        - effect: Ajax dies only when his [Stamina](../../../rule/health/stamina.md) reaches −350. While his [Stamina](../../../rule/health/stamina.md) is below 0, Ajax is [bleeding](../../../condition/bleeding.md), he can choose any two options from his Tactical Stance trait each round, and the Director gains 2 additional [Malice](../../../rule/monster/malice.md) per round.
      feature_type: trait
      icon: ⭐️
      name: I'm Not Done Yet.
      type: feature
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** A creature within distance marks Ajax.
            **Effect:** The target is marked while Ajax is marked. While the target is marked this way, Ajax gains an [edge](../../../rule/dice/edge.md) on power rolls against them, and whenever the target uses a [triggered action](../../../rule/combat/triggered-action.md) involving their mark on Ajax, he can make a [free strike](../../../feature/common/main-actions/free-strike.md) against them.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Is This What They Taught You?
      target: The triggering creature
      type: feature
      usage: Triggered action
    - distance: Melee 5
      effects:
        - effect: |-
            **Trigger:** An enemy within distance uses an ability to reduce damage.
            **Effect:** Ajax makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the target, dealing extra damage equal to twice the amount that was reduced. This extra damage can't be reduced in any way.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Melee
      name: Shieldbreaker Talisman
      target: The triggering creature
      type: feature
      usage: Triggered action
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** A creature uses the Hesitation is Weakness ability.
            **Effect:** Ajax [shifts](../../../movement/shifting.md) up to his speed and can make a [free strike](../../../feature/common/main-actions/free-strike.md). If the target has R < 4, this free strike also makes them [weakened](../../../condition/weakened.md) until the end of their next turn.
      feature_type: ability
      icon: ❗️
      keywords: []
      name: Who's Hesitating?
      target: Self
      type: feature
      usage: Triggered action
    - distance: Ranged 10
      effects:
        - effect: |-
            **Trigger:** Ajax causes a creature within distance to gain ferocity or wrath.
            **Effect:** If the target has I < 4, they use a [signature ability](../../../rule/combat/signature-ability.md) against a target of Ajax's choice.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Your Obsession With Me Betrays You
      target: The triggering creature
      type: feature
      usage: Triggered action
    - cost: 2 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** A creature within 10 squares regains [Stamina](../../../rule/health/stamina.md).
            **Effect:** Ajax regains the same amount of [Stamina](../../../rule/health/stamina.md).
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
      name: You Would Flounder Your Assault?
      target: Self
      type: feature
      usage: Triggered action
    - cost: Villain Action 1
      distance: 5 burst
      effects:
        - roll: Power Roll + 5
          tier1: 11 fire damage; A < 4 [weakened](../../../condition/weakened.md) (save ends)
          tier2: 17 fire damage; A < 5 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 21 fire damage; A < 6 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
        - Weapon
      name: Phoenix Wing King
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 2
      distance: 3 burst
      effects:
        - effect: |-
            **Effect:** Ajax uses the shadow elf eclipse's technique to reduce each target's [surges](../../../rule/resource/surge.md) to 0. Additionally, until the end of the round, Ajax ignores [edges](../../../rule/dice/edge.md) and double edges on any target's abilities, and ignores any nondamaging effects of any target's damage-dealing abilities.
            **Special:** This villain action can be replaced with a villain action from a creature any target has previously encountered.
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
      name: I've Learned Their Tricks
      target: Each enemy in the area
      type: feature
      usage: '-'
    - cost: Villain Action 3
      distance: 7 burst
      effects:
        - effect: '**Effect:** Each target who has I < 5 is knocked [prone](../../../condition/prone.md) and can''t stand until Ajax deals damage to them. For each target not knocked [prone](../../../condition/prone.md), Ajax can move up to his speed toward that target and use Blade of the Gol King against them.'
      feature_type: ability
      icon: ☠️
      keywords:
        - Area
        - Magic
      name: Awe of the Iron Crown
      target: Each enemy in the area
      type: feature
      usage: '-'
free_strike: 11
intuition: 5
keywords:
    - Human
    - Humanoid
level: 11
metadata:
    scc: mcdm.monsters.v1/monster.ajax-the-invincible.statblock/ajax-the-invincible
    source: mcdm.monsters.v1
might: 5
movement: Fly, hover
name: Ajax the Invincible
organization: Solo
presence: 4
reason: 5
role: ""
size: 1L
speed: 7
stability: 2
stamina: "700"
type: statblock
```
