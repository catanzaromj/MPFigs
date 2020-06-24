# Code for multiparameter persistence figures

A repository for creating plotly figures for understanding
multiparameter persistent homology. 

## Contents 
* The `Wrinkled_cylinder` directory contains:
  - the main code, `wrinkled_cylinder.py` for making plotly figures of the wrinkled cylinder;
  - a modified version, 'wrinkled_cylinder_with_thresh.py' for making thresholded or sliced versions of the wrinkled cylinder to better understand its persistence. For example, by just change the z-range to [-2,-0.5], one can easily see the hole in the surface, generating a first homology class (see the figure below);
  - a modified version, 'wrinkled_cylinder_slices.py' for just drawing the traces of the deformation; and
  - the 'Output_html_files' directory, containing a bunch of samples of thresholding.


* `Slider_tests` contains (deprecated) code for creating interactive versions of thresholding using native plotly and making a dash app.

* `old_tests` contains misc. old code

### Examples

The wrinkled cylinder

![The wrinkled cylinder](./figs/Wrinkled_cylinder.png)

A thresholded version of the wrinkled cylinder.
 
![A thresholded wrinkled cylinder](./figs/thresh.png)

Interactive versions can be found in [Wrinkled_cylinder/Wrinkled_cylinder.html](Wrinkled_cylinder/Wrinkled_cylinder.html) and [Wrinkled_cylinder/Wrinkled_cylinder_thresh.html](Wrinkled_cylinder/Wrinkled_cylinder_thresh.html).
