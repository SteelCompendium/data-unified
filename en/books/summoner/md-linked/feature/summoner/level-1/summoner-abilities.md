---
class: summoner
feature_source: summoner
level: "1"
name: Summoner Abilities
scc: mcdm.summoner.v1/feature.summoner.level-1/summoner-abilities
type: feature
---

Your own abilities focus on support and enable you to position and outfit your allies for success.

## Heroic Abilities

Breaking down your [essence](essence.md) into pure power can lead to devastating effects. Your [heroic abilities](../../../rule/general/heroic-ability.md) enable you to punctuate your army's efforts.

### 5-Essence Ability

Choose one [heroic ability](../../../rule/general/heroic-ability.md) from the following options, each of which costs 5 [essence](essence.md) to use. (Quick Build: [Rallying Cry](../../ability/summoner/level-1/rallying-cry.md).)

#### Essence Transfer {data-scc="mcdm.summoner.v1/feature.ability.summoner.level-1/essence-transfer"}

*You pierce your foe and repurpose some of that 'fiber of their being' they weren't using.*

| **Magic, Melee, Strike** | **Main action** |
|--------------------------|----------------:|
| **📏 Melee 1** | **🎯 One creature** |

**Power Roll + Reason:**

- **≤11:** 5 + R corruption damage; 2 charges (see below)
- **12-16:** 8 + R corruption damage; 3 charges
- **17+:** 11 + R corruption damage; 4 charges

**Effect:** You can spend charges to activate one of the following effects. You can activate an effect multiple times. All charges disappear after using this ability.

- 1 charge: You or an ally within your Summoner's Range can spend a [Recovery](../../../rule/health/recoveries.md).
- 1 charge: You or an ally within your Summoner's Range gain a [surge](../../../rule/resource/surge.md).
- 2 charges: You call forth a signature [minion](minions.md) into an unoccupied space within your Summoner's Range.

#### Explosive Parade {data-scc="mcdm.summoner.v1/feature.ability.summoner.level-1/explosive-parade"}

*Your minions swell with energy until they can no longer exist in this realm.*

| **Magic, Ranged** | **Main action** |
|-------------------|----------------:|
| **📏 Summoner's Range** | **🎯 Special** |

**Power Roll + Reason:**

- **≤11:** You summon four [signature minions](minions.md).
- **12-16:** You summon five [signature minions](minions.md).
- **17+:** You summon six [signature minions](minions.md).

**Effect:** The [minions](minions.md) are summoned within distance regardless of your minion maximum and without organizing them into squads. Each newly summoned [minion](minions.md) immediately moves up to their [speed](../../../rule/character/speed.md) toward a creature or object.

If they move adjacent to their target, become targeted by an [opportunity attack](../../../rule/combat/opportunity-attack.md), or stop moving, they explode, dealing 2 [damage](../../../rule/damage/damage.md) to one adjacent creature or object and pushing them 1 square. If a target is affected by two or more minions' explosions, the effects stack. These [minions](minions.md) activate no effects upon death, and you gain no [essence](essence.md) from their deaths.

**Special:** In addition to the [minions](minions.md) summoned as a part of this ability, you can choose to command any number of your [minions](minions.md) within distance, provided they haven't used a main action or maneuver during the [turn](../../../rule/combat/turn.md).

#### Distraction Tactics {data-scc="mcdm.summoner.v1/feature.ability.summoner.level-1/distraction-tactics"}

*Your minions do the work to draw the heat away from your allies.*

| **Magic** | **Free maneuver** |
|-----------|------------------:|
| **📏 Self** | **🎯 Special** |

**Effect:** Until the end of the encounter or until you are [dying](../../../rule/health/dying.md), each [minion](minions.md) under your control during the encounter is the target of the following effect:

The target's [strikes](../../../rule/combat/strike.md) can inflict I < WEAK [taunted](../../../condition/taunted.md) (EoT) to enemies. The [potency](../../../rule/character/potency.md) increases by 1 for each [minion](minions.md) that joined the [strike](../../../rule/combat/strike.md).

#### Rallying Cry {data-scc="mcdm.summoner.v1/feature.ability.summoner.level-1/rallying-cry"}

*"Show them what you're made of!"*

| **Magic, Ranged** | **Maneuver** |
|-------------------|-------------:|
| **📏 3 burst** | **🎯 All Allies** |

**Effect:** Each target chooses between gaining 2 [surges](../../../rule/resource/surge.md) or dealing additional [damage](../../../rule/damage/damage.md) equal to your [Reason](../../../rule/character/reason.md) on their next [strike](../../../rule/combat/strike.md).

#### Shields of Essence {data-scc="mcdm.summoner.v1/feature.ability.summoner.level-1/shields-of-essence"}

*You call forth protective forces to keep you all from harm.*

| **Magic, Ranged** | **Maneuver** |
|-------------------|-------------:|
| **📏 Summoner's Range** | **🎯 Special** |

**Power Roll + Reason:**

- **≤11:** Three creatures
- **12-16:** Four creatures
- **17+:** Five creatures

**Effect:** Until the end of the encounter, each target can use a [free triggered action](../../../rule/combat/triggered-action.md) whenever they take [damage](../../../rule/damage/damage.md) to reduce the incoming [damage](../../../rule/damage/damage.md) by half and then lose this effect.

#### Summoner's Sword {data-scc="mcdm.summoner.v1/feature.ability.summoner.level-1/summoners-sword"}

*You draw your strength from the army you surround yourself with and summon a hot blade of energy and fervor.*

| **Magic, Melee, Strike** | **Main action** |
|--------------------------|----------------:|
| **📏 Melee 3** | **🎯 One creature or object** |

**Power Roll + Reason:**

- **≤11:** R damage
- **12-16:** 2 + R damage
- **17+:** 4 + R damage

**Effect:** This [strike](../../../rule/combat/strike.md) deals an additional 2 [damage](../../../rule/damage/damage.md) for each ally [adjacent](../../../rule/combat/adjacent.md) to you.
