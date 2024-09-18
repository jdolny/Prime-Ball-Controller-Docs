# Local Multiplayer

A simple Local Multiplayer prefab is also include with Prime Ball Controller.  It makes it easy to add split screen support.

1.) If you have the player gameobject in your scene it must be removed as they will be added during runtime.

2.) Create some extra layers for each player.  One unique layer is needed for each player camera.  The demo scene uses CameraPlayer1,CameraPlayer2,CameraPlayer3,CameraPlayer4

3.) Add the MultiPlayer Manager prefab to your scene, located at Magaeric Solutions->Prime Ball Controller->Prefabs

4.) Select the prefab in your scene manager to display the Multi Player Game Manager Script options.

5.) Drag in the player prefab to the Player Prefab slot

6.) Select the 2 player split type - if only 2 players you can select b/w horizontal or vertical split screen, not used if more than 2 players

7.) Select the number of players

8.) Add the Camera Player Layers

9.) Optionally, add some extra spawn points and set the border size.

10.) Hit play, happy local multiplaying.

