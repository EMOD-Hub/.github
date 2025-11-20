Getting Started with EMOD
==========================
Since EMOD is a stochastic model, you must run numerous realizations of each 
scenario in order to collect proper statistics.  You will likely need a high 
performance computing (HPC) platform to run these simulations.  We support 
SLURM-based HPC as well as a large VM using our Container Platform (see below).

EMOD-HIV
========
To get started using EMOD-HIV, please see the documentation at:

https://emod-hub.github.io/emodpy-workflow/tutorials/get_started/

emodpy-workflow is the main tool for running and configuring EMOD-HIV and these
tutorials will show you how easy it is.

EMOD-Malaria
============
The following link will show you how to run a simple example of EMOD-Malaria on
GitHub Codespaces.

https://github.com/EMOD-Hub/emodpy-malaria/blob/main/getting_started.md

Container Platform
==================
The Container Platform uses the Docker container to allow you to run EMOD on
different platforms.  Via this tool, you can run EMOD on your Windows, Linux, or Mac
laptop.  This can be great for trying things out, but you will likely need something
with more memory and CPU-cores in order run enough simulations.  This usually requires
the need of a SLURM-based HPC, but the Container Platform could allow you to use
a large Virtual Machine.  The link below provides more information:

https://github.com/InstituteforDiseaseModeling/idmtools/tree/main/idmtools_platform_container
