# Movement Rules
### Moving Rate and Pace
`BMR`: **Base Moving Rate** (pr. second) = 1.2 m/s + Quickness/2 + Stride

`Moving Rate`: **BMR**  x Pace multiplier

A character can change his `pace` multiple up or down by 1 multiple each second he is moving.

Pace multiplier | Description | Pace penalty to simultaneous maneuvers
--- | --- | ---
x0.25 | Crawl / Climb | NA
x½ | Creep / Slow Walk | -5
x1 | Walk (base) | -10
x1½ | Brisk | -20
x2 | Jog | -30
x3 | Run | -40
x4 | Sprint | -70
x5 | Dash | -100

- Characters can move no faster than **brisk** backwards, and the maneuver penalty is **doubled**.
- Characters who are prone can move no faster than **walk** pace, and the maneuver penalty is **quadrupled**.

MM task results apply as normal. The result is the percentage of the distance they would normally move given their rate of speed.
