SCYLLER — Exploratory & Simulation Tool of Contamination Dispersion

Exploratory and numerical modeling of particle drift (microplastics/pellets) using COPERNICUS (CMEMS): surface currents and Antarctic polar projection visualization. Includes:

Exploratory map of ports/stations near a disaster (Folium).

2D Lagrangian simulation with uo/vo and KDE (density) fields animated on Cartopy.

Author: Raúl Galdeano Pazos (ULisses 2025)
Contact: raulgaldeanopazos@gmail.com
---

Features

NetCDF CMEMS loading (uo, vo) at 6 h, global mesh approx. 1/12°.

Forward Lagrangian simulation with explicit integration and m/s → degrees conversion.

KDE (density) frame-by-frame and GIF animation (matplotlib.animation).

Cartopy SouthPolarStereo projection with coastlines and land/ocean mask.

Folium for exploratory mapping and geodesic distances (geopy).

Requirements

Python 3.10+ recommended.

Main dependencies:

xarray, numpy, scipy, pandas

matplotlib, cartopy, folium

geopy

(optional) seaborn for styles, not required for animation

Note: Cartopy requires system libraries (proj, geos, shapely). It's much simpler in conda.

