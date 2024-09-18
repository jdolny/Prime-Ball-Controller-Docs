#Creating Zones

There are multiple ways you could create zones.  This is just an example of how I like to do it.  This guide will show you how to setup a stationary camera zone.  For additional reference, check out the demo scene and examine how each zone was setup.

## 1.  Create The Zone Object

1.  Begin by creating a empty game object called Camera Zones.  This will keep all of your zones organized.<br/>
![Camera Zone 1](../images/camerazone1.png)
2.  Remember to zero out your empty game object if not already done.<br/>
![Camera Zone 2](../images/camerazone2.png)
3.  Add a plane to your Camera Zones, rename it to something meaningful
4.  Remove the mesh renderer component from the plane
5.  Change the mesh collider to convex and check the is trigger box
6.  Scale and position the plane in your scene, if the player is anywhere inside the trigger the zone will be active
7.  You should now have a scene without a layout like this.  Obviously your scene will look different.<br/>
![Camera Zone 3](../images/camerazone3.png)
8.  Add a new empty gameobject with your zone as the parent, named **Camera Position**<br/>
![Camera Zone 4](../images/camerazone4.png)
9.  In your scene view, position your view to how you would like the camera to look.  In this example I zoomed in on the zone, with a slight overhead view<br/>
![Camera Zone 5](../images/camerazone5.png)
10.  Select the **Camera Position** game object, then select game object->Align With View from the File Menu
![Camera Zone 6](../images/camerazone6.png)

## 2.  Assign The Zone Object To The Zone Game Manager
1.  Drag the **Zones prefab** located at **Assets/MagaericSolutions/Prime Ball Controller/Prefabs** into your scene hierarchy
1.  Select the Zones object and find the Zones Game Data under the Zone Game Manager Script Component
2.  Click the plus sign to add a zone, or modify the existing Template zone<br/>
![Camera Zone 7](../images/camerazone7.png)
3.  Give the zone a name
4.  Drag the zone plane you created back in section 1 step 3 into the Zone Area
5.  Drag the zone camera position you created back in section 1 step 8 into the Stationary Camera Position
6.  Change the **Camera Type** to **Stationary**
7.  Your finished zone should look something like this<br/.>
![Camera Zone 8](../images/camerazone8.png)

Your zone is finished.