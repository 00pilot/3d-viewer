Go to [https://unfavorablesemicircle.github.io/3d-viewer/](https://unfavorablesemicircle.github.io/3d-viewer/) for the online 3d composite viewer.

## Controls ##
- Click and drag to rotate
- Q or Escape: return to main menu
- H: Toggle RGB / HSB mode
- D: Toggle absolute / consecutive difference graphing
- A: Animate; draw points in order over time with alternate color scheme
- Z: Render image from current viewpoint

## To add new composites ##
- Add the image to the root directory. It must be a BMP (otherwise the colors will be distorted), and the file name shouldn't have spaces.
- Add the file name to the list in `ufsc3d.pde`, following the format of the others.
- Images larger than 50 MB should be split into smaller files. It's also helpful to split multi-paneled images like HARVEST or GOLDEN into multiple images.
