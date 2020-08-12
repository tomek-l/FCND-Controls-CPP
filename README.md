# Scenario 1: Wrong model (mass) correction

Before:

![](docs/scenario1_bad.gif)

After:

![](docs/scenario1_good.gif)


# Scenario 2 Body rates & roll/pitch control

The vehicle recovers from roll axis rotation 


Before:

![](docs/scenario2_bad.gif)

After:

![](docs/scenario2_good.gif)


# Scenario 3: Lateral control

The vehicle corrects the initial yaw error, and converges to it's target X position.

Before:

![](docs/scenario3_bad.gif)

After:

![](docs/scenario3_good.gif)



# Scenario 4: Non-idealities & robustness

The two vehicles:
- with offset center of gravity
- with larger mass

converge to their set X positions.

Before:

![](docs/scenario4_bad.gif)

After:

![](docs/scenario4_good.gif)


# Scenario 5: Tracking trajectories

The vehicle is able to track "figure 8" trajectory within the set error margin.

Before:

![](docs/scenario5_bad.gif)

After:

![](docs/scenario5_good.gif)
