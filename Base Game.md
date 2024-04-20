# Path 2 Victory

The skirmish game inside PF2e

*Path 2 Victory* is a hack of PF2e that turns the expansive roleplaying game into an accessible miniatures skirmish game. 

2024, version 1.40

## Introduction

*Path 2 Victory* is a miniatures skirmish game, which means you gather a handful of miniature figures to represent the creatures in your warband, and you move them around a board with scenery where they fight one another and pursue other objectives. Every figure (called a “creature”) has stats, actions and other details associated with it, which are detailed on its creature card. 

*Path 2 Victory* can be played on a one-inch grid, or you can play without a grid and use rulers and measuring tapes to measure distances. One inch in game represents five feet in the real world.

*Path 2 Victory* is open source and community-built, which means you can take it and adapt it to fit your needs. 

## How was *Path 2 Victory* created?

*Path 2 Victory* is a standalone game, but it is heavily based on – and mostly cross-compatible with – the popular tabletop roleplaying game PF2e. *Path 2 Victory* differs from PF2e in several major ways: 

* Each creature has a points cost associated with it, based on how powerful it is. The more powerful the creatures in your warband, the fewer you are allowed to have. 

* There are rules for deployment, scoring objectives and when the game ends. 

* The [Proficiency without Level](https://2e.aonprd.com/Rules.aspx?ID=1370) variant rule applies, which makes fights between creatures of very different levels still viable. 

* All creatures get two actions (called “action points” in *Path 2 Victory*) instead of three on their turn, which makes the game quicker and reduces maximum movement by a third, allowing for a smaller play area.

* A round consists of players alternating activating creatures (or groups of creatures) until all creatures have acted, at which point the round ends and a new one begins. 

* Conditions have been simplified, and by default creatures loses every condition at the end of their turn. 

* Damage can be of multiple types (5 fire and poison damage, for example).

* Resistance has been turned into a random roll so that all creatures have a chance to do damage to creatures with resistance. 

* There are new rules for cover to simplify the process and allow for a creature to be hit if it provides cover to another. 

Some of the most significant of these changes were originally suggested by GluMaz [on Reddit](https://www.reddit.com/r/Pathfinder2e/comments/fnmo01/pathfinder_2e_as_base_rules_for_skirmish_wargaming/). 

You can import characters, monsters, spells, variant rules, magic items and all the rest into *Path 2 Victory* with a few changes (described in the appendix). 

## ORC License

This product is licensed under the ORC License to be held in the Library of Congress and available online at various locations including paizo.com/orclicense, azoralaw.com/orclicense and others. All warranties are disclaimed as set forth therein.

This product is based on the following Licensed Material:

> **Pathfinder Player Core** © 2023 Paizo Inc., Designed by Logan Bonner, Jason Bulmahn, Stephen Radney-MacFarland, and Mark Seifter. Authors: Alexander Augunas, Kate Baker, Logan Bonner, Jason Bulmahn, Carlos Cabrera, Calder CaDavid, James Case, Eleanor Ferron, Steven Hammond, Joan Hong, Vanessa Hoskins, James Jacobs, Jenny Jarzabski, Erik Keith, Dustin Knight, Lyz Liddell, Luis Loza, Patchen Mortimer, Dennis Muldoon, Stephen Radney-MacFarland, Mikhail Rekun, David N. Ross, Michael Sayre, Mark Seifter, Kendra Leig Speedling, Mark Thompson, Clark Valentine, Andrew White, Landon Winkler, and Linda Zayas-Palmer

If you use our Licensed Material in your own published works, please credit us as follows:

> **Path 2 Victory** © 2024

#                                  How to read a creature card

<img src="img/basilisk.png" style="float:right; width: 2.5in; margin-left:15px;" />Creatures are the living (and unliving) participants of battles*.* Monsters, heroes, undead, bystanders and livestock are all creatures. Each creature is represented by a figure. 

**Name:** The name of the creature, in this case “Basilisk”. 

**Points Cost:** How strong or valuable the creature is in a warband. In most games of *Path 2 Victory,* each player will put together a warband of the same number of points, calculated by adding up the points cost of each creature in their warband. 

**Alignment:** The nine alignments are the factions of *Path 2 Victory,* and each has a corresponding symbol: 

| | Lawful | Neutral | Chaotic |
| --- | ---------------- | -------------- | ----------------- |
| **Good** | ☼ Lawful good    | ✿ Neutral good | ✯ Chaotic good    |
| **Neutral** | 👁️ Lawful neutral | ⚖ True neutral | 🌀 Chaotic neutral |
| **Evil** | ✊Lawful evil     | 👿 Neutral evil | ⛈ Chaotic evil    |

**Size:** How large the monster is. Tiny, Small and Medium creatures occupy a single square (1” by 1”). Large creatures occupy four squares (total 2” by 2”), Huge creatures nine squares (total 3” by 3”) and Gargantuan creatures sixteen squares (total 4” by 4”). Miniatures usually sit on a circular or square base the same width as the space that the creature occupies. 

**Tags:** Any details about the creature, like its body shape or origin. These have no effect by default, but some powers will refer to them (for example, a spell that affects beasts will affect a basilisk).

**Level:** The relative power of the creature, from -1 to 14.

### Stats

Each creature has eight stats.

**Fight:** A creature’s Fight is how likely it is to hit with a strike (like a sword blow, an arrow shot or targeted spells). 

**Armor:** A creature’s Armor is how hard it is to hit with a strike. 

**Power:** A creature’s Power is how difficult its special effects, called powers, are to resist. A dragon’s fiery breath or a medusa’s petrifying glare are powers, as are many offensive spells.

**Saving Throws (Fortitude, Reflex and Will):** These three stats work the same way: they can cause a power to be negated or have a diminished effect.

**HP:** HP (“hit points”) is the maximum amount of damage a creature can take before it becomes helpless and begins to die. The creature’s current HP begins at its maximum, and is reduced as the creature takes damage. If the creature is healed, its current HP increases – but can never exceed the maximum HP. 

When a creature reaches 0 HP, it is dying. It falls prone, gains the helpless status and cannot act except to make recovery checks on its turn (more details under “Conditions and combat statuses” and “Dying”, below). 

**Speed:** Speed is the maximum distance the creature can move with a single Stride action. 

Some creatures have special movement modes, represented with a symbol. These include Flight, Burrowing, Wall Climb and Aquatic and are described under “Movement modes” below.

### Features

The special rules governing a creature, including the special actions that it can take, are described on its card. Each feature has some or all of the following details: 

**Number of Uses:** When a feature is marked with ☐, 🄳 or 🄴 it means that it can only be used that many times in a battle. Each time it is used, check off one of the boxes. Once all boxes have been checked off, it cannot be used again. 

The difference between the types of checkbox only matter for long-term play. In long-term play: 

* ☐ Consumable: After this box is checked off, it is never recovered. The potion is drunk or the scroll burns up.

* 🄳 Daily: After this box is checked off, it remains checked until the creature can rest safely for eight hours. 

* 🄴 Encounter: After this feature is used, it remains checked until the end of the battle. 

**Name:** The name of the feature.

**Action Points:** Some features are actions; these are active features that must be performed by the creature. 

A creature typically gets two action points on its turn, and can spend those action points to perform actions. An action that costs one action point is indicated with one dot (“●”); an action that costs two action points is indicated with two dots (“●●”). 

Some actions are reactions (indicated with ↻); they are performed outside of the creature’s turn. Between each of its turns, a creature can only take one reaction. 

Some actions require zero action points – these are called free actions and are indicated with a hollow dot (“○”). These can only be performed on the creature’s turn, but they do not cost any action points to use.

**Precondition:** Some features, especially reactions, may have preconditions that must be met before they can be used. For example, the basilisk’s *petrifying glance* can only be used if and when a creature within 6 squares and within line of sight begins its turn.

A feature does not *have* to be used just because its precondition is met. 

**Range/Area:** Some features have a range/area. This is how far away an eligible target can be and how large and what shape the effect is. “Melee” means a single target in an adjacent square (within one square, up, down, left, right or diagonal). “Ranged #” means a single target within that many squares. Others, like “Cone” and “Blast”, target an area rather than a creature and are explained in more detail later.

**Strike:** If an action is a strike, it will say so here. 

When a creature makes a strike, it rolls a 20-sided die (1d20) and adds its Fight. If the result equals or exceeds the target’s Armor, the strike “hits”, meaning that it has the effect. 

**Effect:** The effect or rules of the feature. For a strike, this effect only applies if the strike hits. 

Some effects can be avoided or reduced in effect if the target fails on a saving throw. The entry will say something like “Will negates” or “Reflex half”. The target rolls a 20-sided die (1d20) and adds the specified saving throw (Fortitude, Reflex or Will). If the result equals or exceeds the attacker’s Power, then the effect is negated or the damage taken is halved (as applicable). 

Some features give a condition as an effect (for example, “slowed”, “stunned” or “rattled”). Conditions are described in an appendix.

### Standard features

At the bottom of a creature’s card are listed in italics certain common features, without details on how they work. 

If a skill name is listed (like Acrobatics, Occultism or Society), it means the creature is trained in that skill. At certain times, for example to claim an objective or peform a physical feat like jumping or climbing, a creature must succeed on a skill check to be successful. To make a skill check, roll 1d20 and add the applicable saving throw. Subtract 5 if the creature is not trained in the skill. If the result exceeds the Power specified, the skill check is successful. 

“Immune”, “resist” and “weak” followed by a damage type indicate that the creature takes no damage, less damage or more damage from attacks doing that type of damage. Immune is also used for conditions; it means that the creature does not gain that condition, even if it otherwise would. 

Other common features included in this shorthand are described later. 

# Getting started

## What you need to play

* Several miniatures each

* At least one 20-sided die (a “d20”) and one six-sided die (a “d6”)

* Some tokens to track conditions, damage, etc.

* A grid map of about 24 by 18 squares and a way to draw or mark terrain and objectives. 

## Building a warband

There are several ways you can put together a *Path 2 Victory* warband. 

1. **Narrative Play:** Each player chooses the creatures that are appropriate for the story. You can play *Path 2 Victory* as a roleplaying game, or use it to model a larger skirmish or battle in an existing PF2e campaign. 
2. **Balanced, Unlimited Play:** Players agree on a number of points for each warband. Each player selects creatures with total point costs equal to or below the number of points agreed. 
3. **Balanced, Limited Play:** As unlimited play, but each player selects an alignment, and then selects creatures of that alignment or adjacent alignments (see below).
4. **Random Box Recruitment:** Each player buys a couple of boxes of random pre-painted miniatures, and then selects creatures from their assortment with total point costs equal to or below 200 (or other agreed number). 
5. **Campaign Play:** Players assemble and cultivate a warband over one or more adventures, with each encounter potentially changing their warband. Basic details for campaign play are described in an appendix. 

### Single most expensive creature

In all forms of play except “Narrative Play”, no single creature can cost more than half of a warband’s points. For example, a warband of 200 points can contain a young red dragon (90 points) but not a crag linnorm (192 points).

### Alignments

There are nine factions in *Path 2 Victory:* the nine alignments. Each player chooses an alignment for their warband, but can also recruit those of “adjacent” alignments and True Neutral creatures. For example, a Lawful Evil warband can also include Lawful Neutral, Neutral Evil and True Neutral creatures. A Neutral Good warband can also include Lawful Good, Chaotic Good and True Neutral creatures. A True Neutral warband can also include Neutral Good, Lawful Neutral, Chaotic Neutral and Neutral Evil creatures. 

### Points by level

The cost of a creature is calculated based on its level, plus a certain amount for every upgrade it has (if any). 

##### Table 1: Points cost by level

| **Level** | **Cost** | **Upgrade cost** | **Level** | **Cost** | **Upgrade cost** |
| --------- | -------- | ---------------- | --------- | -------- | ---------------- |
| **-1**    | 9        | 2                | **7**     | 48       | 8                |
| **0**     | 12       | 2                | **8**     | 60       | 10               |
| **1**     | 14       | 3                | **9**     | 72       | 12               |
| **2**     | 18       | 3                | **10**    | 90       | 15               |
| **3**     | 21       | 4                | **11**    | 108      | 18               |
| **4**     | 26       | 5                | **12**    | 135      | 23               |
| **5**     | 32       | 6                | **13**    | 160      | 27               |
| **6**     | 40       | 7                | **14**    | 192      | 32               |

#### Upgrades

Some creatures can take magic items or other add ons, or have upgrades specified on their creature card. Players can give one or more of these upgrades with a creature of that type, but pay an extra points cost for each upgrade based on the creature’s level (as shown in the table above). If a player brings multiple of the same type of creature, they can upgrade some and not others, or all.

# Setting up a standard game

*Path 2 Victory* can be played in many different ways, with different terrain setups, deployment rules, victory conditions and so on. What is described below are the standard rules, which can be modified by agreement of the players or if playing a particular scenario. 

1. Agree on a points cost for the game

2. Each build a warband of that points cost or lower

3. Lay out a battle grid of appropriate size

4. Alternate placing terrain

5. Determine how many objectives are in play and alternate placing objectives

6. Roll to see who chooses their deployment zone first. Each player chooses a deployment zone and deploys their warband in that zone. 

## Victory condition

Players are competing for whose warband can win the most victory points, mostly from objectives. 

The player who has the most points worth of creatures in their warband still in play at the end of the game wins an additional +2 points, or +4 points if their opponent or opponents have no creatures still in play. 

## Battle grid 

Games of *Path 2 Victory* are played on a grid of one-inch by one-inch squares. 

Small games of *Path 2 Victory* (150 points or fewer per side) can be played on a grid of about 24 squares by 18 squares. Each square is 1 inch by 1 inch, making the grid 2 feet by 1 ½ feet. Players deploy in opposite corners, up to 6 squares away from the corner. 

Medium games (500 points or fewer per side) should be played on a grid of about 36 squares by 24 squares (3 feet by 2 feet). Players deploy in opposite corners, up to 6 squares away from the corner. 

Large games (more than 500 points per side) should be played on a grid of about 48 squares by 36 squares (4 feet by 3 feet). Players deploy on opposite long edges, up to 6 squares away from the edge. 

If you want to play without a grid, see the appendix for details. 

## Terrain

Players alternate placing pieces of terrain (see the Terrain chapter for more details) until about a third to a half of the board is filled with terrain. Everywhere else is open ground (squares with no special terrain traits). 

Terrain tiles are standardized terrain pieces that are all 8 squares by 5 squares in dimensions. Some are described in the appendix. You can play *Path 2 Victory* by using terrain tiles instead for a more consistent and balanced experience. 

## Objectives

Objectives are desirable things on the board that warbands may want to interact with or control – anything from treasure chests and switches to activate or deactivate traps to wild animals and prisoners about to be sacrificed. Unless otherwise specified, objectives are difficult and obstructing terrain (see the Terrain chapter for more details), and a creature cannot end its move standing on the objective. 

Each objective has a skill listed and a Power, usually Power 15. If a creature adjacent to the objective Interacts with it, they make a skill check. On a success, they claim the objective for their warband. A creature can claim an unclaimed objective or one claimed by another warband.

At the end of each round, each warband scores 1 Victory Point for each objective they currently have claimed (whether they claimed the objective in that round or an earlier round).

Players can choose objectives with special effects associated with them. 

### Standard objectives

Roll 2d6 and take the higher result. Players alternate placing objectives on the map until they have placed that many objectives. Players choose objectives from the standard objectives below. No type of objective can be placed more than once. 

Each objective is associated with several skills. 

| **Objective**      | **Skill 1** | **Skill 2**  | **Skill 3**  | **Skill 4** |
| ------------------ | ----------- | ------------ | ------------ | ----------- |
| **Book**           | Arcana      | Lore         | Occultism    | Religion    |
| **Device**         | Arcana      | Crafting     | Thievery     | Medicine    |
| **Exotic Flower**  | Medicine    | Nature       | Survival     | Thievery    |
| **Golem’s Eye**    | Acrobatics  | Crafting     | Stealth      | Thievery    |
| **Notable**        | Deception   | Diplomacy    | Intimidation | Society     |
| **Savage Beast**   | Athletics   | Intimidation | Nature       | Performance |
| **Spectral Haunt** | Diplomacy   | Occultism    | Performance  | Religion    |
| **Willful Sprite** | Deception   | Society      | Lore         | Survival    |

 

When an objective is placed, roll 1d6 to determine its Power and which skills can be used to claim it. 

| **d6** | **Result**                    |
| ------ | ----------------------------- |
| **1**  | Skill 1 or 2, Power 15        |
| **2**  | Skill 2 or 3, Power 15        |
| **3**  | Skill 3 or 4, Power 15        |
| **4**  | Skill 1 or 4, Power 15        |
| **5**  | Any of the 4 Skills, Power 15 |
| **6**  | Any of the 4 Skills, Power 20 |

 

## Deployment

Deployment takes place in the deployment zones specified by the size of the battle grid. 

At the start of the first round, each player rolls a d20. The player that rolls highest chooses their deployment zone, and places all of their creatures in that zone. Then, clockwise from that player, each player chooses a zone and places all of their creatures. 

In other words, the player who picks last gets to deploy their creatures knowing how the other players are deployed. This hopefully compensates them for having fewer options (or just one option) for their deployment zone. 

| **Points per warband** | **Battle grid size**     | **Deployment zones**                                 |
| ---------------------- | ------------------------ | ---------------------------------------------------- |
| **150 or fewer**       | Small: 24 by 18 squares  | Up to 6 squares from the corner, in opposite corners |
| **500 or fewer**       | Medium: 36 by 24 squares | Up to 6 squares from the corner, in opposite corners |
| **More than 500**      | Large: 48 by 36 squares  | Up to 6 squares from the edge, in opposite edges     |

For free-for-all games where there are three or four players all fighting each other, go one size larger and always deploy in corners.

# Rounds and turns

A *Path 2 Victory* game takes place over several rounds. 

Every creature gets one turn to act each round. Players alternate activating creatures from their warband to take a turn. Once a creature has completed its turn, the next player gets to activate a creature to take their turn, and so on until every creature has been activated. If a player has activated all of their creatures, skip them until the rest of the players have activated all of their creatures.

Once all creatures have been activated, the round ends and a new one begins. The first player to activate is the one to the left of the player who was first to activate in the previous round. 

### Roll to see who goes first

Each player rolls 1d6. Whichever gets the higher result goes first in round 1 (“first player”). Then, whichever player activated a creature last in the earlier round goes first in subsequent rounds.

### Round limit

If both players agree to play to a fixed time limit, at the end of round 6 and every round after, roll 1d6 and add the number of rounds that have occurred. If the result equals or exceeds 12, the game ends immediately. Otherwise it continues. 

## Taking a turn

The player activates a creature in their warband that has not yet been activated this round. 

### Two action points

At the start of each of its turns, a creature’s action points (AP) are set to 2. It can spend these action points on one or more actions: actions cost either 0 AP (○, also called free actions), one AP (●) or two AP (●●). 

A creature cannot save its action points for a later turn. If it does not spend them, it loses them. 

Unless otherwise specified, a creature can take a particular free action only once per turn. Actions costing 1 AP that can only be performed once per turn are therefore written “●○” to indicate that they only cost 1 AP, but they cannot be performed twice in a round. 

### Group activation

A player can activate a group of creatures in their warband at once. The creatures must have spent the whole game adjacent to at least one other creature in the group. They must all spend their action points on the same actions and in the same order, though the details can be different (e.g. if they all Stride, they can move in different directions; if they Strike, they can choose different targets or use different weapons). However, if the group breaks up, all the creatures in it must then be activated separately; the group cannot reform. 

### End of turn

At the end of a creature’s turn, if it is suffering from persistent damage it takes that much damage. Its persistent damage is then reduced by 5 (or removed altogether if it is already at 5). 

The creature then loses all conditions it is experiencing. 

## Universal actions

The following are actions that any creature can take, unless otherwise specified. 

**Crawl** ● Move 1 square while prone.

**Drop Prone** ● Become prone.

**Escape** ● Remove one condition currently affecting the creature.

**Grapple** ● Choose an adjacent target. Make a Fight roll. They make a Fortitude save (Power equal to the Fight roll result). The target can’t be more than one size larger than the creature. On a failure, it is grabbed.

**Interact** ● Ready an item, open a door, manipulate an item or claim an objective.

**Leap** ● The creature jumps over one square or over a one-square wide gap. 

**Long Jump** ●● The creature moves up to their Speed in squares, then makes an Athletics skill check. Divide the result by 4 (round down): that is how many squares they jump over or how wide a gap they can jump over. If that is not enough, they fall. 

**Ready** ●● Your turn ends. Before your next turn, you can take a free action or 1-AP action as a reaction, at any time. 

**Shove** ● Choose an adjacent target. Make a Fight roll. They make a Fortitude save (Power equal to the Fight roll result). The target can’t be more than one size larger than the creature. On a failure, it is pushed 1 square. 

**Stand** ● The creature stands up from prone. If a creature is already in the standing creature’s space, either the standing creature or the original creature move to the nearest empty space (original creature’s choice). 

**Step** ● The creature moves 1 square. This movement does not trigger reactions.

**Stride** ● The creature moves up to their Speed in squares.

**Strike** ● Make an attack with a melee or ranged weapon. Additional attacks are subject to the multiple attack penalty. 

**Trip** ● Choose an adjacent target. Make a Fight roll. They make a Reflex save (Power equal to the Fight roll result). The target can’t be more than one size larger than the creature. On a failure, it falls prone. 

## Reactions

Outside its turn, a creature can take a reaction. A creature can take at most one reaction until it next activates. 

The following are reactions that are commonly available. They must be listed on a creature card to be used by that creature. 

### Common reactions

**Attack of Opportunity** ↻ If a creature within your reach casts a spell, moves out of reach of your attacks or makes a ranged attack: Make a melee Strike against the triggering creature.

**Retributive Strike** ↻ If an enemy within 3 squares of you does damage to an ally within 3 squares of you: Reduce the damage taken by 2 + your level. If the enemy is within reach, make a melee Strike against the triggering creature. 

**Ferocity** ↻ If you would be reduced to 0 HP or below: Roll 1d6. On 4–6, set HP to 1 instead.

**Shield Block** ↻ If you take slashing, piercing or bludgeoning damage: Reduce damage by the specified amount. 

# Movement and positioning

When a creature Strides or Steps (or takes another action that allows them to move), they move a number of squares, as chosen by their player. They cannot move more than their Speed (if Striding) or more than 1 square (if Stepping). They can move fewer squares than they are entitled to. 

Creatures cannot move through solid terrain (described below) or through the spaces of enemy creatures, and they cannot end their movement on spaces occupied by allied creatures. 

Some movement, like moving through difficult terrain or moving diagonally, costs more movement. If a creature Strides or Steps two or more times consecutively, they add up all the available movement for the purpose of these calculations. 

For example, a creature with Speed 5 who Strides twice can cross five squares of difficult terrain if they Stride twice. A creature with Speed 5 who Strides once can only cross two squares of difficult terrain, and the extra square of movement goes to waste unless there is open ground they can move on.

### Diagonal movement

Because moving diagonally covers more ground, count that movement differently. The first square of diagonal movement a creature makes in a turn counts as 1 square, but the second counts as 2 squares, alternating between the two thereafter. For example, as a creature moves across 4 squares diagonally, count 1, then 2, then 1, and then 2, for a total of 6. A creature’s total diagonal movement is tracked across all of their movement during their turn, but resets at the end of their turn.

A creature can move diagonally past an enemy creature’s space – this does not count as passing through their space – and past difficult terrain. 

A creature cannot move diagonally past solid terrain, since it represents a hard corner. They must move around it. 

### Unwilling movement

A creature can be pulled, pushed or shunted. Move them that number of squares. They cannot enter squares occupied by other creatures (allies or enemies). A push must move the creature further away from the attacker or point of origin with each square moved; a pull must move the creature closer to the attacker or point of origin with each square moved. A shunt can move them closer or farther, or no closer or farther.

### Movement modes

Some of these movement modes allow creatures to ignore terrain or other creatures. The creature must still end its turn in an unoccupied space.

**≋ Aquatic:** The creature ignores the negative effects of water terrain (shallow and deep). 

**🕳 Burrowing:** The creature can choose to ignore the effects of terrain, auras and enemy creatures during its movement. The creature “resurfaces” when it ends it movement, at which point it can be affected by terrain, auras and creatures. Burrowing creatures still fall if they enter a void. 

**☁ Flight:** The creature can choose to ignore the effects of terrain (except solid terrain), and move through spaces occupied by enemy creatures.

**🌳Wall Climb:** The creature is not off-guard while on an incline and can climb or stay on any incline however steep. 

While adjacent to solid terrain, the creature can (a) ignore the effects of terrain (except solid terrain) and (b) move through spaces occupied by enemy creatures. (In the fiction, the creature is climbing along the wall out of the way.)

**✪ Teleportation:** The creature ignores the effects of terrain, auras and enemy creatures during its movement, and can move through spaces occupied by enemy creatures. The creature reappears when it ends it movement, at which point it can be affected by terrain, auras and creatures.

### Carrying objects

During a scenario, a creature will sometimes end up carrying something, for example a sacred idol. 

While carrying a Light Load, a creature has the encumbered condition. While carrying a Heavy Load, a creature has both the encumbered and slowed conditions. 

Dropping a Load is a free action. Picking up an unattended Load requires the Interact action (1 AP). 

### Vertical movement

Movement modes like Flight, Burrowing and Wall Climb that assume vertical movement just allow a creature to ignore terrain, not to physically move higher up (and potentially out of range). 

**Incline:** While standing on an incline, ladder or the like, a creature is off-guard. 

If an incline is too steep, creatures cannot traverse it at all without the aid of ropes, ladders or the like, or the Wall Climb movement mode. Some creatures cannot climb at all (like large mammals). Use your discretion. 

**Ascending:** To ascend a vertical distant costs 1 square per square of height gained. For example, climbing a 3-square tall ladder and then stepping off it costs 4 squares of movement (three for the vertical movement and one for the horizontal movement). 

**Descending:** Descending costs no extra movement beyond the horizontal movement involved. 

**Falling:** A creature that falls 2 squares or more takes 5 damage per 2 squares it falls. If it takes damage, it falls prone at the bottom. Creatures with Flight do not fall, and creatures with Wall Climb only fall until they become adjacent to solid terrain. 

A creature falls if there is no rope, ladder or the like by which to descend a steep or sheer drop, or if they are forced off a steep or sheer drop by unwilling movement. 

### Narrow spaces and tight gaps

A creature can cross a space narrower than their own space. If it has a sheer drop on one or both sides, they must make an Acrobatics check (Power 15) once per action. If they fail, they lose their movement. If they critically fail, they fall. While on a narrow space, a creature is off-guard. Each time a creature is hit by an attack or fails a save, they must make an Acrobatics check (use the attacker’s Power) or fall. 

A creature can squeeze through a space half its base width or wider, but treats every square as difficult terrain. 

# Terrain

Pieces of terrain represent anything from forests, cliffs, giant skeletons, castle ruins or fields of poisonous mushrooms to rooms in a building or dungeon. Each square in a piece of terrain is either open ground (a flat space with no special features) or has one or more terrain traits, like “concealing” for a cloud of smoke or “encumbering” for sticky spiderwebs. 

A terrain piece can all have the same terrain trait (every square in the piece is filled with mushrooms, making it difficult terrain, for example) or different squares in the piece can have different traits (a ruin might have stone walls with the solid trait; piles of rubble with the difficult trait; and a flagstone floor which is open ground). 

A square can have one or more traits attached. For example, vegetation is obstructing difficult terrain. The cobwebs of giant spiders are encumbering difficult terrain. Fog or mist is concealing. Pitch darkness is opaque. Walls are solid terrain. 

As well as filling squares, terrain can run along the border between squares. For example, a fence (difficult, obstructing) may run between two squares. Creatures can stand in the squares on either side of the fence. 

## Terrain traits

* ☁ **Concealing:** Grants concealment to creatures within it. A creature ignores the square(s) of concealing terrain it is standing on when determining concealment (whether as the attacker or defender).

* 〜 **Deep water:** Deep water can be traversed using movement, but at half speed. While swimming, a creature is off-guard. Shallow water is just a variety of difficult terrain. 

* △ **Difficult:** It costs one extra square to enter each square of difficult terrain, or to cross difficult terrain between squares. 

* ▭ **Door:** An adjacent creature can open or close a door by Interacting. While closed, doors are solid terrain. 

* ➲ **Directional:** The terrain pushes creatures in a particular direction. Moving in any other direction is difficult terrain. At the end of each round, all creatures on the directional terrain are moved 2 squares in the set direction. 

* 🕸 **Encumbering:** If a creature enters encumbering terrain or ends their turn on it, they are encumbered.

* ☠ **Hazardous:** When a creature enters a hazard, they take 5 damage. At the end of a creature’s turn, they take 5 damage if they are on a hazard. Damage type depends on the hazard (piercing for a pit of spikes, fire for a fire pit, acid for a pool of acid, etc).

* ♣ **Obstructing:** Grants cover. A creature ignores the square(s) of obstructing terrain it is standing on when determining cover (whether as the attacker or defender). 

* ▦ **Opaque:** Blocks line of sight. A creature ignores the square(s) of opaque terrain it is standing on when determining line of sight (whether as the attacker or defender).

* ■ **Solid:** Solid terrain blocks movement, line of sight and areas of effect.

* ⨂ **Teleportation circle:** All Teleportation Circles are adjacent to all other Teleportation Circles on the map. 

## Terrain types

To add more depth to your terrain, you can specify what *causes* your terrain to be concealing, difficult, obstructing, hazardous or the like. 

For example, in the caldera of a volcano the difficult terrain may be rubble, the concealing terrain smoke and the hazardous terrain magma. In an icy waste, the difficult terrain may be ice and the concealing terrain snowfall. 

Creatures may ignore some types of terrain but not others, for example in PF2E red dragons can see through smoke, winter hags can see through snowfall and some druids can move freely through undergrowth and vines. 

| **Terrain traits**         | **Terrain type**                               |
| -------------------------- | ---------------------------------------------- |
| **Concealing**             | Smoke, snowfall, dim light.                    |
| **Difficult**              | Rubble, mud, ice.                              |
| **Difficult, obstructing** | Fence, low wall, undergrowth, curtain.         |
| **Directional**            | Buffeting winds, river current, conveyor belt. |
| **Encumbering, difficult** | Cobwebs, vines, quicksand.                     |
| **Hazardous**              | Gouts of flame, superheated steam.             |
| **Hazardous, difficult**   | Magma, pool of acid, stone spikes.             |
| **Opaque**                 | Darkness.                                      |

# Attacks and powers

Strikes and offensive powers are called attacks, and the creature making a strike or using a power is called the attacker. The creatures potentially affected by the strike or power are called targets. 

## Making a strike 

When a creature makes a strike, they make a Fight roll (roll 1d20 and add their Fight).

Compares the result of the Fight roll to the target’s Armor. If the Fight roll equals or exceeds the Armor, the strike hits. Otherwise, it misses.

If the Fight roll is a natural 20 (the die result is 20, ignoring modifiers) or the result exceeds the Armor by 10 or more (a result of 27 or more against Armor 17, for example), it is a critical hit. It hits and does double damage.

Some offensive spells involve strikes. Others are powers (described below).

#### Ranged attack in melee penalty

A creature that is within an enemy’s reach suffers a -2 penalty to their Fight roll with ranged strikes. 

#### Multiple attack penalty

After a creature concludes an action that included a Fight roll, their subsequent Fight rolls *that turn* suffer a -5 penalty. After a creature concludes a second action that included a Fight roll, their subsequent Fight rolls *that turn* suffer a -10 penalty. 

For example, a creature takes the Multiattack action and makes two strikes. After both strikes are resolved, it takes the Strike action and makes one strike. *That* strike suffers a -5 penalty. Then it takes the Shove action. *That* Fight roll suffers a -10 penalty. 

## Using a power

When a creature uses a power that includes a saving throw (including most offensive spells), each target rolls a saving throw (rolls 1d20 and adds their Fortitude, Reflex or Will) and compares the result to the caster’s Power. If the saving throw equals or exceeds the Power, the power is negated or has a diminished effect. If the saving throw is less than the Power, the power succeeds and has the full effect. 

If the saving throw is a natural 1 (the die shows a 1, before modifiers) or it is below the Power by 10 or more (a result of 7 or less against Power 17, for example), it is a critical failure. The target takes double damage from the power. 

### Saving throw types

**[Saving throw] negates:** If a saving throw is listed as “Fortitude negates”, or the like, it means the attack has no effect on that target if the target makes a successful saving throw, including doing no damage. 

**[Saving throw] half:** If a saving throw is listed as “Will half”, or the like, it means on a successful saving throw the power does half damage, and on a critical success (the saving throw is above the Power by 10 or more), it does no damage. 

Round damage down to the nearest 1 (for damage values after halving of 9 or less) or down to the nearest 5 (for damage values after halving of 10 or more). 

## Targeting 

To target a creature, an attacker needs (a) the target to be within range of the attack, (b) line of sight to the target and (c) line of effect to the target. 

To target a point of origin for an area of effect at range (for example, a burst 2 within range 10), an attacker needs (a) line of sight to the point of origin and (b) line of effect to the point of origin. The area of effect extends to its full extent, unless intercepted by solid terrain. 

### Range

When measuring distances in squares, count the squares from the first square adjacent to the attacker to the square that includes the target (with diagonals alternating between costing 1 square and 2 squares). If the total is less than or equal to the range, the target is within range. 

Ranged weapons often have two ranges listed, for example “Ranged 12/24”. The first is the short range, at which the weapon can be used without penalty. The second is the long range; attacks at this range suffer a -2 penalty. 

### Line of sight 

Melee and Ranged attacks require the attacker to have line of sight to the target – in other words, to be able to see the target. 

If the attacking player can draw a line between any point on the space their attacking figure occupies and any point on the space the target occupies, without it passing through solid or opaque terrain, the attacker has line of sight. 

Area effects ignore opaque terrain: they have line of sight if they do not pass through solid terrain.

### Cover 

Cover refers to things that physically interfere with the attack. Foliage, a low wall and a fellow combatant are all forms of cover. Cover applies against strikes (attacks that target Armor) and against other attacks that target Reflex.

The attacking player chooses the point in the attacking creature's space from which the attack originates. The defending player then chooses any point in the target's space. Imagine a line between those two points. Use the same point on the attacker's space for each target if there are multiple targets. 

Make a cover check for:

* Each piece of obstructing, solid or opaque terrain that the line passes through.

* Each figure of the same size or smaller than both attacker and defender that the line passes through.

In order from closest to the attacker to farthest from the attacker. If terrain is in the same square as a figure, roll for the terrain first. 

A cover check involves rolling 1d6. The first time the attacker rolls a 1, the attack targets the terrain or figure instead of the original target. If the thing in the way was already a target of the attack, they are only targeted once (so a soldier who provides cover against a dragon’s fiery breath is only affected once by that breath, even if they end up saving others behind them from being targeted). 

If no 1s are rolled, the original target remains the target. 

**Adjacent cover:** Defenders do not benefit from and attackers do not suffer from cover in their space. Attackers do not suffer from cover of less than one square in width that they are adjacent to (for example, archers can shoot out of arrow slits and duelists can swing swords over fences and low walls without penalty). 

**Larger creatures:** In the case of creatures that occupy multiple squares, the player who controls the attacking figure chooses which square to draw from of those the attacking figure occupies. 

### Concealment

Concealment refers to things that obscure the attacker’s view of the target, without physically blocking the attack. Fog, darkness and illusions are all forms of concealment. 

Concealment works like cover, except it only applies to strikes (attacks that target Armor), not attacks that target Reflex. 

Use the same line as for cover. Make a concealment check for: 

* Each piece of concealing terrain that the line passes through.

* The figure, if it is hidden or otherwise concealed by a spell or effect. 

Make the checks in order from closest to the attacker to farthest to the attacker. 

A concealment check involves rolling 1d6. The first time the attacker rolls a 1, the attack misses. 

If no 1s are rolled, the original target remains the target. 

**Larger creatures:** In the case of creatures that occupy multiple squares, the player who controls the attacking figure chooses which square to draw from of those the attacking figure occupies. 

### Height

Creatures are as high as they are wide (for example, a Large creature occupies 8 1-inch cubes: it is 2” wide by 2” long by 2” tall). Where elevation is an issue for determining line of sight, cover or concealment, draw the lines from points in these cubes rather than from ground level. This can mean figures of smaller sizes now grant cover or figures of larger sizes no longer grant cover depending on how the elevation changes their heights. 

### Adjacency

A creature is adjacent to another creature, or to terrain, an objective, etc., if it is in the next square over (orthogonally or diagonally).

By default, a Melee attack can target adjacent creatures. If there is a number after Melee, like Melee 2, it is a reach attack and can be used against creatures that many squares away (with adjacent squares counting as “square 1”). 

## Areas of effect

Areas are measured in the same way as movement, but areas’ distances are never reduced or affected by difficult terrain. They are blocked by solid terrain. 

If any of a creature’s space is within the area of effect, the creature is affected (even if other parts of their space are outside of the area of effect). 

**Emanations:** An emanation power is measured from the sides of the origin space, usually the user’s own space. An emanation 1 power thus affects all adjacent squares to the user. 

**Bursts:** A burst power is measured from a single corner of a square within the range of the effect, spreading in all directions to a specified radius. 

**Cones:** A cone power is measured from a single edge or single corner of the origin space, usually the user’s own space. It covers a quarter-circle of space. 

**Lines:** A line power is measured in a straight line from a single corner of the origin space. 

<img src="img/aoe.png" style="width: 700px;" />

# Hit points and damage

Hit points measure how far or close a creature is to becoming helpless and beginning to die. 

When a creature takes damage, subtract that amount from their current hit points (just called “hit points” or “HP”). At the start of each battle, a creature’s current hit points are equal to its maximum hit points. 

### Healing

When a creature is healed, they reduce the damage that they have taken/increase their current hit points by that value. A creature cannot be healed beyond its maximum hit points. 

### Dying

When a creature is reduced to 0 HP or lower, it gains the helpless status and falls prone. While its HP are 0 or lower, it is dying. 

Each time a dying creature’s turn ends, and each time it is hit by a strike that damages it, it makes a recovery check: it rolls 1d6. On a 1–3, it is eliminated and its figure is removed from play. 

If a dying creature is healed, their current HP becomes the value of the healing provided (for example, a dying creature on -8 HP healed 5 hit points sets their current HP to 5). They cease to be helpless (but they are still prone). 

### Looting

Keep track of where each creature is eliminated. A creature on or adjacent to that space can Interact with the body to take one item from it, or to begin carrying the body if the body is the same size or smaller than the creature. A body is a Heavy Load if it is the same size as the creature carrying it, or a Light Load if it is smaller. 

### Damage types

There are 12 types of damage: Bludgeoning, piercing, slashing, acid, cold, fire, electricity, sonic, mental, poison, void and vitality. 

Vitality damage only damages undead creatures and void damage does not damage undead or construct creatures.

Damage can have two or more types, for example “5 fire and electricity damage”. 

### Temporary HP

Creatures can acquire temporary HP, separate to their current HP and not limited by their maximum HP. When a creature takes damage, subtract it from their temporary HP first. 

Temporary HP does not stack; if a creature gets temporary HP from two sources, use the higher value. 

### Immunity, resistance and weakness

**Immune:** A creature takes no damage from an attack of a damage type to which they are immune, even if it involves other damage types as well.

**Resist:** When a creature with resistance to a particular damage type takes damage of that type, roll the specified number of d6s. For each 4+ result, reduce the damage it takes by 5. 

If a creature takes damage of multiple types, only roll the higher resistance value. 

*For example, a creature with resist cold 2d6 takes 15 cold and acid damage. Their player rolls a 5 and a 2, reducing the damage by 5.* 

**Weak:** A creature with weakness to a particular damage takes that much additional damage each time it takes damage of that type, even if the damage is of other types as well. Choose the higher value of weakness if the creature is weak to multiple types of damage from that attack. 

If a creature both resists and is weak to a source of damage, roll resistance first. If it still takes damage, add the extra damage from its weakness. 

### Persistent damage

A creature takes persistent damage at the end of its turn, then it reduces by 5 (from persistent fire damage 10 to persistent fire damage 5, for example). Once it reaches 0, it is removed. 

Persistent damage of the same type does not stack. Persistent damage of different types does stack. 

# Spells

Spells are discrete magical effects. 

Every creature that can cast spells is described as a caster of a particular tradition and rank. 

The traditions are occult, arcane, divine and primal. These determine which spells the caster can learn, but have no other effect in game.

A caster’s rank describes how powerful the spells they cast are, and what the maximum rank of spell they can cast is. For example, a Caster Rank 7 can cast spells of up to rank 7. 

## Interpreting spells

Spells are described as actions, with a particular action point cost. If multiple actions are described in the one spell, only one of them can be taken. For example, the *heal* spell reads

● Melee: Heal 5 damage.  
 *Heighten:* Heal +5 damage per rank.  
●● Ranged 6: Heal 10 damage.  
*Heighten:* Heal +10 damage per rank.

That means that the caster can cast the spell by either spending 1 action point or 2. If they spend one action point, they heal 5 damage at melee range (usually, adjacent squares only). If they spend two action points, they can heal 10 damage at a range of 6 squares. A caster of higher rank can heal more damage (as described below). 

If a spell is listed as a strike, then the caster makes a Fight roll and compares it to the target’s Armor. Only if the attack hits does the spell’s effect take place. Otherwise, a spell’s effect is automatic (though the target may avoid the effect, for example by making a saving throw that negates it). 

### Rank and heightening

Spells have a minimum rank, which is the lowest rank of caster that can cast them. 

When a spell of a particular rank is cast by a caster of higher rank, it can have a more powerful or different effect. This is described under the spell’s “Heighten” entry. 

Rank 0 spells are called cantrips, and can usually be cast any number of times (indicated with an infinity sign: ∞). Sometimes spells of higher ranks also be cast any number of times. 

### Sustaining

A spell that has a sustain entry can be cast again on the caster’s next turn, for that many action points. It does not cost any uses of the spell to sustain. A spell can be sustained indefinitely, unless otherwise mentioned, but if it is not sustained in a given turn, it ends (you cannot sustain a spell one round, then not sustain it the next, then sustain it the round after). 

### Prepared and spontaneous casters

There are typically two types of caster: prepared casters and spontaneous casters. Prepared casters have a list of spells, each of which can be cast a certain number of times. Spontaneous casters can cast a certain number of spells of each rank, choosing from all applicable spells they know. 

For example, the Kobold Sorcerer 1 is a spontaneous caster. They can cast three spells, choosing from *bane, fear* and *charm.* They could choose *bane* all three times. 

> 🄳🄳🄳 Bane, fear, harm; ∞ Acid splash, shield; 🄴: Glutton's jaws

The Kobold Druid 1 is a prepared caster. It can cast *heal* once and *magic weapon* once. 

> 🄳 Heal, 🄳 Magic weapon (animal, beast, fungus, plant or dragon only); ∞ Ray of frost, tanglefoot; 🄴 Heal (animal or beast only)

# Other rules

## Skill checks 

The rules will say when a creature needs to make a skill check. To do so, roll 1d20 and add the corresponding saving throw bonus. If they are not trained in the applicable skill, they suffer a -5 penalty. Compare the result to the specified Power for that skill check. If it is equal to or greater than the Power, the creature succeeds. 

Unless otherwise mentioned, mindless creatures can only make skill checks for skills they are trained in. The same is true for animals and beasts unless they are also humanoids, can cast spells or strike with a weapon. 

| **Skill**        | **Saving throw** | **Skill**       | **Saving throw** |
| ---------------- | ---------------- | --------------- | ---------------- |
| **Acrobatics**   | Reflex           | **Nature**      | Will             |
| **Arcana**       | Will             | **Occultism**   | Will             |
| **Athletics**    | Fortitude        | **Performance** | Will             |
| **Crafting**     | Will             | **Religion**    | Will             |
| **Deception**    | Will             | **Society**     | Will             |
| **Diplomacy**    | Will             | **Stealth**     | Reflex           |
| **Intimidation** | Will             | **Survival**    | Will             |
| **Lore**         | Will             | **Thievery**    | Reflex           |
| **Medicine**     | Will             |                 |                  |

 

## Commanders, minions and mounts

A commander is a creature that leads other creatures, called minions. The minions act on their commander’s turn (they can take actions in any order, including for example the commander taking an action, a minion taking an action, then the commander taking another action). 

A minion receives 1 AP per turn. The commander can give up 1 AP to give one of its minions +1 AP for that turn. A commander with more than one minion can give up more than 1 AP, but must give each AP to a different minion. 

### Mounts

Some creatures can be mounted by other creatures. 

When one creature mounts another, the mount becomes a minion and the rider its commander – the mount acts on its rider’s turn, and receives 1 AP per turn by default. If the rider dismounts, the mount goes back to normal.

There may be room for other creatures on a mount along with its commander. These passengers get AP as normal. 

Commanders and passengers can make their attacks from any point on the mounted creature. Passengers must occupy a particular space, but can move about/change spaces any time with their own actions or whenever the mount Strides. In practice, this may limit passengers to reach or ranged attacks (for example if they are confined to a howdah on the back of a Huge beast like an elephant). 

If a mount falls prone, its commander and any passengers dismount and are placed in unoccupied spaces around the mount. Make a Reflex save for each commander and passenger (against the mount’s Power): on a failure, they fall prone. If the mount is Huge or larger, the commander and passengers take falling damage as well if they failed their save.

## Hero points

A player can purchase up to three hero points for each of their creatures, paying the upgrade cost for that creature each time. 

A creature can spend a hero point to reroll a Fight roll, saving throw or check that they have made, or to make a creature targeting them with an attack reroll their Fight roll. Either way, use the second result.

A creature can spend a hero point just before making a recovery check. They pass that recovery check and all subsequent ones that they make in this encounter. 

## Common features

**Aquatic Only:** This creature can only swim; it cannot move on land. 

**Commander:** See “Commanders, minions and mounts” above. This entry will specify which creatures are the commander’s minions. If it says “Starts with X” (such as “Starts with Capybara Pet 12 minion”), it means that if that commander is part of a warband, then that minion is part of the warband too (at no additional points cost). 

**Scent:** A creature with scent ignores the concealed status of creatures they are adjacent to and treats invisible creatures they are adjacent to as concealed instead. 

**Swallow Whole ●** A creature of the listed size or smaller that is (a) grabbed and (b) within reach is swallowed (Reflex negates). When first swallowed and at the start of each of its turns, the swallowed creature takes the listed damage.

**Trample ●●** The creature Strides up to its Speed and may move through the spaces of creatures of smaller size. Each time it attempts to move through a creature, that creature makes a Reflex save. On a success, the trampling creature’s movement ends. On a failure, the creature is knocked prone and takes the listed damage. If the trampling creature’s space overlaps with that of other creatures at the end of its movement, move the other creatures to the nearest unoccupied spaces. 

**Truesight/See Invisibility:** A creature with truesight or see invisibility ignore the invisible and concealed statuses of creatures. 

**Void Healing:** When the creature would heal from a spell, potion or other magical effect, it takes that amount as damage instead. When the creature would take necrotic damage, it takes no damage and heals that amount instead. 

# Conditions and combat statuses

## Conditions

**Encumbered**: The creature suffers a -2 penalty to Speed and loses the Flight, Burrowing and Wall Climb modes. 

**Confused**: At the start of this creature’s turn, the opponent spends one of the creature’s action points and control the action the confused creature takes. The opponent cannot choose any limited-use actions.

**Controlled**: On the creature’s turn, the opponent spends the creature’s action points and controls the action(s) the controlled creature takes. The opponent cannot choose any features with a limited number of uses.

**Off-guard**: The creature takes a -2 penalty to Armor. If a creature receives the off-guard condition due to a combat status (for example, they are flanked or prone), they keep the condition until that combat status ends. 

**Grabbed**: The creature is immobilized and off-guard. This condition ends immediately if the creature is beyond the reach of all enemy creatures. 

**Immobilized:** The creature cannot willingly move from its current space. 

**Rattled**: The creature suffers a -2 penalty to Fight and Power. 

**Sickened**: The creature suffers a -2 penalty to saving throws. 

**Slowed**: The creature cannot take reactions and has one fewer action points on their next turn.

**Stunned**: The creature cannot take reactions and has no action points on their next turn. 

### Special conditions

Some creature cards describe other conditions. These also end at the end of the target’s turn unless specified. 

## Combat statuses

Combat statuses are circumstantial, sometimes beneficial, and do not typically go away on their own. 

**Flanked:** When a creature has enemy creatures on opposite sides of it, and those creatures are not helpless, the creature is flanked. When a creature is flanked, it is off-guard against all attackers until it ceases to be flanked. 

The target must be in reach of both flankers, and a line drawn from the center of one flanker’s space to the center of the other must pass through the target’s space. For example, if attacker 1 is in a given space, attacker 2 can be in a variety of other spaces to flank the target (T): 

<img src="img/flanking.png" />

**Helpless**: A creature that is dying is helpless. They cannot take actions (including reactions) or spend action points. When their turn begins, it ends immediately. The creature does not count as a creature for the purposes of affecting opponents (they can move through the helpless creature’s space, are not flanked by the helpless creature, etc). 

**Invisible:** The creature cannot be seen, which means attackers do not have line of sight to it. Area of effect attacks can still affect an invisible creature as normal, as can the attacks of those with the True Seeing or Blindsight features.

**Quickened:** The creature gains +1 action point at the start of its next turn. It then loses the quickened status. 

**Prone:** The creature is off-guard and takes a –2 penalty to Fight. The only movement a creature can take while prone is to Crawl. A creature can take the Stand action to remove this status.

**Swallowed:** A swallowed creature shares a space with the swallower, but cannot be targeted by any effect. 

When a creature is first swallowed and at the start of each of its turns, it takes damage as specified on the swallower’s card. While swallowed, a creature is grabbed and slowed. It can use the Escape action, but must succeed on a Reflex save against the swallower’s Power to climb out of the gizzard of the swallower.

A swallowed creature can attack its swallower, who is off-guard against the attack. On a critical hit, the swallowed creature escapes. The swallowed creature also escapes if its swallower is reduced to 0 HP or below. 

When a creature escapes, place it in an unoccupied space adjacent to the swallower.

# Game Mode: Solo adventuring

In this variant, dice rolls determine how enemy creatures act, allowing a player to run an adventure or campaign by themselves.

The player’s creatures are referred to as “adventurers” and the AI’s creatures as “monsters”. Adventures from PF2e can be easily adapted to solo adventures in *Path 2 Victory*; an example is given at the end of this section.

## Early and late turns

At the start of each round, the player decides whether each adventurer will act early or late. 

Each adventurer that acts early gets 2 AP on its turn. If late, it gets 3 AP on its turn. 

Monsters can act “super-early”, typically only getting 1 AP or taking a special defensive action. 

Early adventurers act before early monsters, but after super-early monsters. Late adventurers act before late monsters. 

Within each phase, the player decides which creature acts first (for example, the player chooses which of their early adventurers takes their turn first; they also choose which early monster takes its turn first.)

**Order:** Super-early monsters (Ⅰ), early adventurers, early monsters (Ⅱ), late adventurers, late monsters (Ⅲ).

## Gambits

Monsters have fixed actions on their turn, called “gambits”. To determine which gambit a monster uses, roll 1d6 for each type of monster (“Goblin Warrior”, “Flash Beetle”, etc.) at the start of each round (after the player has chosen whether each adventurer is acting early or late). 

The gambit will say which dice results lead to the monster pursuing that gambit, whether the monster is acting super-early (Ⅰ), early (Ⅱ) or late (Ⅲ), and which actions it is pursuing. 

Cardboard AI creatures do not have limited uses of their actions. The gambit system in effect reflects limited uses by having some actions be rarer than others. Similarly, cardboard AI creatures ignore the action point rules: they take whichever actions their roll dictates.

### Interpreting the entries

A slash between actions means the monster chooses one of those actions: preferring attacks over movement, and preferring melee attacks if it can make them over ranged attacks. 

An arrow means after taking the original action, the monster takes the subsequent action. 

### Targeting

Find out the monster’s “preferred” target, following this order until there is no ambiguity about who the monster targets:

1. Enemies within range of their attack, or able to be within range with the movement the monster has available.

2. (When using an area attack) Maximising the number of enemies targeted. 

3. Enemies listed as their “preferred” enemy.

4. Enemies that are nearest.

5. Enemies that are yet to act.

6. Enemies with the lowest current HP.

7. Enemies with the lowest Armor.

Monsters who have no enemies in range move towards whichever enemy they can get in range of with their movement, again preferring enemies based on the order given above. 

Monsters do not target helpless creatures. 

### Interpreting movement actions

**Shift:** The monster takes the Step action. If the monster has a melee action coming up, it Steps to get an enemy within reach. Otherwise, it Steps away from enemies. 

**Charge:** If the monster is already within melee reach of an enemy, it does not move. Otherwise, the monster takes the Stride action towards its preferred target. 

**Reposition:** The monster takes the Stride action towards its preferred target, even if it is already in melee reach of an enemy.

**Retreat:** The monster takes the Stride action moving as far away from all enemies as possible. 

**Stride:** The monster moves so its subsequent actions are most effective (into range, into reach, out of melee reach of enemies if it is making ranged attacks) against its preferred target. If it has no applicable subsequent actions, it moves into melee reach of its preferred target. 

### Example

Here are the gambits for the taxidermic dog. On a roll of 1, it takes no actions but becomes resistant to all damage. On a roll of 4, it acts in the early monster phase, by moving (preferring an enemy already adjacent to an ally even if it is already adjacent to another enemy) and then biting with its jaws. 

> **Gambits**  
> *Prefer enemies already adjacent to allies.*   
> ⚀ Ⅰ resist all 5 until the end of the round  
> ⚁⚂ Ⅱ Jaws > Reposition  
> ⚃⚄ Ⅱ Reposition > Jaws  
> ⚅ Ⅲ Stride > Jaws > Jaws

## Scenario: Basement Crawl

The player controls five kobolds (and their pet cat) in two encounters, with the dice determining how the enemies respond. 

Print the hero, monster and spell/item cards. 

### Adventurers

* Kobold Bard 1

* Kobold Druid 1 (Cat Companion 1; *scroll of burning hands*)

* Kobold Fighter 1 (*minor healing potion*)

* Kobold Sorcerer 1 (*scroll of* *ray of enfeeblement*)

* Kobold Rogue 1

### Encounter 1

**Set up:** A basement on a 12x12 board.

Place: 

* 4 precarious piles (2x2 each) – obstructing terrain

* 4 shelves (2x1 each) – solid terrain 

* 1 fungus patch (made from five 2x2 patches of difficult terrain; the fungus leshy treats the fungus patch as normal terain)

* 2 beds (1x2 each)

* 2 flash beetles, one on each bed

* 1 fungus leshy, on the fungus patch

* 1 stone door and 1 wooden door, in opposite corners

Deploy adventurers up to 4 squares from the stone door.

Set aside: 

* 3 taxidermic dogs 

* 1 briar doll

* 4 flash beetles

* 1 animated rocking horse

**Start of Each Round (Including Round 1):** Roll 1d6 for each bed. On 4–6, place a new flash beetle on it. 

**Start of Round 4:** Place the three taxidermic dogs adjacent to the wooden door. 

**Start of Round 10:** Place the briar doll and animated rocking horse adjacent to the wooden door. 

**When the fungus leshy is defeated:** Flash beetles stop spawning.  

**The briar doll and rocking horse are defeated:** Scenario ends; all adventurers gain +1 Advance if you are using the campaign play rules. 

#### Special rules

**Soothe Beetle** ●● Target a beetle within 6 squares. If you succeed on a Nature check (Power 14) the target beetle won’t take actions until attacked or harmed. 

**Precarious pile:** A creature can search (Interact, 1 AP) the pile with a Thievery check (Power 14). On a success, the pile is destroyed and roll 1d4. The first time that the number is equal to or less than the number of destroyed piles, the creature finds ablative armor plating. On a failure, the pile topples.

A creature that moves through the pile must make an Athletics check (Power 14) to climb over it. On a failure, the pile topples.

If the pile topples, creatures on and adjacent to the pile take 10 bludgeoning damage (Reflex half, Power 14) and the pile is removed from play.

**Bed:** Difficult terrain for Medium and larger creatures; cover for Small and smaller creatures.

**Fungus Patch:** A creature can search (Interact, 1 AP) the pile with Survival (Power 16). On a success, they find a healing potion (1–3 on 1d6) or a basic poison (4–6 on 1d6). Each item can only be found once; on the next success, the remaining item is found.

### Encounter 2

**Set up:** A garden on a 12x12 board.

* 4 hedges (each 1x4) – barriers 

* 4 boulders (1x1) – solid terrain 

* 3 holes (1x1) – difficult terrain

* 1 fountain (2x2) – difficult terrain 

* 1 shed (2x2) somewhere at the top of the board – solid terrain

* 1 faerie dragon

Deploy the adventurers in the two bottom rows. 

Set aside: 

* 3 reefclaws

**Start of Rounds 2, 3 and 4:** Place a reefclaw adjacent to a hole (use a 1d3 to determine which).

**Shed:** A creature can search (Interact, 1 AP) the shed using the Crafting skill (Power 16). On a success, they find a *fiery* hand weapon. 

**When all enemies are defeated or the hero carrying the \*fiery\* weapon from the shed reach the bottom edge of the map:** Scenario ends; all adventurers gain +1 Advance if you are using the campaign play rules.

# Game Mode: Wargaming

In this variant, players choose a faction and then build armies from within that faction. 

Rules for playing without a grid are provided, although there is no problem with playing on a grid if players prefer. 

Two example factions and a variety of alternative deployments and victory conditions are provided in separate PDFs. The deployments and victory conditions originally appeared in *Last Alliance* by Chris Sakkas.

## Factions

Two example factions are provided: the Doughty Kingdom and the Redolent Halls.

## Deployment zones

When playing with these alternative deployment zones (provided in a separate PDF), players alternate deploying a creature from their warbands until all creatures have been placed.

## Victory conditions

If you are playing with one of these alternative victory conditions (provided in a separate PDF), do not place objectives unless specified. 

Where these rules refer to a warband being “Broken”, it means three-quarters of the warband by points cost is helpless or has been eliminated. 

If a player’s Victory Points exceed the other player’s by 5 or more, that player has won a major victory. Otherwise, they have won a minor victory. 

## Gridless play

For the most part, you can play *Path 2 Victory* without a grid by substituting “inches” any time the game refers to “squares”. Measure diagonal movement normally instead of imposing an extra cost for it. 

### Ranges

Something is within range if the distance between any point on the edge of the base of the attacker and any point on the edge of the base of the target is less than or equal to the range. 

### Adjacency

A creature is adjacent to another if there is less than 1 inch between both creatures’ bases. 

### Targeting

Look from the attacking figure’s perspective. If any part of the target figure is visible, the attacking figure has line of sight. If any part of the target figure is obscured, it has cover or concealment (as applicable). 

If any model that is sculpted unusually (for example, they are kneeling, or have been posed standing on a large rock), imagine it standing in a neutral pose to determine line of sight, cover and concealment. 

### Areas of effect

Measure emanations and bursts as circles of the radius specified (bursts are measured from a point, emanations from the edge of the base of the creature causing the emanation). 

Measure cones as quarter-circles of the radius specified. 

Measure lines as a line of no thickness of the length specified. 

# Appendix: Converting from PF2e

Converting creatures from PF2e is more art than science, but here are some tips. 

*Path 2 Victory* uses the Proficiency without Level variant rule, so make sure to make the necessary adjustments first (basically, subtracting level from any number that includes Proficiency).

**Level, Alignment and Size:** Unchanged from PF2e.

**Points Cost:** Calculate based on the below table: 

##### Table 2: Points cost by level

| **Level** | **Cost** | **Upgrade cost** | **Level** | **Cost** | **Upgrade cost** |
| --------- | -------- | ---------------- | --------- | -------- | ---------------- |
| **-1**    | 9        | 2                | **7**     | 48       | 8                |
| **0**     | 12       | 2                | **8**     | 60       | 10               |
| **1**     | 14       | 3                | **9**     | 72       | 12               |
| **2**     | 18       | 3                | **10**    | 90       | 15               |
| **3**     | 21       | 4                | **11**    | 108      | 18               |
| **4**     | 26       | 5                | **12**    | 135      | 23               |
| **5**     | 32       | 6                | **13**    | 160      | 27               |
| **6**     | 40       | 7                | **14**    | 192      | 32               |

Cost is calculated as the XP that a level 5 party would receive from defeating that creature in PF2e. 

## Stats

**Fight:** Choose the highest attack bonus. 

**Armor:** Unchanged from PF2e (where it is called AC).

**Power:** Choose the highest DC listed. If none, set Power to Fight +9. Alternatively, if the creature has one strike at a significantly lower attack bonus than the others, could use that attack bonus +10 as the creature’s power, and change the strike into a save-negates power. 

**Saving Throws:** Unchanged from PF2e. 

**HP:** Round hit points to the nearest 5 if the creature has more than 10 hit points. 

**Speed:** Convert feet into squares by dividing by 5. Choose the highest speed among all movement modes, unless that represents a particularly niche movement. 

In *Path 2 Victory,* creatures have at most one movement mode. If a creature has multiple movement modes, choose the most useful (Burrowing is usually more useful than Aquatic or Wall Climb, and Flight is almost always the most useful). If one of a creature’s movement modes is much less than others (for example, it has a walk speed of 60 feet but a fly speed of 10 feet), it is better to ignore the slower movement mode. 

Aquatic creatures that cannot move on land at all (or barely, for example with a walk speed of 10 feet or less) should have the Aquatic Only feature. They are of little use in most games of *Path 2 Victory.* 

## Features

* Where a lower-level creature has multiple weapon options, can gate additional weapons options as upgrades. 

* Remove critical success and failure rules except where particularly interesting or important. 

* Simplify tracking or remove it altogether. For example, make a recharge power usable twice per encounter instead. If a fear effect can only affect a given monster once, abstract this by making the entire fear effect usable once per encounter. 

* When an action costs three action points, consider if an element can be removed from it to make an action that is balanced at two action points. Alternatively, it can be okay to just make an action that costs three action points cost two action points. 

* Because *Path 2 Victory* has two action points per turn instead of three, ignore “maintenance” actions like Raise Shield or the Fly action to remain in the air. *Path 2 Victory* is just not fine-grained enough that it is necessary to have these kinds of actions. 
  * When an action requires a maintenance action, like a ranged weapon that needs the Reload action to use again, an alternative option is to make the original action usable only once per turn. 


### Damage

* Consolidate different types of damage, so instead of doing 2 fire damage and 3 poison damage, a strike does 5 fire and poison damage. 

* Find the average damage and use that. When this amounts to damage of 10 or more, round to the nearest 5. 

* Precision and bleed no longer exist as damage types – the associated damage still happens, but there are no special rules relating to precision and bleed damage.

* Instead of hardness, use resist all. 

* Replace every 5 points of resistance with 2d6 resistance (so resist 10 becomes resist 4d6, etc). 

### Strikes

Remove/consolidate attacks that are unlikely to see much use.

In *Path 2 Victory,* the multiple attack penalty does not increase during an action. That makes some actions that allow for multiple attacks too powerful. You can remove these actions or modify them. 

### Spellcasting

Creatures are casters of rank equal to the highest rank of spell that they can cast. This is different to, and simpler than, the original game where casters would cast spells of different ranks. 

To figure out how many spells/spell slots the creature has available, follow this rough guide:

* Take the number of spells memorized/spell slots available for the highest rank of spells. 

* Add half the number of spells memorized/spell slots available for the next two highest ranks of spells.

* Subtract 2.

* Ignore all other spells memorized/spell slots available. 

For example, Grugach can cast three rank-4 spells, five rank-3 spells and seven rank-2 spells. He becomes a Caster Rank 4, with ((3 + 5/2 + 7/2) -2) spell slots, i.e. seven. 

Then in terms of the specific spells known/memorized, choose spells that have a purpose in combat and are iconic for the creature. 

### Areas of effect

For powers and spells, reduce areas of effect, from 16 to 8, from 12 to 8 and from 6 to 4. Powers with areas of effect of 1, 2 or 3 generally do not need to be reduced in area. 

### Conditions

Conditions almost always just last until the end of the creature’s next turn. When it comes to the lowered abilities conditions, this is not as much of a concern because the replacements (sickened, rattled or off-guard) can be more useful and represent a steeper penalty. 

* **Blinded:** Use rattled and encumbered instead. 

* **Broken:** Instead of breaking a creature’s weapons, they become rattled.

* **Dazzled:** Use rattled instead. 

* **Deafened:** Ignore, or choose a thematically appropriate condition. 

* **Fatigued:** Use off-guard or sickened instead. 

* **Frightened and fleeing:** Fear effects apply options like pushing the target, ending their action even if they have movement remaining or the rattled or dazed conditions.

* **Paralyzed:** Use stunned instead. 

* **Restrained:** Use immobilized instead. 

* **Lowered abilities conditions (clumsy, drained, enfeebled and stupefied):** Pick one of sickened, rattled or off-guard as seems appropriate. 

Other conditions are not described in *Path 2 Victory* but can be used sparingly: fascinated, petrified (remove from play and replace with a statue of the same size), etc. 

You can also proxy additional conditions or effects in a two-step process: saying that a certain event gives a creature a condition, and then giving it an additional rider when affected by that condition. 

For example, in PF2e the craig linnorm loses regeneration when it takes cold damage. In *Path 2 Victory,* the Craig Linnorm becomes sickened when it takes cold damage, and loses regeneration while sickened. The flavorful weakness is preserved, but no further tracking is needed beyond the existing *Path 2 Victory* condition system. 