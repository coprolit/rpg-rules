# Movement Rules
### Moving Rate and Pace
`BMR` - **Base Moving Rate** m/s = stride length x stride frequency
- **Stride length** m = height m x 0,415
- **Stride frequency** steps/s = 1.8 steps/second + (2x Qu bonus - 50) / 100 * 1,8

`EMR` - **Encumbered Moving Rate** m/s = `BMR` - encumbrance speed penalty m/s
- **Encumbrance speed penalty** m/s = (carried load kg - load allowance kg) * 0.02
- **Load allowance** kg = (18 kg + (x2 strength bonus - 50) / 100 * 18)

`MR` - **Actual Moving Rate** m/s = `EMR` x Pace multiplier

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
