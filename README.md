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

## Advantages of AIStudio Version

The main advantage of this AIStudio version of the code is the significantly accelerated process of GROMACS source code compilation. Additionally, the AIStudio container retains stored files even when the connection is interrupted, eliminating concerns about data loss.

## Copyright Notice

The primary code for these notebooks was developed by GitHub user [bioinfkaustin](https://github.com/bioinfkaustin). If this code is used in a published work, please cite the GitHub repository at [GROMACS on Colab](https://github.com/bioinfkaustin/gromacs-on-colab). 

For viewing the version of the code executed on Google Colab, please visit: [GROMACS on Colab](https://github.com/bioinfkaustin/gromacs-on-colab).
