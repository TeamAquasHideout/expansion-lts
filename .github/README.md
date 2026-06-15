# Expansion LTS

This repository serves to be a community-run resource for long term service of pokeemerald-expansion. 

To understand the method for LTS, kindly refer to our [wiki](https://github.com/TeamAquasHideout/expansion-lts/wiki). The current versions being supported are as follows:
- 1.15 (1.15.3)

The repo structure is as follows:
- **master**<br>
  Follows the master branch for pokeemerald-expansion, and thus will always reflect its latest release.
- **Versions (1.15, 1.18, etc)**<br>
  These are the main branches where development for LTS can be found. These branches are stopped at the last patch version of their indicated minor version, and will receive periodic updates as outlined in the wiki above. The Version branches are also split into two: the `_lts` and `_lts_dev` branches.
  - **`lts`**<br>
    Serves as the main branch of a supported version. Pull requests targetting this branch must be pret synchronizations.
  - **`lts_dev`**<br>
    Serves as the development branch of a supported version. Pull requests targetting this branch include: Imports of commits from Expansion and LTS specific bugfixes.


You may find expansion's original repository [here](https://github.com/rh-hideout/pokeemerald-expansion).
