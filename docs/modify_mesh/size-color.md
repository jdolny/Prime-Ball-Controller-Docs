#Changing The Color and Size of The Sphere

The sphere is made of 2 meshes.  An inner mesh and an outer mesh.  This allows you to easily swap out the colors of both the exterior and interior of the sphere.  You could also replace the inner
sphere with some type energy particle for a nice effect.

##Changing the color
1.  Changing the color is straitforward.  Just change the material that is assigned to both the outer and inner mesh

##Changing the size
The best way to change the size of the sphere involves 2 steps.

1.  Change the size of the rigidbody to your desired size, leave the outer and inner mesh alone
2.  Change the ground check radius multiplier to something slightly smaller than your rigidbody size 