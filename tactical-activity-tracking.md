# Tactical Activity Tracking Rules

In a tactical situation, action is tracked in **rounds of five seconds**. During a `round` combatans perform actions (movement, attack, etc.) by roughly ordering the characters’ actions based on `initiative` and when they would be completed.

Actions are assigned a number of `Action Points` (AP) to represent the time required (see AP table).
Combatants receive **4 Action Points every round**, which may be spent among any number of actions.

## Actions
Specific actions are declared when they are started, and resolved (e.g., roll a maneuver) when they are completed.

**Fixed/range of AP** Some actions require a fixed number of Action Points, while others are given a range, such as 2 – 4. Actions with a range of AP can be performed more quickly at a penalty of **-25 for each AP less than the normal maximum**.

**Instantaneous actions** Some actions occur so quickly they are treated as instantaneous (0 AP); the first such action costs 0 AP and is thus a “free” action taking no time during the round, however any further instantaneous actions performed that round take 1 AP each. This represents the fact that no action is strictly instantaneous.

**Round to Round Actions** A few actions may require more than 4 AP such as donning or removing armor, or picking a complicated lock. These actions take multiple rounds to complete and must usually be performed uninterrupted by other actions (although they may be combined with other actions such as movement).

**Tactical Movement** Movement is a unique action during the combat round, because it is often combined with other actions, such as
shooting while moving forward, advancing while drawing a weapon, or charging into combat. An action penalty based on one’s movement pace applies to all other actions performed in the round.

| Action | AP cost |
| --- | --- |
Drop item | 0
Use shield in melee | 0
Shift item to other hand | 1
Draw weapon/ammo/item | 1
Prone <-> Stand | 1
Perception | 1 - 2
Ranged Attack | 1 - 3
Eat or drink (herb/potion) | 2
Melee Attack | 2-4
Get item from ground | 3
Dodge | 4
Mount/dismount | 4
Reload | 6
Load Light Crossbow | 8
Load Heavy Crossbow | 16
Pick Lock / Disarm Trap | 20
Hold position (Swim/Climb) | C
Movement | special


### parry
The amount of `parry` to be used and who it will be used against must be announced at the beginning of the round, or as soon as melee ensues.


## Tactical round
During a round, actions resolve when they would be completed in order by counting down from the highest initiative to the lowest.

The tactical round is played out in 3 phases:
- Initiative,
- Resolution,
- and Upkeep.


### Initiative
`initiative` - determines the order in which combatants resolve their actions, from highest to lowest initiative.

Base initiative is rolled once at the start of any time-sensitive, tactical situation:

**Base Initiative = 2d10 + Qu - (1 for every -10 penalty)**

The actual initiatives that actions are declared and resolved on are based on how many `Actions Points` the combatant has remaining. Add **5 for every for every AP left**. Actions are declared before the Action Points are spent, and are resolved after the Action Points are spent. 

**Actual Initiative = Base Initiative + (remaining Action Points x 5)**

Instantaneous actions (0 AP) can be declared and resolved at Base Initiative + 20 (or at any point after).

_**Example**: Hauser rolls a 14 on initiative, +1 for quickness bonus is 15. He has 4 AP at the start of the round, so his current initiative at the start of the round is 15 + (4 AP x 5) = 35. On 35, the GM asks Hauser’s player to declare his action. He will make a melee attack for 3 AP. 3 AP x 5 = 15. Hauser will be attacking his target from initiative 35 until 35 - 15 = 20. On initiative 20, Hauser’s player will roll to resolve his melee attack._

Immediately after an action is resolved, if the combatant has any more AP left, he should declare his next action, which will then resolve when the AP are spent.


### Resolution
Actions are resolved on the initiative when they are completed, usually by rolling an attack or an appropriate skill maneuver, although some mundane actions such as drawing a weapon or simple movement may not require any roll. 

### Upkeep
The last step in the round is to account for ongoing effects. During upkeep, the players and the GM should perform the following for all combatants:
- Subtract hits due to bleeding.
- Reduce the remaining duration of all spells or other non-stun, timed effects by 1 round.
- Reduce stun effects 1 round, starting with the most severe effect (Stunned/Unable to Parry, then Stunned, then Dazed), if the combatant had spent less than 2 AP before being stunned.
- Remove any staggered effect if the combatant had spent less than 2 AP before being staggered.
- Advance any environmental or other effects (e.g., a rising tide, or a spreading fire).
