# STL Model Files #

These files are simple STL files that represent various mask shapes that DREAM.3D
can use in order to generate synthetic microstructures that adhere to those shapes.

## Cylinder.stl ##

This is a simple cylinder shape that has a Z Height of 30 length units and a radius of
10 length units. The example pipeline located in the Prebuilt Pipelines->Examples->Cylinder_Synthetic
utilizes this file to generate a synthetic microstructure where the cylinder masks
the valid voxels. The model was generated using ParaView 5.6.0


## ASTMD638_specimen ##

This a specimen for tensile testing in accordance with ASTM D638 "Standard Test Method for Tensile Properties of Plastics". It is a Type 1 specimen to be made from rigid plastic.

Tensile testing of RepRap printed specimens is being performed at the Michigan Tech Open Sustainability Technology Research Group http://www.mse.mtu.edu/~pearce/Index.html. Specific information about the testing can be found here http://www.appropedia.org/Mechanical_testing_of_polymer_components_made_with_the_RepRap_3-D_printer.

The bounding box information is:

X: 0 to 180
Y: 0 to 19
Z: 0 to 3.2


## Notes ##

The pipeline uses the *Sample Triangle Geometry on Regular Grid* which can take
a long time to process the __stl__ file. Please give these pipelines a while to
execute.


