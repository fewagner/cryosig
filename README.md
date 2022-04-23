[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fewagner/thermomodel/HEAD)

# thermomodel

Thermal response model of a cryogenic particle detector. 

Detector/environment parameters:

C,  # keV / K
Gb, # keV / s / K
G,  # heat cond between components, keV / s / K
lamb,  # thermalization time (s)
eps,  # share thermalization in components
Tb,  # bath temperature, K

## Usage

Start die notebook in Binder (click on the button) or pull the repository and run the notebook locally. You will have to install all dependencies er hand, i.e. run `! pip install numpy scipy tqdm` in an empty cell in the notebook.
