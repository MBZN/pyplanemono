# pyplanemono

[TOC]

Welcome to the PyPlaneMono repository!

This repo contains the code for the PyPlaneMono python package, which is capable of calculating geometrical quantities of a plane grating monochromator (PGM). Colloquially known as the plane mono, PGMs are widely used at synchrotron and free-electron laser facilities which require monochromatic soft X-ray light (50-3000 eV) worldwide. 

To install, we recommend you use PyPi installation:

``` console
$ python -m pip install pyplanemono
```
You should take extra care when you wish to use PyPlaneMono's API with *SHADOW* to perform raytracing; you must use *SHADOW*'s own python environment to do so. (usually a miniconda 3.8 installation)

You can also install from source should you wish to develop PyPlaneMono yourself:
``` console
$ git clone https://github.com/MBZN/pyplanemono pyplanemono
$ cd $! && python -m pip install -e .
```

## Example
To see the full calculations carried out for the B07c beamline at Diamond, please consult [this repository][2].
## References
If you have found this library useful, please consider citing the following:

Wang, P. Y., Bazan da Silva, M., Hand, M., Wang, H., Chang, P., Beilsten-Edmands, V., Kim, T. K., Lee, T.-L., Sawhney, K. & Walters, A. C. (2025). J. Synchrotron Radiat. 32(1), 261–268.
https://doi.org/10.1107/S1600577524011603

A web based version of this library with a GUI is also available on the [Diamond server][1]. An [offline version][3] can also be run on your local machine with python and a modern browser.

[1]:https://pgmweb.diamond.ac.uk
[2]:https://github.com/MBZN/b07c-raytracing/
[3]:https://github.com/DiamondLightSource/pygmweb
