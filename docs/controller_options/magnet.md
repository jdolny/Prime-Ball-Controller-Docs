#Magnet

- **Enabled** - Enable / Disable Magnet ability
- **Magnet Layer** - The layers that magnet mode can be activated on
- **Movement Force** - The movement force while in magnet mode.  This value is relational with magnet power.  If this value is too high and the magnet power is too low, the player will not stick to the wall when going around corners.
- **Magnet Power** - The strength of the magnet to keep the player attached to the wall.  This setting is relational to magnet climb force.
- **Max Climb Angle** - The max angle that can be climbed while in magnet mode
- **Min Ceiling Angle** - The minimum angle to be considered hanging from ceiling when in magnet mode
- **Grounded Control Mode** - When moving from climbing up a wall to being grounded and the ground layer is still magnet controls how it should be handled.
	- **Break** - Magnet mode is disabled a controls resume as if not on magnet
	- **Freeze** - Player sticks to the surface and cannot move until the magnet button is released
	- **Magnet** - Player continues in magnet mode
- **Activation Velocity Mode** - When magnet activates, should velocity carry over or be cleared resulting in a temporary freeze at activation
