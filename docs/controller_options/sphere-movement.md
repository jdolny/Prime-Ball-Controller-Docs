#Sphere Movement

These settings control all of the aspects of movement.  There are seperate settings for ball and wheel control modes to give advantages such as faster speed or higher slope limit for different modes.

- **Control Mode** - The control mode of the sphere.  Hybrid mode starts off as ball movement and transitions to wheel as the player speeds up.  Hybrid is recommended.
- **Ball Brake Rate** - When the control mode is currently ball, the rate at which the sphere comes to a stop when no input is received
- **Control Switch Steps** - When the control mode is set to hybrid, this controls how many steps must pass before control switches from ball to wheel
- **Step Reset Acceleration** - When the control mode is set to hybrid and the acceleration drops below this number, the control switches from wheel to ball
- **Wheel Direction Curve** - When the control mode is currently wheel, this controls how tight the sphere orbits the camera when the player is pressing directly left or directly right
- **Wheel Rotation Velocity** - When the control mode is currently wheel, this controls how long it takes for the sphere to turn in the opposite direction
- **Ball Movement / Wheel Movement** - Movement properties specific for when the ball is in ball or wheel mode
    - **Movement Force** - The force applied to move the sphere
    - **Acceleration Rate** - The rate at which to accelerate the sphere
    - **Acceleration Reset Rate** - The rate at which the acceleration is reset back to zero when no input is received
    - **Drag** - The sphere's rigidbody drag
    - **Allow Air Control** - Enable / Disable air control
    - **Air Control Amount** - The amount of air control.  Higher number gives more control.
    - **Grounded Gravity Force** - The force of gravity when the player is grounded
    - **Initial Gravity Force** - The force of gravity when the player first becomes ungrounded, before the increment amount has applied
    - **Max Gravity Force** - The maximum gravity force that can be applied
    - **Gravity Increment Amount** - The amount of additional gravity force to add while player is falling.
    - **Max Slope Angle** - The max slope angle that the sphere can roll up
    - **Minimum Slip Angle** - The minimum angle that will cause the sphere roll back down a slope
    - **Max Angle Slip Multiplier** - The force that prevents a player from going up a slope greater than the max slope angle.  If this number is low enough the player will be able roll up the slope if there is enough momentum
    - **Minimum Slope Angle Modifier** - The minimum angle required for a player to be considered on a slope, otherwise act as on flat ground
    - **Slip Force** - The force applied when slipping down a slope
    - **Up Slope Speed** - When going up a slope, controls if the player should go slower or at the same speed as when on flat ground
    - **Down Slope Speed** - When going down a slope, controls if the player should go faster or at the same speed as when on flat ground
    - **Up Hill Multiplier** - If up slope speed is set to slower, this controls how much slower to go
    - **Down Hill Multiplier** - If down slope speed is set to faster, this controls how much faster to go
    - **Slope Land Slip** - When jumping and landing on a slope, how much force should be transfered to roll back down.  Setting to 0 will cause the player to momentarily stick before the slip force is applied. Setting this value too high will cause the player to ricochet away from the slope when landing
    - **Control Orientation** - The player controls are based on the camera position.  This allows you to override the controls based on a different position



