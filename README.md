This is a viewer for [3D composites](http://www.unfavorablesemicircle.com/wiki/3D_Composite) of videos. For an alternative viewer you could try [tomasf's 3d composite STLs](http://tomasf.se/projects/semi/stl.html?path=BREADTH_composite3D.stl). [lorpus's fork](https://lorpus.github.io/sketches/ufsc3d/) has some additional composites.

Go to [https://unfavorablesemicircle.github.io/3d-viewer/](https://unfavorablesemicircle.github.io/3d-viewer/) for the online 3d composite viewer.

## Controls ##
- Click and drag to rotate
- Q or Escape: return to main menu
- H: Toggle RGB / HSB mode
- D: Toggle absolute / consecutive difference graphing
- A: Animate; draw points in order over time with alternate color scheme
- Z: Render image from current viewpoint

## To add new composites ##
- Add the image file. It must be a BMP (otherwise the colors will be distorted), and the file name shouldn't have spaces.
- Add the file name to the list in `ufsc3d.pde`, following the format of the others.
- Images larger than 50 MB should be split into smaller files. It's also helpful to split multi-paneled images like HARVEST or GOLDEN into multiple images.
