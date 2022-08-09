#Camera Zone Options

- **Zone Area** - The area that will activate the zone.  This should be a plane with the mesh renderer removed and the collider set to trigger.
- **Camera Blend Time** - When entering a zone, the time it takes to blend to the new camera
- **Camera Blend Style** - The blend style to use when changing to the new camera
- **Stationary Camera Position** - If the camera type is set to stationary, the position of the camera
- **Camera Type** - The type of camera to be used in the zone
- **Camera LookAt** - The object you want the camera to look at while in the zone, if the camera type is stationary this can be empty to just use the position of the camera
- **Camera LookAt Rotation** - If the camera type is set to overhead, a look at rotation is needed so the camera isn't looking straight down.  This provides a top down view offset
- **Overhead Camera Distance** - When using the overhead camera, this sets how far away the camera is
- **Magnet Cam If Climbing** - If the camera type is stationary and the player is climbing with magnet mode, switch to the magnet cam or stay in stationary cam
- **Control Change Wait For Blend** - When entering a zone, the controls will change to be relative to the new camera.  Enabling this setting will wait to change the controls until the camera is completely finished blending
- **Override Default Movement** - Enable this setting to override the movement controls for the zone
- **Movement Override** - If Override default movement is enabled, control the new movement with these settings
- **Override Default Abilities** - Enable this setting to override the player abilities for the zone
- **Abilities Override** - If Override default abilities is enabled, control the new abilities with these settings
- **Halfpipe Boost Enabled** - Enables the option to incrementally increase boost strength while on a half pipe in order to go higher with each successful boost
- **Halfpipe Boost** - If halfpipe boost enabled use these settings to control the boost

