# **Repository:** `halogas-littlethings-2d-3d-rc`

This is the official data and code repository for the paper:
> **Yasmin, A. and Wulandari, H. R. T. (in preparation)**

---

## Summary

This repository provides all supplementary data, plots, and scripts used in our comparative study of 2D and 3D kinematic modeling techniques. We analyze the rotation curves for a sample of 15 spiral galaxies from the **HALOGAS** survey and 13 dwarf irregular galaxies from the **LITTLE THINGS** survey.

## Repository Contents

This repository is organized as follows:

### `/Data/`
Contains the data point files (`.csv`) used for the analysis. This includes the extracted rotation curve data (Radius, Vrot, error) for each method (2DBarolo, 3DBarolo, 2DiskFit) for both surveys.

### `/Paper-Figures/`
Contains high-resolution versions of the main figures presented in the manuscript (Figure 1 and Figure 2).

### `/Individuals-Galaxy-Plot/`
Contains all supplementary plots for individual galaxies, organized by survey and then by galaxy.
* **/Individuals-Galaxy-Plot/HALOGAS/**: Contains a subfolder for each of the 15 HALOGAS galaxies (e.g., `/NGC2403/`, `/NGC3198/`).
* **/Individuals-Galaxy-Plot/LITTLE-THINGS/**: Contains a subfolder for each of the 13 LITTLE THINGS galaxies (e.g., `/DDO154/`, `/DDO168/`).
* Inside each galaxy's folder, you will find the main plot (e.g., `NGC2403_main.png`) and the corresponding zoom-in plot (`NGC2403_zoom.png`), where applicable.

## Citation

If you use the data or plots from this repository in your research, we kindly ask that you cite our main paper:
> Yasmin, A. and Wulandari, H. R. T. (in preparation)

---

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for full details.
