# AST-08 2021 UCSC SIP repo for sharing code

1. Directory descriptions
For descriptions of the purposes of a certain jupyter notebook, read the text at the top of the notebook. Below are descriptions for directories.

mask-plots/*: plots collected from DetectingVariables.ipynb demonstrating relationship of magnitude of median flux from keck DEIMOS spectra against HST 814W magnitude for each of the keck DEIMOS filters (filters begin with mct).

2. Running the code
I use jupyter notebooks on macOS High Sierra. Follow these instructions below to run these notebooks (.ipynb files).

Download Anaconda using this link here . Once Anaconda is fully installed, launch Jupyter Notebook, which should open up a new tab. Check out this pre-tutorial for more information on setting up Jupyter on your computer along with some python tutorials.

On the web browser, navigate to the AST-08-StellarVariability directory and open the DetectingVariables.ipynb notebook. To run this code, you MUST set the path directory for the subMasterSPLASH2.fits file which was separately downloaded to your local directory by setting subMaster_fndir = <pathname> in the code. This line should be towards the top of the notebook. In my case, it is ../subMasterSPLASH2.fits since the fits file is one-level outside the AST-08-StellarVariability directory.
  
