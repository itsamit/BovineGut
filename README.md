# BovineGut
To run the code, install COBRApy and the Gurobi/IBM Cplex optimizer.

All the input files and scripts are added to github, which can be executed to reproduce the community models.

GCMs\_Reconstruction Code:
The community modelling code integrates individual models into pairwise community models.

All the individual models are given in the Individual\_GEMs directory.

The script for GCMs\_Reconstruction code has been provided as GCMs\_Reconstruction.ipynb.

The resultant Community model will be generated in the Pairwise\_GCMs directory.

Three\_Membered\_GCM\_Reconstruction Code:
The code for Three-membered community GCMs has also been provided as Three\_Membered\_GCM\_Reconstruction.ipynb.

The Output of the community model will be generated in the Three\_Membered\_GCMs directory.

GEM\_GCM\_Analysis Code:
The code represents the list of media and corresponding boundary conditions used in the construction of individual GEMs. The information on the media conditions is also available in the Supplementary Tables.

The code can be used to perform FBA/FVA, loopless FBA/FVA for measuring the PMA and PGSI.

The code also generates a list of TIC-associated reactions, provides biomass-sensitivity analysis results, a list of transporter reactions, information on compartmentalized flux distribution patterns, and the VFA-associated flux distribution profiles for all the individual and community models.
