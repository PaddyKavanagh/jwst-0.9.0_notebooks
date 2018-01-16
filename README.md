# jwst-0.9.0_notebooks

This repository contains Jupyter notebooks demonstrating the use of the JWST calibration pipeline (jwst-0.9.0) for MIRI data within python. 

jwst-0.9.0 is a release candidate for Build 7.1.1 of the JWST calibration pipeline can be installed into an Anaconda environment as follows:

conda create -n jwst --file <URL>

where <URL> is:

Linux: http://ssb.stsci.edu/releases/jwstdp/0.9.x/latest-linux

OS X: http://ssb.stsci.edu/releases/jwstdp/0.9.x/latest-osx

The CRDS context should be set to jwst_0425.pmap for this build. Also, standard CRDS environment variables should be set. E.g., for bash:

export CRDS_PATH=/path/to/your/crds

export CRDS_SERVER_URL="https://jwst-crds.stsci.edu"

export CRDS_CONTEXT="jwst_0425.pmap"

