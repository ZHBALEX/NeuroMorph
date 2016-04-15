#### NeuroMorph Import Objects   ([download](http://dstats.net/download/http://github.com/ajorstad/NeuroMorph/raw/master/NeuroMorph_Toolkit/NeuroMorph_Import_Objects.py))
This module is used to import one or many object models from .obj files obtained through 3D image segmentation software (e.g. [ilastik](www.ilastik.org) or [TrakEM2](www.ini.uzh.ch/~acardona/trakem2.html)) into Blender, for use with the other NeuroMorph tools.


#### NeuroMorph Measurement Tools   ([download](http://dstats.net/download/http://github.com/ajorstad/NeuroMorph/raw/master/NeuroMorph_Toolkit/NeuroMorph_Measurement_Tools.py))
This module measures surface areas, volumes, and lengths of regions of meshes specified by a user-defined selection of vertices. New objects are created as children of the original mesh object, and the measurements are stored in appropriate property variables of these children objects in the Geometry Properties panel of the Object context (bottom right of the Blender interface, see documentation for details). Objects are named, optionally, according to a naming convention developed for neural structures. Measurements can be exported into a .txt file that can be read by Excel.


#### NeuroMorph Image Stack Interactions   ([download](http://dstats.net/download/http://github.com/ajorstad/NeuroMorph/raw/master/NeuroMorph_Toolkit/NeuroMorph_Image_Stack_Interactions.py))
This module superimposes images from the original (electron microscopy) image stack onto mesh objects. The images are displayed in the x-y plane, and are uploaded into empty objects in Blender.  Individual points on the images can be selected, and objects containing those points can be retrieved (from the possibly hundreds or thousands of invisible objects in the scene) and made visible, allowing for easy navigation of object connectivity.
