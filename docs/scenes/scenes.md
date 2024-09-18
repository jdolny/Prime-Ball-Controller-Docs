#Scenes

Prime Ball Controller comes with 3 built in scenes.  To be fair, it is only 1 scene with some various functionality changes used to demonstrate different features.  The scenes can be found under **Assets->Magaeric Solutions->Prime Ball Controller->Scenes**

### Scene 1 - PBC_Demo_Scene
This is the main scene that allows to explore all of the features that the ball controller has to offer.  The main components include the Player Object and the Zones object.  When examining how the scene is setup, those are the objects to analyze.
The environment object is mostly just a bunch of cubes to make the scene, with the exception of the moving platforms.  They also have the Simple Platform Component attached to them to allow the ball to move correctly on the moving platform.

### Scene 2 - Pbc_AbilityPickup_Scene
This scene is the same as the demo scene but has the projectile ability disabled by default.  It has a green cube on the floor with the Ability Pickup Component Script attached to it that enables the projectile ability when contacted by the ball.  It just serves
as an example of how to enable abilities during runtime.

### Scene 3 - Pbc_Multiplayer_Scene
This scene is also the same as the demo scene but does not have the player in the scene by default.  It instead uses the multiplayer manager component to add players during runtime.  It can be used as an example of how to setup a local multiplayer game.
For more information on how to use the Multi Player Game Manager, refer to [the Local Multiplayer Overview](../../multiplayer/multiplayer)

### Bonus
In the Unity asset store, there are a few photos of the ball controller using glowing materials.  This was setup with HDRP.  Just create a new HDRP project and import the HDRP materials located at **Assets->Magaeric Solutions->Prime Ball Controller->Pipeline Materials**
