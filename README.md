# Sunda_IT_M2
This repository provides sea surface height (SSH) calculation results for the Lesser Sunda Islands region, along with the associated visualization scripts for analyzing and presenting the spatial structure and variability of SSH.

Sunda_result10_180.mat
Contains the computed sea surface height (SSH) fields for the Lesser Sunda Islands (LSI) region. These results serve as the primary diagnostic dataset for examining the spatial organization and variability of SSH signals associated with internal-wave-related processes.

Sunda_flux.mat
Stores the corresponding energy flux estimates derived for the LSI region. This dataset is intended to support analyses of energy pathways and spatial modulation of internal-tide-related fluxes, in conjunction with the SSH fields.

Sunda_M2_PWFvis_1219.m
The main visualization script of the repository.
This program integrates plotting routines compatible with the PWF (Plane Wave Fitting) framework and includes an embedded band-pass filtering module.
Important note: the filter passband must be redefined prior to use, based on the local internal tide wavelength characteristic of the study region, to ensure physical consistency of the extracted signals.

maskCreator.m and generate_etopo_mask.m
Auxiliary functions for constructing and applying topographic masks based on bathymetric data (ETOPO). These routines are used to exclude land and shallow regions, enabling a clearer focus on oceanic signals and their interaction with underlying topography.
