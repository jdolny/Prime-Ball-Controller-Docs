# Setup With Existing Cinemachine

If you are already using Cinemachine and want to keep your existing Camera Brain, you will need to make one adjustment to the PlayerSphere object.

1.  Remove the Main Camera from the PlayerSphere Object located at **PlayerSphere->Cameras->Main Camera**<br/>
![Remove pbc camera1](../images/deletepbccamera1.png)
2.  Select the PlayerSphere Object and find the Pbc Manager Script
3.  Expand Data Repository then Cinemachine Cameras.  Drag your Main Camera into the Main Camera Position.
![Remove pbc camera2](../images/deletepbccamera2.png)


That's it.