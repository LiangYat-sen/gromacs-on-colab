## GROMACS-on-AIStudio

This repository provides four notebooks for running molecular dynamics simulations on AIStudio.

* `Build_to_AIStudio.ipynb` \
  Installs GROMACS to your AIStudio workspace. Due to AIStudio servers being located in mainland China, GROMACS needs to be manually downloaded and uploaded into the container. The storage in the container is persistent and won't be overwritten.

* `GROMACS_for_CHARMM-GUI.ipynb` \
  Equilibrates a system prepared with [CHARMM-GUI](https://www.charmm-gui.org/). This notebook unpacks a `CHARMM-GUI.tgz` archive from "Solution Builder." Optionally, it can merge in an archive from "Ligand Reader," allowing for piecewise preparation of protein-ligand systems.

* `GROMACS_for_production.ipynb` \
  Starts or resumes a production simulation.

* `Trajectory_analysis_tools.ipynb` \
  Calculates data that can be derived from a production simulation trajectory, such as centroid structures, RMSDs, and interaction energies.

All inputs and outputs are stored in your AIStudio workspace.

