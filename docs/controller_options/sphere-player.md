#Sphere Player

The sphere player settings are used for various options of the sphere that don't seem to fit into any other category.

- **Ground Layer** - The layer to be considered grounded.
- **Ground Check Trigger Collision** - Should the ground check collider with triggers or ignore them when determining grounded.
- **Ground Check Radius Multiplier** - The amount to multiply the sphere's radius by to check for ground.  This effectively makes the sphere collider ground check slightly smaller than the sphere collider.
- **Ground Check Distance** - The distance the sphere cast should travel to check for ground
- **Use Floating Controller** - When this is checked, the sphere's collider will float above the ground to allow stair handling and better obstacle avoidance.  This does slightly alter how the sphere handles.  If you don't need these features, it is recommended to disable.
- **Collider Center** - If using the floating collider, how far should the collider be offset or above ground.
- **Floating Mesh Offset** - If using the floating collider, the mesh may need to be slightly moved up so it's not clipping into the ground, use this to raise it up.
- **Float Force** - If using the floating collider, this the vertical force added to the player to keep it floating.
- **Damper** - If using the floating collider, the damper controls how springy the ball is.  A lower number will have a higher spring.
- **Movement Audio Source** - The audio source used to play the roll and air sound
- **Boost Audio Source** - The audio source used to play the boost sounds.
- **Sphere Audio Source** - The audio source used for all other sounds.
