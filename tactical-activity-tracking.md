# Tactical Activity Tracking Rules
To break up the action into manageable periods and to simplify tracking of durations for movement, attacks, injuries and other effects, action occurs in time periods of five seconds, which are called rounds.

During a `round` characters’ actions are roughly ordered based on when they would be completed, using a `initiative` timer to track the duration and order of actions: The GM counts down the `initiative` while combatants declare `actions`, and spend `Action Points` to perform `actions` when they complete.

Actions that take more `Action Points` (time) will resolve later in the round, although combatants with high `initiative` have a chance to complete long actions before others complete shorter actions.

`Round` - In a tactical situation, action is tracked in **rounds of five seconds**.

`Initiative` - determines the order in which combatants declare and resolve their actions, from highest to lowest initiative.

`Action` - Actions include any activity the character performs including movement, shooting, melee, or retrieving items from a backpack.

`Action Points`- Actions are assigned a number of **Action Points** (AP) to represent the time required (see [AP table](https://github.com/coprolit/rpg-rules/blob/master/tactical-activity-tracking.md#actions)). Combatants receive **4 Action Points every round**, which may be spent among any number of actions.

## Tactical round
During a round, actions resolve when they would be completed in order by counting down from the highest initiative to the lowest.

The tactical round is played out in 3 phases:
- Initiative,
- Resolution,
- and Upkeep.

### Initiative
Initiative is rolled anew every round by every combatant and determines the order in which combatants declare and resolve their actions.

Base initiative is rolled once at the start of any time-sensitive, tactical situation:

`Base Initiative` = **2d10 + Qu - (1 for every -10 penalty)**

The actual initiatives that actions are declared and resolved on are based on how many `Actions Points` the combatant has remaining. Add **5 for every for every AP left**. Actions are declared before the Action Points are spent, and are resolved after the Action Points are spent. 

`Actual Initiative` = **Base Initiative + (remaining Action Points x 5)**

### Resolution
During the Resolution phase combatants declare and resolve their actions based on `initiative`, by counting down from the highest initiative to the lowest.

Actions are declared when they are started, and paid for (in AP) and resolved on the initiative when they are completed, usually by rolling an attack or an appropriate skill maneuver, although some mundane actions such as drawing a weapon or simple movement may not require any roll.

Instantaneous actions (0 AP) can be declared and resolved on the same `initiative`.

_**Example**: Hauser rolls a 14 on initiative, +1 for quickness bonus is 15. He has 4 AP at the start of the round, so his current initiative at the start of the round is 15 + (4 AP x 5) = 35. On 35, the GM asks Hauser’s player to declare his action. He will make a melee attack for 3 AP. 3 AP x 5 = 15. Hauser will be attacking his target from initiative 35 until 35 - 15 = 20. On initiative 20, Hauser’s player will roll to resolve his melee attack._

Immediately after an action is resolved, if the combatant has any more AP left, he should declare his next action, which will then resolve when the AP are spent. 

### Upkeep
The last step in the round is to account for ongoing effects. During upkeep, the players and the GM should perform the following for all combatants:
- Subtract hits due to bleeding.
- Reduce the remaining duration of all spells or other non-stun, timed effects by 1 round.
- Reduce stun effects 1 round, starting with the most severe effect (Stunned/Unable to Parry, then Stunned, then Dazed), if the combatant had spent less than 2 AP before being stunned.
- Remove any staggered effect if the combatant had spent less than 2 AP before being staggered.
- Advance any environmental or other effects (e.g., a rising tide, or a spreading fire).


## Actions
Actions include any activity the character performs including movement, shooting, melee, or retrieving items from a backpack.

Some actions require a fixed number of `Action Points`, while others are given a range, such as 2 – 4. Actions with a range of AP can be performed more quickly at a penalty of **-25 for each AP less than the normal maximum**.

| Action | AP cost | - |
| --- | --- | --- |
Ranged Attack | 1-3 |
Melee Attack | 2-4 |
Thrown Attack | 2-4 |
Dodge | 4 |
Ammo reload | 6 |
Use shield in melee | 0 |
_ | |
Movement | special | 1 pace change allowed per tick
Mount/dismount | 4 |
Rapid dismount | 2 |
Prone <-> Stand | 1 |
_ | |
Perception | 1-2 |
Orientation Maneuver | 0 | Result is a delay (penalty to initiative): Failure = can perform no actions in round, Partial success = -20, Near success = -10, Success = 0
_ | |
Draw weapon/ammo/item | 1 |
Sheath weapon/ammo/item | 2 |
Get item from ground | 3 |
Drop item | 0 |
Shift item to other hand | 1 |
_ | |
Eat or drink (medicals) | 2 |
Power supply reload	| 8 |
Apply first aid	| 8 |	per hit/round
Pick Lock / Disarm Trap | 20 |
Misc. Static Action	| 8+ |

#### Instantaneous actions
Some actions occur so quickly they are treated as instantaneous (0 AP); the first such action costs 0 AP and is thus a “free” action taking no time during the round, however **any further instantaneous actions performed that round take 1 AP each**. This represents the fact that no action is strictly instantaneous.

#### Round to Round Actions
A few actions may require more than 4 AP such as donning or removing armor, or picking a complicated lock. These actions take multiple rounds to complete and must usually be performed uninterrupted by other actions (although they may be combined with other actions such as movement).

#### Conditional Actions
A conditional action is a **held action** that will be triggered when certain conditions are met. The combatant declares a specific trigger and action on his initiative, and it is considered “ready” (and AP is spend) when it would normally resolve. The action is resolved when (and if) the trigger condition occurs (often on someone else’s initiative).

Conditional actions can be held for as many rounds as the character can maintain unbroken concentration.

#### Canceling action
An action may be canceled before it is resolved. Depending on how stressful the cancelled action was, this may require an `Orientation Maneuver`.

#### Movement
Movement is a unique action during the combat round, because it is often combined with other actions, such as
shooting while moving forward, advancing while drawing a weapon, or charging into combat. An [action penalty](https://github.com/coprolit/rpg-rules/blob/master/movement-rules.md) based on one’s movement pace applies to all other actions performed in the round.

#### Closing
Closing occurs any time a combatant gets within melee combat range of another combatant (3m). If a combatant is within melee range at any point in the round, he gets to attack with a penalty due to his pace.
This represents an initial ‘clash of blades’ that could be anywhere from one to a few seconds but can be just as deadly (or ineffective) as a full round of combat.

The defender, assuming his weapon is readied and he is not engaged in other activities, does not get a penalty and can attack and parry as normal.

#### Charging
If a combatant closes into melee at high speed relative to defender, then he has the potential for a more damaging blow. This is called charging, which sacrifices accuracy (reflected in the penalty due to pace) in favor of power. A successful charge increases the power of the attack based on the charger’s speed:

| relative speed | hits | critical |
| --- | --- | --- |
3 m/s | x2 | +1
6 m/s | x3 | +2
12 m/s | x4 | +3

#### Parry
The amount of `parry` to be used and who it will be used against must be announced at the beginning of the round, or as soon as melee ensues. At the beginning of the round, a player should know what his Defensive Bonus is against each of his opponents.

For melee actions that are utilizing `parry`, the `Action Points` are considered **spent once the parry is used**. This prevents combatants from parrying then deciding to do something else. However, the actual attack occurs at the normal initiative even if the benefits from the parry are realized earlier (as the result of being attacked).
