# PanseMonk

Monte Carlo ray-tracing simulations of spontaneous temperature separation through directional thermal emission and specular reflection.

## Overview

This repository contains the Python simulation code accompanying the manuscript:

**"Spontaneous Temperature Separation by Directional Emission and Specular Reflection"**

Vishwanath H. Dalvi, Sudhir V. Panse and Jyeshtharaj B. Joshi.

The simulations examine radiative energy exchange within an effectively two-dimensional evacuated enclosure consisting of:

- A directionally emissive source maintained at constant temperature.
- A blackbody receiver divided into two thermally isolated sections.
- Perfectly specular reflectors with planar or elliptical geometries.

Monte Carlo ray tracing is used to investigate the development of steady-state temperature differences without external work or active control.

## Requirements

Python 3 with the following packages:

- NumPy
- SciPy
- Matplotlib
- Numba
- randomgen

## Usage

Run the simulation using:

```bash
python pansemonk.py
```

Simulation parameters, including reflector geometry and directional emissivity, can be modified within the script.

## License

This code is distributed under the MIT License. See the `LICENSE` file.

## Correspondence

Vishwanath H. Dalvi  
Institute of Chemical Technology, Mumbai, India  
vh.dalvi@ictmumbai.edu.in
