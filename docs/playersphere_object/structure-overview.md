#PlayerSphere Game Object
The structure of the PlayerSphere should not be modified, with the exception of the cameras object.  The cameras can removed from the prefab without issue.  They were just included to make it easier to
get them into your project.  Most of the required scripts are added dynamically and the script initialization may fail if you move things around too much.  There are only 3 scripts that need to be added 
to your objects.

1.  **Pbc Manager** -  This is the main initialization script and should be attached to the PlayerSphere parent object
2.  **Mesh Rotation Controller** - This script handles the appearance of the ball's rotation and should be attached to your mesh
3.  **Standard Camera Controller** - This script handles the position of the camera when using the standard camera and should be attached to your Standard Camera

