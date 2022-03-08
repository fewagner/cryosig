[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fewagner/cryosig/HEAD)

# cryosig

Response model of a cryogenic particle detector equipped with a TES. 

Detector/environment parameters:

C,  # keV / K
Gb, # keV / s / K
G,  # heat cond between components, keV / s / K
lamb,  # thermalization time (s)
eps,  # share thermalization in components
Rs,  # Ohm
Rh,  # Ohm
Rt0,  # Ohm
L,  # H
k,  # 1/K
Tc,  # K
pulser_scale,  # scale factor
pileup_prob,  # percent / record window
tpa_queue,  # V^2
tp_interval,  # s
dac_ramping_speed, # V / s
Ib_ramping_speed, # A / s
xi,  # squid conversion current to voltage, V / A
i_sq,  # squid noise, A / sqrt(Hz)
tes_fluct,  # percent
Tb,  # bath temperature, K

Control parameters:

Ib,  # A
dac,  # V^2

## Usage

Start die notebook in Binder (click on the button) or pull the repository and run the notebook locally. You will have to install all dependencies er hand, i.e. run `! pip install numpy numba scipy tqdm` in an empty cell in the notebook.
