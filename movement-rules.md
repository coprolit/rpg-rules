# Movement Rules
### Moving Rate and Pace
#### Base Moving Rate
`BMR` m/s = stride length x stride frequency
- **Stride length** m = height m x 0,415
- **Stride frequency** steps/s = 1.8 steps/second + (2x Qu bonus - 50) / 100 * 1,8

#### Encumbered Moving Rate
`EMR` m/s = `BMR` - encumbrance speed penalty m/s
- **Encumbrance speed penalty** m/s = (carried load kg - load allowance kg) * 0.02
- **Load allowance** kg = (18 kg + (x2 strength bonus - 50) / 100 * 18)

`Moving Rate`: **EMR** x Pace multiplier

Pace multiplier | Description | Pace penalty to simultaneous maneuvers | MM difficulty
--- | --- | --- | ---
x0.25 | Crawl / Climb / Swim | NA | see [MM rules](https://github.com/coprolit/rpg-rules/blob/master/moving-maneuver-difficulties.md)
x½ | Creep / Slow Walk | -5 |
x1 | Walk (base) | -10 |
x1½ | Brisk | -20 |
x2 | Jog | -30 |
x3 | Run | -40 | Easy
x4 | Sprint | -70 | Light
x5 | Dash | -100 | Medium

- Characters can move no faster than **brisk** backwards, and the maneuver penalty is **doubled**. He suffers a penalty of -10 (backwards creep), -20 (backwards walk), or -40 (backwards brisk) while fighting.
- Characters who are prone can move no faster than **walk** pace, and the maneuver penalty is **quadrupled**.

### Movement Maneuvers
**Encumbrance MM penalty** = -20 x load / load allowance

For normal movement, a `maneuver roll` is not required; however, for stressful situations such as moving in rough terrain or while stunned, a roll is required (using the appropriate skill of Running, Swimming, etc.). For example, a combatant who is running in a zigzag toward an enemy outpost should make a maneuver roll; likewise, a maneuver roll is called for if a combatant is stunned or moving across slick ground, broken terrain, or other similar obstacles.

MM task results apply as normal. The result is the percentage of the distance they would normally move given their rate of speed.

**Terrain Modifiers** | -
--- | ---
Perfectly flat and uniform terrain | Easy (+20)
Nearly flat surface with no obstacles | Light (+10)
Mostly flat and open area | Medium (0)
Rough and rocky road, furnished room | Hard (-10)
Sloping and rocky, people in the way | Very Hard (-20)
Modest slopes/rocks, light crowd | Extremely Hard (-30)
Numerous obstacles, steep, crowds | Sheer Folly (-50)
Dense obstacles, packed crowd | Absurd (-70)
Sheer cliff, tightly packed crowd | Nigh Impossible (-100)
