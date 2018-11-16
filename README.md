[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jooh/notebook_bids_OSD2018/master?filepath=os2018_bids.ipynb)

# BIDS demo
[RISE](https://github.com/damianavila/RISE) slideshow notebook for
[BIDS](http://bids.neuroimaging.io/) presentation at 2018 CBU Open Science Day.

This notebook first introduces BIDS, including basic interfacing with BIDS data using
pybids. The second half of the presentation is an interactive tutorial of dcm2bids, a
tool for converting MRI DICOM data to the BIDS format.

# install requirements

Consider whether you can live with the mybinder version linked above, which includes
all dependencies.

For a local install, see environment.yml for the conda environment. You will also need
to activate some notebook extensions, install one linux package (tree), and one node.js
package (bids-validator). To see how this is done, consult the Binder build files
apt-get.txt and postBuild.

At CBU, `conda activate cbu_nipy_1_00` should work.
